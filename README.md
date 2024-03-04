# Implementing OAuth2 Login in Angular 17 with Google Cloud

This project demonstrates how to implement OAuth2 login in an Angular 17 application using Google Cloud Client IDs.

## Features:

- Secure and convenient user login using existing Google credentials.
- Step-by-step guide with clear instructions.
- Code snippets and screenshots for each step.

## Prerequisites:

- Node.js and npm
- Angular CLI
- A Google Cloud Console account

## Getting Started:

1. Clone this repository.
2. Install the required dependencies:

```
npm install
```

3. Configure the authConfig object in app.config.ts with your specific Google Cloud information:

- issuer: URL of the identity provider (https://accounts.google.com)
- clientId: Client ID from your Google Cloud console
- redirectUri: Redirect URI for your application
- scope: Scopes of access requested by your application

4. Run the application:

```
ng serve
```

5. Visit http://localhost:4200 in your browser.
6. Click the "Sign in with Google" button to initiate the login process.

## Usage:

The application allows users to sign in with their Google accounts.
Upon successful login, users are redirected to the dashboard component.
Users can also log out of the application.

## Testing:

Test the login functionality by clicking the "Sign in with Google" button and following the prompts.
Test the logout functionality by clicking the "Logout" button.

## Additional Notes:

This is a basic example of OAuth2 login with Angular 17 and Google Cloud.
You may need to modify the code to fit your specific needs.
For more information on OAuth2, please refer to the official documentation.
