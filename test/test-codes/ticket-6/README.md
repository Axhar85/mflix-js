Chapter 4: Resiliency

Ticket: Timeouts
Problem:

Task

For this ticket, you'll be required to modify the configuration of MongoClient to set a write timeout of 2500 milliseconds.

The MongoClient is initialized in the src/index.js file. A link to the URI connection settings is included here for your reference.

Testing and Running the Application

Note:

The unit test only has access to DAO methods, but the write timeout for the MFlix application is set in the index.js file.

However, the write timeout for the testing environment is set in test/config/mongoEnvironment.js, so you can test your changes there and the unit test will tell you if something is wrong.

When the unit test passes, make sure to update the code in src/index.js so you can retrieve the validation code from the integration test.

You can run the unit tests for this ticket by running:

 COPY
npm test -t timeouts
Once the unit tests are passing, run the application with:

 COPY
npm start
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Timeouts?

<details> 
  <summary>After passing the relevant tests, what is the validation code for Connection?</summary>
   Answer: 5addf035498efdeb55e90b01
</details>
