# Testing

> [!NOTE]
> Return back to the [README.md](README.md) file.

I have conducted enough manual testing to and believe that the site works well. All sections like navbar buttons and booking page works well as expected. The images in the carousel also shows well and all other images are presented well. The website is intuitive for the user experience and users can easily see the service provided and click on the booking page when needed, the contact details in the footer section and the about us section and team members can be seen easily. 

## Code Validation

### HTML
Index HTML, Booking, and Workshop pages results are positive: 
- https://validator.w3.org/nu/?doc=https://mairima.github.io/photography/index.html

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [404.html](https://github.com/mairima/photography/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://mairima.github.io/photography/404.html) | ![screenshot](documentation/validation/html--404.png) 
|  | [booking.html](https://github.com/mairima/photography/blob/main/booking.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://mairima.github.io/photography/booking.html) | ![screenshot](documentation/validation/html--booking.png)
|  | [index.html](https://github.com/mairima/photography/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://mairima.github.io/photography/index.html) | ![screenshot](documentation/validation/html--index.png)
|  | [workshop.html](https://github.com/mairima/photography/blob/main/workshop.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://mairima.github.io/photography/workshop.html) | ![screenshot](documentation/validation/html--workshop.png)
![alt text](image-1.png)

### CSS

The Jigsaw validator for the page is positive without any errors. 

- https://jigsaw.w3.org/css-validator/validator?uri=https://mairima.github.io/photography

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/mairima/photography/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://mairima.github.io/photography) | ![screenshot](documentation/validation/css-assets-style.png) | Notes (if applicable) |


## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/responsiveness/mobile-home.png) | ![screenshot](documentation/responsiveness/tablet-home.png) | ![screenshot](documentation/responsiveness/desktop-home.png) | Works as expected |
| Gallery | ![screenshot](documentation/responsiveness/mobile-gallery.png) | ![screenshot](documentation/responsiveness/tablet-gallery.png) | ![screenshot](documentation/responsiveness/desktop-gallery.png) | Works as expected |
| Signup | ![screenshot](documentation/responsiveness/mobile-signup.png) | ![screenshot](documentation/responsiveness/tablet-signup.png) | ![screenshot](documentation/responsiveness/desktop-signup.png) | Works as expected |
| Confirmation | ![screenshot](documentation/responsiveness/mobile-confirmation.png) | ![screenshot](documentation/responsiveness/tablet-confirmation.png) | ![screenshot](documentation/responsiveness/desktop-confirmation.png) | Works as expected |
| 404 | ![screenshot](documentation/responsiveness/mobile-404.png) | ![screenshot](documentation/responsiveness/tablet-404.png) | ![screenshot](documentation/responsiveness/desktop-404.png) | Works as expected |
![Mockup image with techsini](image-2.png)
## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Safari | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/firefox-home.png) | ![screenshot](documentation/browsers/safari-home.png) | Works as expected |
| Gallery | ![screenshot](documentation/browsers/chrome-gallery.png) | ![screenshot](documentation/browsers/firefox-gallery.png) | ![screenshot](documentation/browsers/safari-gallery.png) | Works as expected |
| Signup | ![screenshot](documentation/browsers/chrome-signup.png) | ![screenshot](documentation/browsers/firefox-signup.png) | ![screenshot](documentation/browsers/safari-signup.png) | Works as expected |
| Confirmation | ![screenshot](documentation/browsers/chrome-confirmation.png) | ![screenshot](documentation/browsers/firefox-confirmation.png) | ![screenshot](documentation/browsers/safari-confirmation.png) | Works as expected |
| 404 | ![screenshot](documentation/browsers/chrome-404.png) | ![screenshot](documentation/browsers/firefox-404.png) | ![screenshot](documentation/browsers/safari-404.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/mobile-home.png) | ![screenshot](documentation/lighthouse/desktop-home.png) |
| Gallery | ![screenshot](documentation/lighthouse/mobile-gallery.png) | ![screenshot](documentation/lighthouse/desktop-gallery.png) |
| Signup | ![screenshot](documentation/lighthouse/mobile-signup.png) | ![screenshot](documentation/lighthouse/desktop-signup.png) |
| Confirmation | ![screenshot](documentation/lighthouse/mobile-confirmation.png) | ![screenshot](documentation/lighthouse/desktop-confirmation.png) |
| 404 | ![screenshot](documentation/lighthouse/mobile-404.png) | ![screenshot](documentation/lighthouse/desktop-404.png) |
![Lighthouse result](image-3.png)

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
| Home | Feature is expected to display examples of why users should join. | Verified that the page displays the Firms mission and purpose in a clear and concise manner. | The mission and purpose were displayed as expected. | ![screenshot](documentation/defensive/home.png) |
| | Feature is expected to have accessible navigation links. | Checked navigation links for correct functionality and accessibility. | Navigation links were functional and accessible. | ![screenshot](documentation/defensive/navigation.png) |
| | Feature is expected to be fully responsive. | Resized the browser window and tested on multiple devices (mobile, tablet, desktop). | The page was responsive across all tested screen sizes. | ![screenshot](documentation/defensive/responsive.png) |
| Services | Feature is expected to display details of different services offered. | Verified that the page lists all services with relevant details. | Details were displayed as expected. | ![screenshot](documentation/defensive/events.png) |
| Workshop | Feature is expected to showcase a gallery of actual workshops and short description. | Verified that the Workshop contains clear images and text that aren't stretched, pixelated, and fully responsive. | Images are properly sized, and respond well to different device sizes. | ![screenshot](documentation/defensive/gallery.png) |
| Booking| Feature is expected to enforce valid input types for each field. | Entered invalid data (e.g., random text in an email field, numbers in a name field, etc.). | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/signup02.png) |
| Social Links | Feature is expected to include working links to the club’s social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | ![screenshot](documentation/defensive/socialmedia.png) |
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/test`) to test error handling. | A custom 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.png) |

## User Story Testing


| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user | I would like to see examples of services i can book | so that I can decide what service is interesting for me. | ![screenshot](documentation/features/feature01.png) |
| As a user | I would like to Know how to book for a service| so that I can inform the Firm of my booking efficiently | ![screenshot](documentation/features/feature02.png) |
| As a user | I would like to see the deatils of contact| so that I can get in contact if needed. | ![screenshot](documentation/features/feature03.png) |
| As a user | I would like to view a gallery elements| So that i can have a reference of what can be offered | ![screenshot](documentation/features/feature04.png) |
| As a user | I would like assess the site on varipus browsers or any other device | so i can easily use the site no matter the browser with which i access it. | ![screenshot](documentation/features/feature05.png) |
| As a user | I would like to follow the Firm on various platforms (e.g., Instagram, Facebook, Twitter) | so that I can stay updated with Firms services and events. | ![screenshot](documentation/features/feature06.png) |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. | ![screenshot](documentation/features/feature07.png) |
| As a user | I would like to see a 404 error page if I get lost | so that it's obvious that I've stumbled upon a page that doesn't exist. | ![screenshot](documentation/features/feature08.png) |

## Bugs

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3Amairima%2Fphotography%20label%3Abug&label=bugs)](https://www.github.com/mairima/photography/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/mairima/photography/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/mairima/photography/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/bugs/gh-issues-closed.png)

### Unfixed Bugs
currently all test have been positively evaluated.

[![GitHub issues](https://img.shields.io/github/issues/mairima/photography)](https://www.github.com/mairima/photography/issues)

Any remaining open issues can be tracked [here](https://www.github.com/mairima/photography/issues).

![screenshot](documentation/bugs/gh-issues-open.png)

### Known Issues

| Issue | Screenshot |
| --- | --- |
| On devices smaller than 375px, the page starts to have horizontal `overflow-x` scrolling. | ![screenshot](documentation/issues/overflow.png) |
| When validating HTML with a semantic `<section>` element, the validator warns about lacking a header `h2-h6`. This is acceptable. | ![screenshot](documentation/issues/section-header.png) |

> [!IMPORTANT]
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

