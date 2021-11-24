# landingpage-clipboard
Challenge project from Frontend Mentor

# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot



### Links

[Solution](https://github.com/zitescody/landingpage-clipboard)
[Live Site](https://zitescody.github.io/landingpage-clipboard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap



### What I learned

I finally learned how to integrate Bootstrap into my web projects. 

```html
<body>
  <main class="container">
    <div class="row justify-content-center" id="one">
        <img class="logo" src="./images/logo.svg" alt="clipboard logo" aria-label="clipboard logo">
    </div>
    <div class="row p-3" id="two">
        <h1 class="title">A history of everything you copy</h1>
        <p class="content">
            Clipboard allows you to track and organize everything you 
            copy. Instantly access your clipboard on all your devices.
        </p>
    </div>
    <div class="row" id="three">
        <div class="col-md" id="button-container">
            <button type="button" class="btn" id="ios">Download for IOS</button>
        </div>
        <div class="col-md" id="button-container">
            <button type="button" class="btn" id="mac">Download for Mac</button>
        </div>
    </div>
    <div class="row p-3" id="four">
        <div class="col">
            <h2 class="section-title">Keep track of your snippets</h2>
            <p class="content">
                Clipboard instantly stores any item you copy in the cloud, 
                meaning you can access your snippets immediately on all your 
                devices. Our Mac and iOS apps will help you organize everything.
            </p>
        </div>
    </div>
    <div class="row" id="five">
        <div class="col-md align-self-center">
            <img class="computer" src="./images/image-computer.png" alt="mac computer" aria-hidden="true">
        </div>
        <div class="col-md" id="aside">
            <div class="subsection">
                <h2 class="sub-section-title">Quick Search</h2>
                <p class="content">
                    Easily search your snippets by content, category, web address, application, and more.
                </p>
            </div>
            <div class="subsection">
                <h2 class="sub-section-title">iCloud Sync</h2>
                <p class="content">
                    Instantly saves and syncs snippets across all your devices.
                </p>
            </div>
            <div class="subsection">
                <h2 class="sub-section-title">Complete History</h2>
                <p class="content">
                    Retrieve any snippets from the first moment you started using the app.
                </p>
            </div>
        </div>
    </div>
    <div class="row p-3" id="six">
        <div class="col">
            <h2 class="section-title">Access Clipboard anywhere</h2>
            <p class="content">
                Whether you're on the go, or at your computer, you can
                access all your Clipboard snippets in a few simple clicks
            </p>
        </div>
    </div>
    <div class="row justify-content-center" id="seven">
        <div class="col-md">
            <img class="mobile" src="./images/image-devices.png" alt="mobile devices" aria-hidden="true">
        </div>
    </div>
    <div class="row p-3" id="eight">
        <div class="col">
            <h2 class="section-title">Supercharge your workflow</h2>
            <p class="content">
                We've got the tools to boost your productivity
            </p>
        </div>
    </div>
    <div class="row p-3" id="nine">
        <div class="col-md align-self-center" id="feature">
            <img class="icon" src="./images/icon-blacklist.svg" alt="blacklist icon" aria-hidden="true">
            <h3 class="feature-title">Create blacklists</h2>
            <p class="content">
                Ensure sensitive information never makes its way to your
                clipboard by excluding certain sources.
            </p>
        </div>
        <div class="col-md align-self-center" id="feature">
            <img class="icon" src="./images/icon-text.svg" alt="paper icon" aria-hidden="true">
            <h3 class="feature-title">Plain text snippets</h2>
            <p class="content">
                Remove unwanted formatting from copied text for a consistent look  
            </p>
        </div>
        <div class="col-md align-self-center" id="feature">
            <img class="icon" src="./images/icon-preview.svg" alt="eye icon" aria-hidden="true">
            <h3 class="feature-title">Sneak preview</h2>
            <p class="content">
                Quick preview of all snippets on your Clipboard for easy access
            </p>
        </div>
    </div>
    <div class="row justify-content-center" id="ten">
        <div class="col-md" id="companies">
            <img class="company-logo" src="./images/logo-google.png" alt="google logo" aria-hidden="true">
        </div>
        <div class="col-md" id="companies">
            <img class="company-logo" src="./images/logo-ibm.png" alt="ibm logo" aria-hidden="true">
        </div>
        <div class="col-md" id="companies">
            <img class="company-logo" src="./images/logo-microsoft.png" alt="microsoft logo" aria-hidden="true">
        </div>
        <div class="col-md" id="companies">
            <img class="company-logo" src="./images/logo-hp.png" alt="hp logo" aria-hidden="true">
        </div>
        <div class="col-md" id="companies">
            <img class="company-logo" src="./images/logo-vector-graphics.png" alt="vg logo" aria-hidden="true">
        </div>
    </div>
    <div class="row p-3" id="eleven">
        <h2 class="subtitle">Clipboard for iOS and Mac OS</h2>
        <p class="content">
            Available for free on the App Store. Download for Mac or iOS,
            sync with iCloud and you're ready to start adding to your clipboard.
        </p>
    </div>
    <div class="row" id="twelve">
        <div class="col-md" id="button-container">
            <button type="button" class="btn" id="ios">Download for IOS</button>
        </div>
        <div class="col-md" id="button-container">
            <button type="button" class="btn" id="mac">Download for Mac</button>
        </div>
    </div>
  </main>
  <footer>
    <div class="row p-3 justify-content-center" id="footer-logo">
        <div class="col-md align-self-center" id="footer-container">
            <img class="logo-small" src="./images/logo.svg" alt="clipboard logo" aria-label="clipboard logo">
        </div>
        <div class="col-md align-self-center" id="footer-container">
            <a class="content" href="#" id="footer-content">FAQs</a><br>
            <a class="content" href="#" id="footer-content">Contact Us</a>
            
        </div>
        <div class="col-md align-self-center" id="footer-container">
            <a class="content" href="#" id="footer-content">Privacy Policy</a><br>
            <a class="content" href="#" id="footer-content">Press Kit</a>
        </div>
        <div class="col-md align-self-center" id="footer-container">
            <a class="content" href="#" id="footer-content">Install Guide</a>
        </div>
        <div class="col-md align-self-center" id="footer-socials">
            <a href="#"><img class="social" src="./images/icon-facebook.svg" alt="facebook logo" aria-label="facebook"></a>
            <a href="#"><img class="social" src="./images/icon-instagram.svg" alt="instagram logo" aria-label="instagram"></a>
            <a href="#"><img class="social" src="./images/icon-twitter.svg" alt="twitter logo" aria-label="twitter"></a>
        </div>
    </div>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Cody Zites</a>.
    </p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
```
```css
:root {
    /*colors*/
    --strongCyan: hsl(171, 66%, 44%);
    --lightBlue: hsl(233, 100%, 69%);
    --darkGrayishBlue: hsl(210, 10%, 33%);
    --grayishBlue: hsl(201, 11%, 66%);
    --white: white;

    /*fonts*/
    --baiJamjuree: 'Bai Jamjuree', sans-serif;
    --baiJamjureeLight: 400;
    --baiJamjureeMedium: 600;

    --h1Color: var(--darkGrayishBlue);
    --h1Weight: var(--baiJamjureeMedium);
    --h1Size: 24pt;

    --h2Color: var(--darkGrayishBlue);
    --h2Weight: var(--baiJamjureeMedium);
    --h2Size: 20pt;

    --h3Color: var(--darkGrayishBlue);
    --h3Weight: var(--baiJamjureeMedium);
    --h3Size: 18pt;

    --pColor: var(--grayishBlue);
    --pWeight: var(--baiJamjureeLight);
    --pSize: 14pt;

    --buttonWeight: 400;
    --buttonSize: 16pt;
    --buttonColor: var(--white);
    --buttonBorder: 1px solid transparent;
    --buttonBorderRadius: 30px;
    --buttonPadding: 15px 25px 15px;
}
```
### Continued development

I want to continue optimizing my layouts for bootstrap integration. I want to become more confident with developing webpages with the framework.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/10989238/center-image-horizontally-within-a-div/34202666) - Helped me center images
- [Box Shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - Box shadows
- [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/) - Bootstrap integration

## Author

- Website - [Cody Zites](https://github.com/zitescody)
- Frontend Mentor - [@zitescody](https://www.frontendmentor.io/profile/zitescody)

