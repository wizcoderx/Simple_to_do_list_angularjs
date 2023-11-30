# AngularJS Password Generator

This is a simple AngularJS application that generates passwords based on user-selected options.

## Logic Used in the Code

The code utilizes AngularJS to create a dynamic password generator with the following logic:

- Checkboxes are provided for the user to choose which types of characters to include in the password.
- Four types of characters are available: Numbers, Uppercase Letters, Lowercase Letters, and Symbols.
- The password is generated in real-time based on the user's checkbox selections.
- A custom validation function ensures that at least one checkbox is selected before generating a password.

## Custom Validation

Custom validation is implemented in the following way:

- A custom validation function, `hasSelectedOptions`, checks whether at least one checkbox is selected.
- The error message "Please select at least one option." is displayed if the validation fails.
- The password generation logic (`generatePassword` function) is only executed if the custom validation passes.

## Getting Started

To use this password generator, simply open the HTML file in a web browser. Select the desired character types, and the generated password will update in real-time.

Feel free to customize the character sets and password length according to your preferences.

## Contribution

Developers are welcome to make any changes in the code. When making pull requests, ensure that the changes are saved on a different branch. Developers need to create a separate branch for their changes.
