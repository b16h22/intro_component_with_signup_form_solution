# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1).


## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*

### Screenshot

![](./screenshots/desktop_design.png)
![](./screenshots/desktop_active_state.png)
![](./screenshots/mobile_design.png)

### Links

- Solution URL: [Github repo](https://github.com/b16h22/intro_component_with_signup_form_solution)
- Live Site URL: [Github pages](https://b16h22.github.io/intro_component_with_signup_form_solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Javascript

### What I learned

Learned to use For Of loop on the nodelist accessed by querySelecterAll() method.

```js
    const errorMessage = document.querySelectorAll(".error-message");
    const errorIcon = document.querySelectorAll(".error-icon");

    for (let x of errorMessage) {
      x.style.display = "none";
    }

    for (let i of errorIcon) {
      i.style.display = "none";
    }
```

Learned to validate if text input fields are empty and display an error message.

### Useful resources

- [HTML DOM Elements](https://www.w3schools.com/js/js_htmldom_elements.asp) - This helped me learn about HTML DOM elements and methods to access them.
- [JS For Of loop](https://www.w3schools.com/js/js_loop_forof.asp) - This helped me learn about JS For Of loop.
- [RegEx for Email Validation](https://zparacha.com/validate-email-address-using-javascript-regular-expression) - This helped me understand the regEx required for email validation.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)