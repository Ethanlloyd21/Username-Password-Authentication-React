# Username/ Password Authentication using React
- This is a simple application of a username and password authentication using a third party application called OKLA.

## Why use OKLA?


## Install

``` javascript
npm install @okta/okta-signin-widget --save

npm install @okta/okta-react react-router-dom --save
```

## Quick Start

``` bash
# Install dependencies
npm install

# Serve on localhost:3000
npm start

# Build for production
npm run build
```

## Dependencies 

``` javascript
"dependencies": {
    "@okta/okta-react": "^1.4.1",
    "@okta/okta-signin-widget": "^2.21.0",
    "react": "^16.4.1",
    "react-dom": "^16.4.1",
    "react-router-dom": "^4.3.1",
    "react-scripts": "1.1.4"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject"
  }

```

## App Info
#### Creating an accout
- Only the admin has the access to create a new user. The admin can also set up access level on specific user. 
- For authentication, a random password is sent to the user's email. The user can opt to change the password if needed. A link is provided to do this option. 
- All browsing history on the app is monitored via OKLA webiste. 
- Admin can monitor the traffic on the specific webiste. 

## Demo
![](public/img/shoepic.PNG)

For a video demo of this app please <a href="https://drive.google.com/file/d/1eDSKRQAmc2IHXGoJa4_wgPZwCiV5diBf/view"> -----click here ------  </a>

## Technologies
- React
- JavaScript
- CSS
- HTML5
- jQueary
- OKLA (third party application)

### License

This project is licensed under the MIT License
