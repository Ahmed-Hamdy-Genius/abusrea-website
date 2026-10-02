# Abusrea Website Clone

A personal website clone built as a step in my front-end learning journey.

This project is based on [Mohamed Abusrea's Personal Website](https://github.com/abusrea/personal-website). I recreated the project while applying what I learned in HTML, CSS, responsive design, Flexbox, CSS Grid, and Sass.

I also added some styling details of my own, including a navigation hover effect and visual feedback for the contact form fields.

## Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Grid
* Responsive Design
* Sass

## What I Learned

This project was my first practical experience with Sass.

I learned how to:

* Organize styles into multiple Sass partials
* Use `@use` and `@import`
* Work with Sass variables
* Create and reuse mixins
* Structure a larger stylesheet into separate components
* Compile Sass into CSS

I also practiced building responsive layouts using CSS Grid and Flexbox, as well as using CSS pseudo-classes and pseudo-elements for interactive styling.

## Added Features

In addition to recreating the original project, I added a few styling details:

### Navigation Hover Effect

When hovering over a navigation link, the other links become less visible to make the active link stand out.

### Contact Form Validation Feedback

The contact form uses HTML validation with custom CSS styling:

* `*` appears when a required field is not valid.
* `✓` appears when the field becomes valid.
* Valid input fields receive a green bottom border.

The phone field also uses a validation pattern for the required format.

## Main Features

* Responsive layout for different screen sizes
* CSS Grid and Flexbox layout
* Responsive navigation with a mobile menu
* Light and dark theme switch
* Smooth scrolling
* Background video
* Multiple website sections including:

  * Bio
  * Skills
  * Media
  * Projects
  * Clients
  * Contact
* HTML form validation with custom visual feedback

## Project Structure

```text
abusrea-website/
│
├── components/
│   ├── _bio.scss
│   ├── _clients.scss
│   ├── _contact.scss
│   ├── _footer.scss
│   ├── _global.scss
│   ├── _header.scss
│   ├── _media.scss
│   ├── _mixins.scss
│   ├── _projects.scss
│   ├── _responsive.scss
│   ├── _reset.scss
│   ├── _skills.scss
│   ├── _theme.scss
│   └── _variables.scss
│
├── images/
├── styles/
│   └── style.css
│
├── index.html
├── results.html
├── style.scss
└── README.md
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/ahmed-hamdy-genius/abusrea-website.git
```

Open the project folder and launch `index.html` in your browser.

To work with the Sass source files, compile `style.scss` into `styles/style.css` using Sass.

## Credits

Original project by [Mohamed Abusrea](https://github.com/abusrea).

This repository is my own implementation of the project as part of my front-end learning journey, with additional styling and interaction details added by me.

## Live Preview

[Click me](https://ahmed-hamdy-genius.github.io/abusrea-website/) to preview the website.
