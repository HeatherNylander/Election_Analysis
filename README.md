# Election Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.
1. How many votes were cast in this congressional election.
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
7. Which county had the largest number of votes?

## Resources
- Data Source: election results.csv
- Software: Python 3.6.1, Visual Studio Code, 1,38.1 

## Election Audit Results
### Candidate Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane

- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
   
- The winner of the election was:  
    - ```diff 
      + Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
       ```
### County Results
- There were 369,711 votes cast in the election.

- The counties were:
    - Jefferson
    - Denver
    - Arapahoe

- The candidate results were:
    - Jefferson county cast 10.5% of the vote and 38,855 number of votes.
    - Denver county cast 82.8% of the vote and 306,055 number of votes.
    - Arapahoe county cast 6.7% of the vote and 24,801 number of votes.
    
- The county with the largest turnout was:  
    - ```diff 
      + Denver county, which cast 82.8% of the vote and 306,055 number of votes.
       ```

## Election Audit Summary
Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

- This script can be used for any election with the following additions:
    - A summary of how many residents as well as how many registered individuals should be provided to accurately calculate turnout percentages for each individual county. 
    - The script could be modified to add a section to calculate the percentage of votes from each county that went to each candidate. This way there would be a summary detailing the most popular candidate by county.     
