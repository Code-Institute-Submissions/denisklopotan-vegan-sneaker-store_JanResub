# Testing

## Table of contents

1. [Validator Testing](#validator-testing)
    - [HTML](#html)
    - [CSS](#css)
    - [Python](#python)
    - [JavaScript](#javascript)
2. [Performance Testing](#performance-testing)
    - [Lighthouse](#lighthouse)
3. [Browser Testing](#browser-testing)
4. [Device Testing](#device-testing)
5. [Manual Testing](#manual-testing)
6. [Unit Testing](#unit-testing)
7. [Bugs](#bugs)

## Validator Testing

### HTML

To check markup validity of Web documents as HTML, we used: [W3C Markup Validation Service](https://validator.w3.org/).

![](media/testing/html.png)

### CSS

To check Cascading Style Sheets (CSS) validity we used: [W3C CSS Validation Service - Jigsaw](https://validator.w3.org/).

![](media/testing/css.png)

### Python

To check our Python code against style conventions in PEP 8 we used: [pep8 - Python style guide checker](https://pypi.org/project/pep8/).

Since online validator was not available at this point we needed to install app in our project and perform validation trough terminal.
Documentation [page](https://pep8.readthedocs.io/en/release-1.7.x/)

...maybe try https://www.pythonchecker.com/ ?

![](media/testing/python.png)

### JavaScript

To detect errors and potential problems in our JavaScript code we used: [JSHint](https://jshint.com/)

https://codebeautify.org/jsvalidate ??

![](media/testing/js.png)

## Performance Testing

### Lighthouse

"Lighthouse is an open-source, automated tool for improving the performance, quality, and correctness of your web apps.

When auditing a page, Lighthouse runs a barrage of tests against the page, and then generates a report on how well the page did. From here you can use the failing tests as indicators on what you can do to improve your app."

Lighthouse comes integrated by default as part of development tools (DevTools) in Google Chrome browser. You can read more about it [here](https://developer.chrome.com/docs/lighthouse/overview/).

![](media/testing/lighthouse.png)

## Browser Testing

We tested website on following browsers:

- [Google Chrome](https://www.google.com/chrome/)
- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/browsers/)
- [Microsoft Edge](https://www.microsoft.com/en-us/edge?form=MA13FJ)
- [Opera](https://www.opera.com/)
- [Brave](https://brave.com/)

Everything worked correctly.

## Device Testing

Website was tested on these available devices:

- Main working laptop: Lenovo Ideapad 3 Chromebook
- Main smartphone: Google Pixel 6 Pro
- Secondary smartphone: LG V30
- Public library desktop computer

Everything performed correctly:  
Loading website, navigating, opening links, shopping, authenticating as user or admin.. and finally, website behaved responsively on all devices.

## Manual Testing

Manual testing was performed alongside with readme section of **Features**.
All features listed there where proven to work as espected, as follows:

Homepage with:
- Navbar
  - All navbar dropdown menus and search bar work as expected, except Favorites feature which is to be implemented
- Body
   - Shop now button brings us to the products page
- Footer
   - media links, contact and mailchimp form works

Products:
- Products page
   - Clicking on individual products brings us Product detail page
- Product detail
   - Choosing sizes quantity and adding to bag works properly

Accounts:
- Register / Login
   - New users can register and registered log in
- Product managment
   - Updating product fields works as expected
- My profile
   - On personal profile details can be updated
- Logout

Purchasing
- Shopping bag
   - Updating item quantity in bag works
- Checkout form is working properly and orders are placed

Contact us form

To be implemented:
- Favorites feature is currently not working so link is not functional

## Unit Testing

[⮪ Return back to readme](README.md) | [Back to Top 🠕](#testing)



