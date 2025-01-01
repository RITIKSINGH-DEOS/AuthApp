# Authentication App

## Description

The **Authentication App** is a web application built to test user authentication functionalities. It is a full backend app that allows users to test login and registration flows using APIs. The app does not include a frontend UI, and testing is done manually through Postman or similar tools. It utilizes technologies such as **React**, **Node.js**, **Express**, **MongoDB**, and **Mongoose** for handling authentication and storing user data.

## Features

- **User Registration**: Register users with essential details such as name, email (Gmail supported), and password.
- **User Login**: Login using registered name/email and password.
- **Test via Postman**: Since there is no UI, API endpoints can be tested manually using Postman or similar tools.
- **Secure Password Storage**: User passwords are hashed and securely stored in the database.
- **Token-Based Authentication**: Login provides a token for authenticating future requests (JWT - JSON Web Token).

## Tech Stack

- **Frontend**: React (Not implemented yet, can be integrated with API)
- **Backend**: Node.js with Express
- **Database**: MongoDB using Mongoose for ORM
- **Authentication**: JWT (JSON Web Tokens) for securing the API
- **Environment Variables**: `.env` file for configuration
