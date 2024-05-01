# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.


## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | index.html | ![screenshot](documentation/validation/path-to-screenshot.png) | |
|  | book-now.html | ![screenshot](documentation/validation/path-to-screenshot-b.png) | |
|  | tour-plans.html | ![screenshot](documentation/validation/path-to-screenshot-t.png) | |
|  | confirmation.html | ![screenshot](documentation/validation/path-to-screenshot-c.png) | |
|  | 404.html | ![screenshot](documentation/validation/path-to-screenshot-4.png) | |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| assets | style.css | ![screenshot](documentation/validation/css-v-index.png) | |

The only error that appears in the test is from the code imported from the fancyapps.com to build the gallers section 

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | tour-plans | BookNow |
| --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/validation/chrome.png) | ![screenshot](documentation/validation/chrome2.png) | ![screenshot](documentation/validation/chrome3.png) | ![screenshot](documentation/validation/chrome4.png) |
| Firefox | ![screenshot](documentation/validation/firefox.png) | ![screenshot](documentation/validation/firefox2.png) | ![screenshot](documentation/validation/firefox3.png) | ![screenshot](documentation/validation/firefox4.png) | Works as expected |
| Safari | ![screenshot](documentation/validation/safari.png) | ![screenshot](documentation/validation/safari2.png) | ![screenshot](documentation/validation/safari3.png) | ![screenshot](documentation/validation/safari4.png) | Minor CSS differences |
| Opera | ![screenshot](documentation/validation/opera.png) | ![screenshot](documentation/validation/opera2.png) | ![screenshot](documentation/validation/opera3.png) | ![screenshot](documentation/validation/opera4.png) | Minor differences |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Tours plans | BookNow |
| --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/validation/mob1.png) | ![screenshot](documentation/validation/mob2.png) | ![screenshot](documentation/validation/mob4.png) | ![screenshot](documentation/validation/mob5.png) |
| Tablet (DevTools) | ![screenshot](documentation/validation/tab-1.png) | ![screenshot](documentation/validation/tab-2.png) | ![screenshot](documentation/validation/tab-3.png) | ![screenshot](documentation/validation/tab-4.png) |
| Desktop | ![screenshot](documentation/validation/chrome.png) | ![screenshot](documentation/validation/chrome2.png) | ![screenshot](documentation/validation/chrome3.png) | ![screenshot](documentation/validation/chrome4.png)  |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/testing/home-M.png) | ![screenshot](documentation/testing/home-D.png) | Some minor warnings |
| Tours | ![screenshot](documentation/testing/tour-M.png) | ![screenshot](documentation/testing/tour-D.png) | Some minor warning|
| Booknow | ![screenshot](documentation/testing/book-M.png) | ![screenshot](documentation/testing/book-D.png) | Slow response time due to large images |

