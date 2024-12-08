# Info Vault

This project allows users to securely manage and store various types of sensitive information, such as login credentials, credit card details, and addresses. It offers a simple account creation and login system, followed by an interface to save, view, and manage this data. The stored information is encrypted, ensuring a high level of security.

## Features

- **Account Creation and Login**: Users can create an account and log in using a username and password.
- **Manage Information**: Once logged in, users can store and manage:
  - Login information (username and password)
  - Credit card details (card number, expiry date, and CVV)
  - Address information (street, city, zip code, and country)
- **View Saved Information**: Users can view all the information they have saved in a readable format.

## How to Use

1. **Create an Account**:
   - Enter a username and password in the "Account Creation / Login" section.
   - Click the "Create Account" button to register.

2. **Log In**:
   - Enter your username and password in the login form.
   - Click the "Login" button to authenticate and access the next page.

3. **Manage Information**:
   - After logging in, you will be taken to the "Manage Your Info" page.
   - You can choose to:
     - Save login information
     - Save credit card details
     - Save address information

4. **View Saved Information**:
   - Click the "View Saved Info" button to see the details you have stored.

## Encryption and Security

All information stored in the application is encrypted before being saved to the browser's local storage. This encryption ensures that the data is highly secure and can only be accessed by the user who saved it, making it safe to store sensitive information such as login credentials, credit card details, and addresses.

However, it is important to note that while the information is encrypted for security, local storage is still not suitable for storing highly sensitive information in a real-world application, as it is accessible by the user's browser.

## Local Storage

All data (user accounts and saved information) is stored in the browser's local storage. This ensures that the data persists across page reloads. The encrypted data ensures that it remains secure, even if the browser is closed and reopened.

## Notes

- The data stored is only accessible to the logged-in user and can be viewed on the "View Saved Info" page.

## Technologies Used

- **HTML** for structure and layout.
- **CSS** for styling.
- **JavaScript** for functionality and managing user interactions.
- **LocalStorage** for data persistence.
- **Encryption** to secure stored data.

## How to Run

1. Open the following in a web browser: https://stuart-cornwall.github.io/
3. Follow the instructions in the app to create an account, log in, and manage your information.

## Contributing

Feel free to fork the repository and submit issues or pull requests with improvements.

## License

This project is open-source and available under the MIT License.
