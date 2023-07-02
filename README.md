# Learning End to End Testing with Jest

_This repository focuses on creating a basic recipe app using Node.js for the backend. Its purpose is to provide a comprehensive exploration of Unit, Integration, and end-to-end testing._

## Installing

1. To use these exercise files, you must have the following installed:
   - Git
   - Node.js
   - MongoDB
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. Navigate to the location of the folder
4. Run `npm install` to install dependencies
5. Rename `.env.example` to `.env` and update the variables accordingly
6. Run `npm run start` to get the app started on your development environment

### Seed Data to Database

To seed data to database run the command `npm run seed`, and to rollback run `npm run seed:rollback`. After seeding, you can login with the following details: `username: admin, password: okay`

### Running the tests

To run the tests, run the commannd `npm run test`
_The tests, test the api endpoints to ensure that they work as expected and return the required response. The output of the test also shows the code coverage_
