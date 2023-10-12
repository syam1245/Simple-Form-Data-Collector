
Description:
This project is a straightforward web application that demonstrates the collection of user input from a form. It's designed as a minimalistic example to help beginners grasp the concept of handling form data using JavaScript. The project consists of an HTML file and a JavaScript file that work together to capture and display user-provided information.

Technical Documentation:

1. **HTML Structure (index.html):**
   - The HTML document follows standard structure and includes basic metadata.
   - A form element is defined to enclose input fields and a submit button.
   - Input fields for first name, last name, email, and password are labeled using `<label>` elements.
   - Each input field is assigned a name attribute for identification.
   - The submit button is added to trigger the data collection function.

2. **JavaScript Logic (script.js):**
   - There is a JavaScript function named `getFormData` defined with an event parameter.
   - The function is set to prevent the default form submission action to ensure data is collected without a page reload.
   - It selects the form using `document.forms[0]`.
   - The values entered in the first name, last name, email, and password fields are retrieved.
   - The values are logged to the console to demonstrate the data collection process.

3. **How to Use:**
   - Open the 'index.html' file in a web browser.
   - Fill in the form with your first name, last name, email, and password.
   - Click the 'Submit' button.
   - Open the browser's console (usually F12 or Ctrl+Shift+I) to view the collected data.

4. **Contribution:**
   - Contributions and enhancements to this project are welcome. If you have ideas to improve or extend this example, feel free to fork the repository and submit a pull request.

5. **License:**
   - This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). You can use, modify, and distribute it according to the terms of this license.

