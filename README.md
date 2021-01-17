# Election Analysis

## Overview of Election Audit 

Colorado Board of elections employee, Tom, required assisance in completing an election audit of the tabulated results for US congressional presinct in Colorado. From this audit, we were tasked to report the following:

 - The total number of votes cast.
 - The voter turnout for each county.
 - The percentage of votes from each county out of the total count.
 - The county with the highest turnout.
 - The total votes for each candidate.
 - The percentage votes for each candidate.
 - The winner of the election based on the populat vote.
 
 ## Election-Audit Results
 
 ### Resources
 
 To complete this audit, the Data Source used was _**election_results.csv**_ (located in the Resources/ folder of this respository). The sofware used to complete the analysis was _**Python 3.9, Visual Studio Code, 1.52.1**_. The Candidate and County Resultes have been saved in the _**election_results.txt**_ file localed in the analysis/ folder of this repository.
 
 ### Summary
  
   _Output from election_analysis.txt :_
     
     Election Results
     -------------------------
     Total Votes: 369,711
     -------------------------

     County Votes:
     Jefferson: 10.5% (38,855)

     Denver: 82.8% (306,055)

     Arapahoe: 6.7% (24,801)

     -------------------------
     Largest County Turnout: Denver
     -------------------------
     Charles Casper Stockham: 23.0% (85,213)
     Diana DeGette: 73.8% (272,892)
     Raymon Anthony Doane: 3.1% (11,606)
     -------------------------
     Winner: Diana DeGette
     Winning Vote Count: 272,892
     Winning Percentage: 73.8%
     -------------------------
  
The analysis of the election data (above) shows:
  - There were 369,711 votes cast in this election. 
  - Each county saw the following voter turnout:
     - **Jefferson:** 38,855 voters
     - **Denver:** 306,055 voters
     - **Arapahoe:** 24,801 voters
  - The percentage of votes from each county out of the total count were as follows:
    - **Jefferson:** 10.5% of the total count
    - **Denver:** 82.8% of the total count
    - **Arapahoe:** 6.7% of the total count
  - The county with the hight turnout was **Denver**.
  - Each candidate received the following number of votes:
    - **Charles Casper Stockham:** 85,213 votes
    - **Diana DeGette:** 272,892 votes
    - **Raymon Anthony Doane:** 11,606 votes
  - The percentage votes for each candidate were as follows:
    - **Charles Casper Stockham:** 23.0%
    - **Diana DeGette:** 73.8%
    - **Raymon Anthony Doane:** 3.1%
  - The winner of the election based on the popular vote was **Diana DeGette**, with a total of **272,892** votes, which comprised **73.8%** of the total votes.

## Election Audit Summary

After successfully using this script to audit the tabulated results for US congressional presinct in Colorado, with some modifications, it can be used for any election. Such modifications could include adding additional lists and dictionaries to capture voter data outside of counties with subsequent additions of for loops to analyze the data within them. Another modification could be to modify the existing lists and dictionaries to represent and hold the geographical data of a different country/polical system that also determines the election winner based on the popular vote.

  **Example #1**: Audit Election Data to destermine the results of US Presidential Primary Election 
  
  This script can be modified so that it can audit the election data of a US Presidential Primary Election. This can be acccomplished by adding lists and dictionaries to hold the voter data from the States and Towns included in this election. After this, for loops can be added to the script to analyze and output the voter turnout and percentage votes from each state and town. 
  
  **Example #2**  Audit Election data to determine the results of a Canadian Federal Election
  
  This script can be modified so that it can audit the election results of a Canadian Federal Election, where the data used to determine the election results is different than that of the US congressional presinct in Colorado. This can be acheived my making the following additions to the script:
   - Groups each Member of Parliament (MP) with their Political Party.
   - Determines the winning MP/Political Party for each constiuency in the House of Commons.
   - Caculate's the total consituencies won for each Political Party and calculates this as a percentage of the total consituencies. 
   - Determine's the winner of the Federal Election based on which Political Party won the majority of consituencies in the House of Commons. 

 
