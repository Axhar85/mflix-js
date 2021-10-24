Final Exam

Final: Question 6
Problem:

Suppose a client application is sending writes to a replica set with three nodes, but the primary node stops responding:
<img src= "src\public\q6.png" alt =" image6">

C:\Users\azhar\Documents\mongodb\mflix-js\

https://s3.amazonaws.com/edu-static.mongodb.com/lessons/M220/notebook_assets/replica_set_primary_down.png
Assume that none of the connection settings have been changed, and that the client is only sending insert statements with write concern w: 1 to the server.

After 30 seconds, the client still cannot connect to a new primary. Which of the following errors will be thrown by the Node.js driver, and how should it be handled?

<details> 
  <summary>Correct Answer</summary>
   Answer : a Timeout error, resolved by wrapping the call in a try/catch block
</details>
