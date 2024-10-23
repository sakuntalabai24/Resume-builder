## Resume Generator Documentation

This documentation describes the files and their functionalities for the resume generator application.

**Files:**

1. **form.html:** This file contains the HTML form used to update the resume information.
2. **resume.html:** This file displays the generated resume based on the provided information.
3. **style.css:** Contains the CSS styles for both `form.html` and `resume.html` files.
4. **script.js:** Contains JavaScript functions for updating the resume content based on the form input.

**Breakdown:**

**form.html:**

* **HTML Structure:**
    * The file includes a basic HTML structure with the `<head>` and `<body>` elements.
    * Inside the `<head>` section, there is a `<style>` tag with CSS rules for styling the form elements.
    * The `<body>` section contains the main content:
        * A `div` with the class "resume-container" for the resume content.
        * A `section` with the class "profile" for the profile information (name, image, contact, skills, expertise).
        * A `section` with the class "contact" for the professional information (objective, experience, education, skills).
        * A `form` element with input fields for updating resume information.
        * A JavaScript code block within `<script>` tags for handling form submission and updating the resume content.

* **Form Elements:**
    * The form includes the following input fields:
        * **Name:** A text input to enter the user's name.
        * **Image:** A text input to enter the URL of the profile image.
        * **Phone:** A text input for entering the phone number.
        * **Email:** An email input for entering the email address.
        * **Objective:** A `textarea` for entering the user's career objective.
        * **Education:** A text input for entering education details.
        * **Skills:** A text input for entering comma-separated skills.

* **JavaScript Functionality:**
    * The `updateResume()` function is called when the "Update Resume" button is clicked.
    * This function retrieves the values from the form inputs.
    * It updates the corresponding elements in the "profile" and "contact" sections with the entered information.
    * For skills, it dynamically creates a list and adds each skill as a list item.

**resume.html:**

* **HTML Structure:**
    * The file includes the basic HTML structure similar to `form.html`.
    * The `<head>` section includes a link to the external `style.css` file for styling.
    * The `<body>` section contains the main resume content:
        * A `div` with the class "resume-container" for the resume content.
        * Two `sections` with the classes "profile" and "contact" for displaying profile and professional information, respectively.

* **Content:**
    * The "profile" and "contact" sections display pre-filled information.
    * The "skills" section shows a list of pre-defined soft and technical skills.
    * A button with the text "Generate-Resume" is included to navigate to the "form.html" page.

**style.css:**

* **CSS Styling:**
    * This file contains the CSS styles used to format the layout and appearance of both `form.html` and `resume.html` pages.
    * The styles are applied using classes and IDs defined in the HTML.
    * The CSS includes rules for:
        * Body background color and font style.
        * The "resume-container" layout (flexbox for two-column display).
        * Styling for the "profile" and "contact" sections (background colors, padding, borders).
        * Formatting of profile photo, headings, paragraphs, lists, and form elements.
        * Hover effects for elements like image and button.

**script.js:**

* **JavaScript Functionality:**
    * This file contains the JavaScript functions used in the `form.html` file.
    * The `updateResume()` function handles form submission and updates the resume content dynamically based on the user input.

**How to Use:**

1. Open the `resume.html` file in a web browser.
2. Click the "Generate-Resume" button to navigate to the `form.html` page.
3. Enter the required information in the form.
4. Click the "Update Resume" button to update the resume content in `resume.html`.

This structure allows the user to update the resume content dynamically, without having to manually edit the HTML code of the `resume.html` file.
