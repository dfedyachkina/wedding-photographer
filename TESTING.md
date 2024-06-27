# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation


### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | 404.html | ![screenshot](documentation/validation/validation-404-page.png) | |
|  | confirmation.html | ![screenshot](documentation/validation/validation-confirmation-page.png) | |
|  | index.html | ![screenshot](documentation/validation/validation-home-page.png) | |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| assets | style.css | ![screenshot](documentation/validation/validation-css.png) | |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Confirmation | 404 | Notes |
| --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/browser-chrome-home.png) | ![screenshot](documentation/browsers/browser-chrome-confirmation.png) | ![screenshot](documentation/browsers/browser-chrome-404.png) | Works as expected |
| Firefox | ![screenshot](documentation/browsers/browser-firefox-home.png) | ![screenshot](documentation/browsers/browser-firefox-confirmation.png) | ![screenshot](documentation/browsers/browser-firefox-404.png) | Works as expected |
| Edge | ![screenshot](documentation/browsers/browser-edge-home.png) | ![screenshot](documentation/browsers/browser-edge-confirmation.png) | ![screenshot](documentation/browsers/browser-edge-404.png) | Works as expected |

## Responsiveness


I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Confirmation | 404 | Notes | 
| --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsiveness/responsive-mobile-home.png) | ![screenshot](documentation/responsiveness/responsive-mobile-confirmation.png) | ![screenshot](documentation/responsiveness/responsive-mobile-404.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsiveness/responsive-tablet-home.png) | ![screenshot](documentation/responsiveness/responsive-tablet-confirmation.png) | ![screenshot](documentation/responsiveness/responsive-tablet-404.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsiveness/responsive-desktop-home.png) | ![screenshot](documentation/responsiveness/responsive-desktop-confirmation.png) | ![screenshot](documentation/responsiveness/responsive-desktop-404.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-mobile-home-page.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-home-page.png) | Some minor warnings |
| Confirmation | ![screenshot](documentation/lighthouse/lighthouse-mobile-confirmation-page.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-confirmation-page.png) | Some minor warnings |
| 404 | ![screenshot](documentation/lighthouse/lighthouse-mobile-404-page.png) | ![screenshot](documentation/lighthouse/lighthouse-desktop-404-page.png) | Some minor warnings |


## Bugs

- The favicon hasn't been load
![screenshot](documentation/bugs/bug01.png)

Accidently I added link tags of favicons to the header tag. It has been fixed by moving it to the head tag.


- The navigation bar hides some information in the section when you click to see this section on the navigation bar. 
![screenshot](documentation/bugs/bug02.png)

It has been fixed by set up scroll margin top among sections on style.css.

### Unfixed Bugs


> [!NOTE]  
> There are no remaining bugs that I am aware of.
