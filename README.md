# Awak_Assignment
# Login Page Project

This project is a simple login page built using HTML, CSS, and JavaScript. The page includes form validation, error handling, and a mock API call for user login.

## Project Structure

- `index.html`: The main HTML file containing the structure of the login form.
- `index.css`: The CSS file providing styles for the login form and page layout.
- `index.js`: The JavaScript file that handles form validation, error messages, and mock API call functionality.

## Features

### 1. Responsive Design
- The page layout is responsive and adapts to smaller screen sizes using media queries in the CSS.

### 2. Form Validation
- The JavaScript file validates the email and password fields before submitting the form.
- Error messages are displayed if the fields are left empty or contain invalid inputs (e.g., incorrect email format, password shorter than 6 characters).

### 3. Show/Hide Password Functionality
- A checkbox is provided to toggle the visibility of the password field.

### 4. Mock API Integration
- On successful form validation, a mock API request is made using `fetch` to a placeholder API endpoint.
- A success or failure alert is displayed based on the response.

## Files Overview

### `index.html`
This file contains the structure of the login page, including the form with email and password fields, a "show password" checkbox, and a login button. It links to the external CSS and JavaScript files.

### `index.css`
This file handles the styling for the login page, including:
- A background image with full-page coverage.
- Flexbox layout to center the form.
- Styling for form elements, such as input fields, labels, buttons, and error messages.
- Responsive adjustments for mobile screens.

### `index.js`
The JavaScript file performs the following tasks:
- Validates the email and password fields.
- Displays error messages for invalid inputs.
- Sends a mock API request with the form data upon successful validation.
- Toggles the password visibility using a checkbox.

## How to Use

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Enter an email and password in the form.
4. Click "Login" to submit the form. Ensure that the email is valid and the password is at least 6 characters long.
5. Use the checkbox to show or hide the password.

## Dependencies

- No external libraries or frameworks are required. The project uses plain HTML, CSS, and JavaScript.

## Future Enhancements

- Add real API integration for user login.
- Implement password recovery and registration functionality.
- Improve UI/UX design for better user experience.
