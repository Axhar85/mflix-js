Final Exam

Final: Question 3
Problem:

Suppose an instance of MongoClient is created with the following settings:

 COPY
import { MongoClient } from "mongodb"

const URI = "mongodb+srv://m220-user:m220-pass@m220-test.mongodb.net/test"

const testClient = await MongoClient.connect(
  URI,
  {
    authSource: "admin",
    connectTimeoutMS: 50,
    retryWrites: true,
    useNewUrlParser: true
  },
)
Please find the documentation on Connection String URI Format here. The variable representing our client, testClient, will:



<details> 
  <summary>Correct Answer</summary>
   Answer 1: wait at most 50 milliseconds for timing out a connection.

   Answer 2: automatically retry writes that fail.
</details>
