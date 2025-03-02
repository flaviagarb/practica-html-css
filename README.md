# Nick Miller Portfolio

> A practice project to create a complete portfolio featuring the fictional character **Nick Miller**.  

---

## Description

This project was created to practice and strengthen skills in web layout, responsive design, and form validation using HTML5. In addition, it demonstrates the implementation of CSS animations for progress bars and an adaptive banner that changes based on screen size.

The portfolio includes:

- A **header** with a navigation bar linking to different sections of the portfolio.
- A section with a **description** of Nick Miller and animated progress bars representing skills.
- A **banner** with a background image that changes on mobile devices (using media queries or responsive images).
- A **contact form** with proper input types and HTML validations, including:
  - First Name (required)
  - Last Name (required)
  - Phone Number (required)
  - Radio buttons for "How did you meet me?" (required options: University, Keepcoding Kick-off, School, On GitHub)
  - A GitHub tag input validated with the regex `^@[^\s]+` (for @username)
  - A textarea for additional user information (max 180 characters, required)
  - A newsletter subscription checkbox
  - A Save (submit) button and a Reset button
- A **footer** with external links to social networks.
- A burguer menu only with CSS and html, using input checkbox for responsive mobile.
- An additional page: Projects, featuring a **video** that plays on entry and appears with a fade-in animation and displaying a grid layout of projects.
- An additional page 404. 
- Deployment on Github pages.

---

## Table of Contents

1. [Installation](#installation)
2. [How to Use](#how-to-use)
3. [Key Features](#key-features)
4. [Credits](#credits)

---

## Installation

To clone this project and run it locally, follow these steps:

1. **Clone the repository**:
   
   ```
   git clone git@github.com:flaviagarb/practica-html-css.git
   ```

2. **Open index.html**:

You can open it directly by double-clicking the file or by using an extension like Live Server in VSCode

3. **Open website link directly**:

You can open the website here: https://flaviagarb.github.io/practica-html-css/

---

## Key Features

- **CSS Animations:**
  - Progress bars animate from 0% to their target value.
  - Smooth hover transitions on navigation links.

- **Responsive Design:**
  - Media queries adjust the banner and navigation for mobile devices.

- **Form Validation:**
  - Correct input types (e.g., `tel`, `text`, `url`) and HTML attributes like `required`, `pattern`, and `maxlength` ensure data integrity.
  - Regular expression validation for the GitHub tag (`@username`).

- **External Links:**
  - The footer contains links to social networks such as Twitter, GitHub, and LinkedIn.

- **(Optional) Burger Menu with Pure CSS:**
  - Uses an `input type="checkbox"` and a corresponding `label` to toggle navigation without JavaScript.

## How to Use

1. **Main Navigation**
   - The header contains navigation links to various sections (e.g., Skills, Contact).
   - On smaller screens, these links can be hidden or replaced with an optional burger menu.

2. **Skills Section**
   - Check out the animated progress bars that represent Nick Miller’s skills.
   - Each bar gradually fills up to visually demonstrate proficiency levels.

3. **Contact Form**
   - Fill in all required fields: first name, last name, phone number, how you met Nick Miller, GitHub tag (validated with regex `^@[^\s]+`), and additional information.
   - Optionally subscribe to the newsletter via the checkbox.
   - Use the Save button to submit or the Reset button to clear the form.

4. **Video Page**
   - Contains a video that plays automatically and appears with a fade-in effect.

5. **Projects Page**
   - Displays a grid of projects, showcasing layouts achieved with CSS Grid.

## Credits

- **Author**: Flavia Garbetta

This project deepened my knowledge of HTML, CSS animations, and responsive design.  

- **Referenced Resources**:

  - Official MDN Web Docs
  - Tutorials and guides from freeCodeCamp

