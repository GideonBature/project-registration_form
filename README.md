# Registration Page

The Registration Page is a simple webpage that allows users to sign up by providing their first name, last name, email address, and password. It also includes form validation to ensure that the required fields are filled in correctly.

## Usage

To use the registration page, simply open the `index.html` file in a web browser. The registration form will be displayed, and users can enter their information to sign up.

### Registration Form

The registration form consists of the following fields:

- **First Name**: Text input field for entering the user's first name.
- **Last Name**: Text input field for entering the user's last name.
- **Email Address**: Text input field for entering the user's email address.
- **Password**: Text input field for entering the user's password.
- **Claim Your Free Trial Button**: Button for submitting the registration form and creating a new account.

## JavaScript Validation

The registration form includes JavaScript validation to ensure that the required fields are filled in correctly before submitting the form. The `validateForm()` function is called when the form is submitted, and it performs the following validations:

- Checks if the first name field is empty. If it is, an error message is displayed below the field.
- Checks if the last name field is empty. If it is, an error message is displayed below the field.
- Checks if the email field is empty or if the input is not in a valid email format. If either condition is true, an error message is displayed below the field.
- Checks if the password field is empty. If it is, an error message is displayed below the field.

If all the fields are filled in correctly, the form is submitted. Otherwise, the form submission is prevented, and the error messages are displayed to the user.

## CSS Styling

The registration page is styled using CSS. The main styles are defined in the `style.css` file. Here are some key styling properties:

- The container has a background color, and the content is centered within it.
- The text elements are styled with appropriate font families, sizes, and colors.
- The form inputs and buttons have customized styles, including border colors, padding, and background colors.
- Error messages are displayed below the corresponding input fields.

## Files

The registration page consists of the following files:

- `index.html`: The main HTML file that displays the registration form.
- `style.css`: The CSS file that defines the styles for the registration form.
- `script.js`: The JavaScript file that contains the form validation logic.

Feel free to modify and customize the Registration Page as needed!


