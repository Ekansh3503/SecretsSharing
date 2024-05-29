# Secrets-Sharing

```markdown
## Description

This is a web application that allows users to share secrets anonymously. Users can register an account, log in using their credentials or Google account, submit secrets, and view secrets submitted by other users.

## Features

- User registration and authentication
- Local authentication using username and password
- Google OAuth authentication
- Submit and view secrets
- Session management
- MongoDB integration for data storage

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Passport.js
- Passport-local for local authentication
- Passport-google-oauth20 for Google OAuth authentication
- EJS for server-side rendering
- Express-session for session management
- Body-parser for parsing request bodies
- dotenv for environment variables configuration

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Ekansh3503/SecretsSharing.git
```

2. Navigate into the project directory:

```bash
cd secrets-app
```

3. Install dependencies:

```bash
npm install
```

4. Create a `.env` file in the project root directory and add the following environment variables:

```
CLIENT_ID=your-google-client-id
CLIENT_SECRET=your-google-client-secret
```

Replace `your-google-client-id` and `your-google-client-secret` with your actual Google OAuth client ID and client secret.

5. Start the application:

```bash
npm start
```

## Usage

1. Open your web browser and navigate to `http://localhost:3000`.
2. You can register a new account or log in using your credentials.
3. Alternatively, you can click on the "Sign in with Google" button to log in with your Google account.
4. Once logged in, you can submit your secrets or view secrets submitted by other users.
5. To log out, click on the "Logout" button.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
