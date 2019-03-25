# LAB: Authentication

## Before you begin
Refer to *Getting Started* in [lab-instructions.md](../../../reference/submission-instructions/labs.md) for complete setup instructions

## Getting Started
* You've been provided a server code with the authentication middleware, models and routes scaffolded in.
* There are some potential bugs and missing logic.
* Work with a partner!

## Requirements

### Assignment: Auth Server
* Create a UML diagram of the authentication system on a whiteboard
* Identify and fix any bugs
* **NEW CODE:** Protect the `/book` and `/book/:id` routes by requiring user authentication
* Document and publish the code with JSDoc

### Testing
* POST to /signup to create a new user
* POST to /signin to login as a user (use basic auth)
* Need tests for auth middleware and the routes
  * Does the middleware function (send it a basic header)
  * Do the routes assert the requirements (signup/signin)
  * Are the book routes protected properly?
* Ensure that you use supergoose instead of mongo/express


## Assignment Submission Instructions
Refer to the [lab-instructions.md](../../../reference/submission-instructions/labs.md) for the complete lab submission process and expectations
