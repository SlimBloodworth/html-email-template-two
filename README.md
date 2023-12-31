## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Tested with](#tested-with)
  - [Important notes about html email code](#important-notes-about-html-email-code)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

- This is an HTML email template used to facilitate a workshop.
- More detailed instructions and information can be viewed in the [notes.txt file](./notes.txt).

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size.

### Screenshot

- ![desktop](./screenshot.jpg)
- ![tablet](./screenshot.jpg)
- ![mobile](./screenshot.jpg)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- This follows a workflow of build and test:
- Work structurally leaving in all table borders and cell background colors to help more clearly see what is being created, then removing them at the end.
- Work until a minor development milestone is reached, then run a test.
- Run tests through validator, accessibility checker, and spam checker.
- First: Build the skeleton - then test.
- Next: Add content - then test (also test for spam score).
- Next: Style colors and fonts - then test.
- Next: Remove borders and backgrounds - then test.

### Built with

- HTML5 markup
- CSS
- Mobile-first workflow

#### Tested with

- [Litmus PutsMail](https://www.putsmail.com/)
- [Validator - w3.org](https://validator.w3.org)

### Important notes about html email code

In HTML emails we still use XHTML Transitional 1.0 as our document type as it is the most compatible document type across email clients:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

Will need to add xmls="http://www.w3.org/1999/xhtml" to the html tag:

```html
<html lang="en" xmls="http://www.w3.org/1999/xhtml">
```

Will also need to add xmlns:o="urn:schemas-microsoft-com:office:office" to the html tag to insure code gets interpreted correctly for Microsoft Outlook:

```html
<html lang="en" xmls="http://www.w3.org/1999/xhtml" xmlns:o="urn:schemas-microsoft-com:office:office">
```

Adding http-equiv="Content-Type" content="text/html" tells the destination rendering engine how to process text and special characters for HTML emails:

```html
<meta http-equiv="Content-Type" content="text/html" charset="UTF-8">
```

Add meta name="x-apple-disable-message-reformatting" to stop apple from adjusting sizes in their mail apps.

```html
<meta name="x-apple-disable-message-reformatting">
```

Adding the following code ensures that PNG images are displayed correctly for Outlook on Windows>

```html
<!--[if mso]> 
<noscript> 
<xml> 
<o:OfficeDocumentSettings> 
<o:PixelsPerInch>96</o:PixelsPerInch> 
</o:OfficeDocumentSettings> 
</xml> 
</noscript> 
<![endif]-->
```

### Continued development

- TBA

### Useful resources

- [Validator - w3.org](https://validator.w3.org) - Validator used to catch mistakes and iron out details.
- [imgbb](https://imgbb.com/) - Free image hosting.
- [Entity Codes](https://entitycode.com/) - Entity Code Cheat Sheet.
- [What You Should Know About HTML Email](https://webdesign.tutsplus.com/what-you-should-know-about-html-email--webdesign-12908t) - Great article on things to know.
- [envato tuts+: Mastering HTML Email](https://webdesign.tutsplus.com/series/mastering-html-email--webdesign-17696) - A wonderful guide to learning HTML email development.
- [Email Accessibility Article](https://webdesign.tutsplus.com/a-beginners-guide-to-email-accessibility--cms-31240t) - A great article on accessibility in emails .
- [Litmus PutsMail](https://www.putsmail.com/) - Litmus email testing.

## Author

- Website - [Michelle Renee](https://michellerenee.dev)
- Facebook - [Creative Software Solutions](https://www.facebook.com/profile.php?id=100073842390690)
- Twitter - [@michellere57052](https://twitter.com/michellere57052)
- CodePen - [@slimbloodworth](https://codepen.io/slimbloodworth)
- LinkedIn - [Michelle Renee](https://www.linkedin.com/in/michelle-renee-99b455187/)
- GitHub - [@slimbloodworth](https://github.com/SlimBloodworth)

## Acknowledgments

- [Nicole Merlin](https://webdesign.tutsplus.com/what-you-should-know-about-html-email--webdesign-12908t) - For a wonderful and useful article!
