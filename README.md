# GitHub Log In

A simple Node.js app that gets the 3-legged oAuth token from GitHub.

## Set Up

1. `git clone git@github.com:shiya/github-login.git`
2. rename `example.env` to `.env`
3. Go to Github->Settings->'Developer settings'->[OAuth Apps](https://github.com/settings/developers) and create an OAuth app. Create a client secret and save it along with the client ID in your .env file.
4. `npm install`
5. `npm start`
6. Go to <http://localhost:3000>

If you want to test sign-in again, you will need to sign out. Github->Settings->Applications->['Authorized OAuth Apps'](https://github.com/settings/applications), find your app and revoke permissions.
