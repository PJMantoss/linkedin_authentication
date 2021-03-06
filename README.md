# LinkedIn Authentication Plugin with NodeJS and Passport

This "LinkedIn Login" functionality can be added to any web app. The project started with a Client Registration (OAuth Client) on LinkedIn Developer site, then a UI where a user can log in was built (Authorization endpoint), then the code for the API call was written (token endpoint/back channel call to get an access token) and then finally, resource sharing to the call.

## Tech Overview

- LinkedIn API
- LinkedIn OAuth Access Token
- Node/Express
- EJS (Embedded JavaScript Templating)
- Passport (Authentication middleware for Node.js)
- EJS (Embedded JavaScript Templating)
- MaterializeCSS
- Font Awesome

## Dependencies

- express
- express-session
- passport
- passport-linkedin-oauth2
- ejs

## How To Run The Plugin on Your Machine

1. Clone the repo (git clone https://github.com/PJMantoss/linkedin_authentication.git)
2. Change Directory (cd linkedin_authentication)
3. Run **npm install** (to install dependencies)
4. Run **npm start**
5. Open this link http://127.0.0.1:3000/