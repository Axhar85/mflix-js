Final Exam

Final: Question 1
Problem:

Assume we have a collection called elections that holds data about all United States Presidential Elections since 1789. All the documents in the elections collection look like this:

 COPY
{
  year: 1828,
  winner: "Andrew Jackson",
  winner_running_mate: "John C. Calhoun",
  winner_party: "Democratic",
  winner_electoral_votes: 178,
  total_electoral_votes: 261
}
total_electoral_votes represents the total number of electoral votes that year, and winner_electoral_votes represents the number of electoral votes received by the winning candidates.

Which of the following queries will retrieve all the Republican winners with at least 160 electoral votes?


<details> 
  <summary>After passing the relevant tests, what is the validation code for Connection?</summary>
   Answer: elections.find( { winner_party: "Republican",
                     winner_electoral_votes: { "$gte": 160 } } )
</details>
