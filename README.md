# Secure registration, login, and logout application using node.js and passport.js (authentication middleware for Node.js)

## Purpose of the application

~~~~
The application allows a user to securely register and log in to a website through the use of 
secure user authentication.  Once logged in, the user is able to log out of the website where 
the user will not be able to return to the logged in page until first logging in again.
~~~~

----------------------------

## User Stories

~~~~
As a user of the website
So that I can log in
I want to securely register
~~~~

~~~~
As a user of the website
So that I can connect to the logged in page
I want to securely log in
~~~~

~~~~
As a user of the website
So that I can leave the logged in page
I want to log out
~~~~

-------------------------------

## Technical Specifications / Set up instructions

1. Clone this repo to your local machine.  Within this cloned project directory install the below.

2. Install Node.js

* Install Node Version Manager (NVM)
  ```
  brew install nvm
  ```
  Then follow the instructions to update your `~/.bash_profile`.
* Open a new terminal
* Install the latest long term support (LTS) version of [Node.js](https://nodejs.org/en/), currently `16.14.0` (version 17 will be available with a maintenance LTS Start date of 2022-04-01).
  ```
  nvm install 16
  ```

3. Install Node.js dependencies
   ```
   * npm init -y
   * npm install
   ```
4. Install an ESLint plugin for your editor. For example: [linter-eslint](https://github.com/AtomLinter/linter-eslint) for Atom.

5. For testing through test driven development install Jest
   ```
   * npm install -g jest
   * npm install jest
   ```

6. For the purpose of commiting this project, add the `node_modules` and `.env` files to your `.gitignore` file.

### Database

All user data will be stored in memory and so no database system is to be used.

### Test

- To run all tests on the entire directory, run the following from the top parent directory
  ```
  jest
  ```
- To run tests on a specifi file, run the following
  ```
  `jest<file name>`
  ```

  ```bash
  npm run lint              # linter only
  ```
---