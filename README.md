# School_District_Analysis

## Overview of the project
The election commission has requested some additional data to complete the audit:

* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

## Election Audit Results

1. How many votes were cast in this congressional election?

369,711
  
2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

County Votes:

Jefferson: 10.5% 38,855

Denver: 82.8% 306,055

Arapahoe: 6.7% 24,801

3. Which county had the largest number of votes?

Denver

4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

## Election Audit Recomendations

We can use the same code to analyze other elections. To achieve this goal we have to consider change some things in our current code

1. The first thing we need to consider is changing the name of files we need to open and the paths

```# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
```

2. The second thing to consider is having the data organized in the same way that it is organized now. For instance:


![Data](imagen_datos.png)
