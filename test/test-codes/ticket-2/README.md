Chapter 2: User-Facing Backend

Ticket: Delete Comments
Problem:

User Story

"As a user, I want to be able to delete my own comments."

Task

For this ticket, you'll be required to modify one method in commentsDAO.js, deleteComment. Ensure the delete operation is limited so only the user can delete their own comments, but not anyone else's comments.

MFlix Functionality

Once this ticket is completed, users will be able to delete their own comments, but they won't be able to delete anyone else's comments.

Testing and Running the Application

You can run all the tests for this ticket by running:

 COPY
"npm test -t delete-comments"
Once the unit tests are passing, run the application with:

 COPY
npm start
Now proceed to the status page to run the full suite of integration tests and get your validation code.

After passing the relevant tests, what is the validation code for Delete Comments?

<details> 
  <summary>After passing the relevant tests, what is the validation code for Connection?</summary>
   Answer: 5ac25c280a80ed6e67e1cecb
</details>