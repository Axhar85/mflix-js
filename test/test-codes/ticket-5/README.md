Chapter 4: Resiliency

Ticket: Connection Pooling
Problem:

Task

For this ticket, you'll be required to modify the configuration of the MongoClient to set the maximum size of the connection pool to 50 connections.

The MongoClient is initialized in the src/index.js file. A link to the URI connection settings is included here for your reference.

Testing and Running the Application

Note:

The unit test only has access to DAO methods, but the connection pool size for the MFlix application is set in the index.js file.

However, the connection pool size for the testing environment is set in test/config/mongoEnvironment.js, so you can test your changes there and the unit test will tell you if something is wrong.

When the unit test passes, make sure to update the code in src/index.js so you can retrieve the validation code from the integration test.

You can run the unit tests for this ticket by running:

 COPY
npm test -t connection-pooling
Once the unit tests are passing, run the application with:

 COPY
npm start
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Connection Pooling?


<details> 
  <summary>After passing the relevant tests, what is the validation code for Connection?</summary>
   Answer: 5ad4f4f58d4b377bcf55d742
</details>