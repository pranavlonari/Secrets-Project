# Secrets App

Welcome to Secrets App, where users can register and anonymously share their secrets!

## Overview

This web application prioritizes security and privacy while allowing users to post and explore secrets. Here's a brief breakdown of the security measures implemented:

### Security Levels:

1. **User Authentication:**

   - Implemented secure user registration with robust practices using usernames and passwords.

2. **Data Encryption:**

   - Leveraged `mongoose-encryption` for advanced data encryption, ensuring heightened protection for shared secrets.

3. **Password Security:**

   - Employed the MD5 hashing algorithm to enhance password security, following industry best practices.

4. **Bcrypt and Salted Encryption:**

   - Elevated security standards with Bcrypt for password hashing and integrated salted encryption for added protection around shared secrets.

5. **Professional Authentication with Passport.js and Sessions:**

   - Integrated Passport.js for professional-grade authentication, complemented by secure sessions and cookies.

6. **OAuth 2.0 and Google Sign-In:**
   - Orchestrated the strategic deployment of OAuth 2.0 for secure user login, including the careful handling of authorization codes and efficient token exchange.

## Getting Started

To run the Secrets App locally, follow these steps:

1. Clone the repository: `git clone https://github.com/pranavlonari/Secrets-Project.git`
2. Install dependencies: `npm install`
3. Set up environment variables (see `.env.example` for guidance).
4. Run the application: `nodemon app.js`

## Dependencies

- `mongoose`
- `express`
- `passport`
- `mongoose-encryption`
- `bcrypt`
- `passport-google-oauth20`
- `bodyparser`
- `ejs`
- `dotenv`

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Your input is valuable in enhancing the app's security and functionality.

Happy coding!
