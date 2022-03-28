# Election_Analysis
## Overview of Election Audit:
We perform an election audit on the election results for a Colorado Board of Elections employee who has given us the data from a recent local congressional election. We aim to figure out the number of total voters, voters per county, how many votes each candidate received and the winner of the election. We use a csv file, git and python to accomplish this task.
## Election Audit Results:
1. Total number of votes cast:  
* 369,711
3. Breakdown of the number of votes and the percentage of total votes for each county in the precinct.
County Votes:
* Jefferson: 10.5% (38,855)
* Denver: 82.8% (306,055)
* Arapahoe: 6.7% (24,801)
3. Country with the most votes:
* Denver
5. Breakdown of the number of votes and the percentage of the total votes each candidate received:
* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)
6. Determine the winner of the election based on populr vote.
* Winner: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8%

## Election-Audit Summary:
The script can be easily modified and repurposed for another election by changing lines 9 and 11.
 file_to_load = os.path.join( "Resources", "election_results.csv")
 file_to_save = os.path.join("analysis", "election_results.txt")
We used an indirect read for the file path to look for the election results folder, the code would habve to be adjusted based on the folders where the related csv file for the new election is stored. The code in line 9 that says "election results.csv" should also be changed to the filename of your source data. The source data would have to copy the layout of the election results.csv so that it could be treated similarly in python. Furthermore, you can optionally change the election_results.txt name and relevant variable names but that is not necessary as the program witll still be executed.
