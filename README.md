# Election_Analysis
# Project Overview
Complete the Election audit of the local Congressional Election held in Colorado for the Board of Colorado Elections.
The audit is based on the following tasks assigned by the Board members. 
- Calculate the toal number of votes cast
- Get a complete list of candidates who recived votes 
- Calculate the total number of votes each candidate recived
- Calculate the percentage of votes each candidate won
- Dettermine the winner of the election based on popular vote
- The voter turnout for each county
- The percentage of votes from each county
- The county with the highest turnout

# Resources 
Data source : election_results.csv
Software : Python 3.7.6 , Visual Studio Code 1.62.2

Final Audit results Script - https://github.com/Rangisal/Election_Analysis/blob/main/PyPoll_Challenge.py

# Election Audit Results by Candidates

- There were 369,711 votes casted in the election

- The candidates were
  - Charles Casper Stockhalm
  - Diana DeGette
  - Raymon Anthony Doane
  
- The candidate results
  - Charles Casper received 23.00% of the vote with a total of 85,213 votes.
  - Diana DeGette received 73.8% of the vote with a total of 272,892 votes.
  - Raymon Anthony received 3.1% of the vote with a total of 11,606 votes.
  
- The winner of the election was Diana with 272,892 total votes with 73.8% as a percentage.

# Election Audit Results by County

- The Counties were
  - Jefferson
  - Denver 
  - Arapahoe

- The vote turnout for each County
  - Jefferson received 10.5% of the vote with total of 38,855
  - Denver received 82.8% of the vote with total of 306,055
  - Arapahoe received 6.7% of the vote with total of 24,801 

- The County with largest vote turnout was Denver with total of 306,055 and 82.8% as a percentage.





 ![image](https://user-images.githubusercontent.com/93173498/142779999-d1ce63f2-2484-4a9c-82f2-e5df300cf280.png)


# Election Audit Summary 

- This script can be used for any congressionall election with only ballot Id, Candidate and County. And the winning candidate and winning county can be determines with the     total votes and their percentage. 
- The same can be used for the federal election by using state information instead of the county information.
- The final results of the above comparison will be very helpful to determine the vote turnover of each demography. 
- By a proper midification , using if statement the percentage , vote turnover for each candidate from each county can be determined. 

