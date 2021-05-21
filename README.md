# election_analysis

## Election Audit Overview
A Colorado Board of Elections employee had given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total nuber of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote. 

## Resources
- Data source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- County Votes:
 - Jefferson: 10.5% (38,855)
 - Denver: 82.8% (306,055)
 - Arapahoe: 6.7% (24,801)
- Largest county turnout: Denver
- The candidate results were:
    - Charles Casper Stockham: 23.0%  (85,213 total votes)
    - Diana DeGette: 73.8% (272,892 total votes)
    - Raymon Anthony Doane: 3.1% (11,606 total votes)
- The winner of the election was:
    - Candidate Dianna DeGette who received 73.8% of the vote and 272,892 total votes
## Election Audit Summary
An election audit program was built to automate reporting of this specific election.  With minor changes to the code, this script could be used to generate a report for any election.  Two changes could be made:
    - Change county to accept any desired value - to accomodate any subdivision in the data (e.g. country, state, etc).
    - Change candidate to accept any desired value - to accomodate any person, place, thing running in this election. 