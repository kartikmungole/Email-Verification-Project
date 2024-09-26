## Email Verification Project
This is a Django-based project that allows users to register and receive a verification email. The user is required to click the verification link sent via email to activate their account. This functionality is commonly used in web applications to ensure that users provide valid email addresses during the registration process.

## Features
User Registration
Email Verification with unique tokens
Resend verification email option
Login only after email verification
Simple and secure implementation using Django and its built-in functionalities

## Tech Stack
**Backend**: Python, Django
**Database**: SQLite (default for Django, but you can change it)
**Email Service**: SMTP (for sending verification emails)
**Frontend**: HTML, CSS (optional for UI enhancement)

## Email Verification Workflow
A user registers on the site.
A unique token is generated for the user.
An email containing the verification link with the token is sent to the user's email.
The user clicks the verification link.
If the token is valid, the user's account is activated.

## Usage
Navigate to the registration page and sign up with your email address.
A verification email will be sent to the provided email.
Open the email and click the verification link.
