# Development Process & Future Improvements

## Development Workflow

### Step 1: Structural Foundation
I started by creating the HTML5 skeleton. I prioritized semantic tags (`<header>`, `<section>`, `<footer>`) over generic `<div>` tags to improve SEO, code readability and accessibility.
* *Key Decision:* I made specific div wrappers so i could style them later with minimal problems.

### Step 2: Creating the actual css file and adding it on
I wanted a unique visual style.
* **Display choice** I structured most of the sections to use the display flex for simple visuals and responsive layout.
* **Animation:** I defined a custom `@keyframes colorChange` animation to shift the colors of the text, creating a cool looking page.
* **Backtotop** I added a back to top button and a good navbar for easy access of different parts of the website.

### Step 3: Responsiveness
Finally, I added Media Queries.
* **Challenge:** The desktop view was great but the phone or smaller screens needed to be made responsive.
* **Solution:** I implemented a `@media (max-width: 480px and 768px)` rule to increase the container widths to match on smaller devices.

## Future Improvements

While the current version is fully functional, I plan to implement the following features in the next version:

1.  **JavaScript Form Validation:** currently, the contact section is static. I want to add a functional input form that validates email addresses before sending.
2.  **Dark/Light Mode Toggle:** A switch to allow users to toggle between the current light theme and a dark, high-contrast theme.
3.  **Project Responsiveness** Clicking on a project should make the clicker be able to access the exact git repository where the project is located.