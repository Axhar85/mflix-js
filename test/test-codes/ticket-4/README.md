Chapter 3: Admin Backend

Ticket: Migration
Problem:

Task

For this ticket, you'll be required to complete the command-line script located in the migrations directory of src called movie-last-updated-migration.js.

Things always change, and a requirement has come down that the lastupdated value in each document of the movies collection needs to be stored as an ISODate rather than a String.

Complete the script so it updates the format of lastupdated using a bulk write. You can find the exact Node.js syntax in the docs.

To perform the migration, run the script:

 COPY
node movie-last-updated-migration.js
Testing and Running the Application

You can run the unit tests for this ticket by running:

 COPY
npm test -t migration
Once the unit tests are passing, run the application with:

 COPY
npm start
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Migration?

<details> 
  <summary>After passing the relevant tests, what is the validation code for Connection?</summary>
   Answer: 5ad9f6a64fec134d116fb06f
</details>