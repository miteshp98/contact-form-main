# Frontend Mentor - Contact form solution

This is a solution to the [Contact form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

## Features

- **CSS Flexbox:** The layout of the form is designed using CSS Flexbox, ensuring a responsive and flexible design.
- **Hover Effects:** Added hover effects to enhance the user experience and provide visual feedback.
- **JavaScript Validation:** Includes validation for form inputs such as email and names to ensure correct data entry before form submission.

## Technologies Used

- HTML
- CSS (Flexbox)
- JavaScript

## Validation Features

- **Email Validation:** Ensures the email address entered is in the correct format.
- **Name Validation:** Checks that the name fields are not empty and contain only valid characters.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
submitBtn.addEventListener("click", function (e) {
  const isNameValid = checkValidName();
  const isEmailValid = checkValidEmail();
  const isQueryTypeCheck = checkQueryType();
  const isMessageValid = checkMessage();
  const isConsentChecked = checkConsentChecked();

  if (
    !isNameValid ||
    !isEmailValid ||
    !isQueryTypeCheck ||
    !isMessageValid ||
    !isConsentChecked
  ) {
    e.preventDefault();
  } else {
    e.preventDefault();
    document.querySelector(".success-wrap").classList.add("success-dropdown");

    setTimeout(() => {
      document
        .querySelector(".success-wrap")
        .classList.remove("success-dropdown");
    }, 4000);
  }
});
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

- Improved CSS: Enhance the design with more advanced CSS techniques and better responsiveness.
- Advanced JavaScript Logic: Implement more sophisticated form validation and user feedback mechanisms.
- Learning ReactJS: Transition the project to use ReactJS for a more dynamic and scalable user interface. This will include:

  - Component-based architecture for better code organization.
  - State management using React hooks.
  - Improved user experience with real-time validation feedback.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Udemy Webdevlopment](https://www.udemy.com/share/101W9C3@2s1lShiGH32a3OJHMYullps9bvMmvxO_kykXK5ZGloqkGQDHawnryvbZtrMeQ8y81A==/)

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Mitesh Panchal](https://miteshp98.github.io/portfolio-website/)
- Frontend Mentor - [@miteshp98](https://www.frontendmentor.io/profile/miteshp98)
- Linkedin - [@Mitesh Panchal](https://www.linkedin.com/in/mitesh-panchal-356558126/)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Thanks to the challenge provider for creating this opportunity to apply and improve my frontend development skills.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
