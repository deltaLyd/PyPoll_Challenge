# PyPoll_Challenge
## Election Audit Analysis

**Purpose & Overview**: This file contains Python-based computer code that analyzes a CSV file of election results in a U.S. Congressional precinct in Colorado (viewable in this folder: [Resources](https://github.com/deltaLyd/PyPoll_Challenge/tree/main/Resources)), and outputs the results of the analysis to a plain text file (.txt format) to provide data to the Colorado Board of Elections, that it may obtain the necessary information to conduct its audit of the election.  I am working directly with Tom, an employee of the Colorado Board of Elections, and his manager, Seth, to accomplish this task.  Those wishing to inspect the final code may do so here: [PyPoll_Challenge.py](https://github.com/deltaLyd/PyPoll_Challenge/blob/main/PyPoll_Challenge.py)

## Election Audit Analysis Results

The following bulleted lists provide the outcomes of the Election Audit Analysis, which may also be viewed via .txt file with this folder: [Analysis](https://github.com/deltaLyd/PyPoll_Challenge/tree/main/Analysis)

**Election Results**

• Total Votes: 369,711

**County Votes**

• Jefferson: 10.5% (38,855)

• Denver: 82.8% (306,055)

• Arapahoe: 6.7% (24,801)


**Largest County Turnout** 

Denver

**Election Results by Candidate**

• Charles Casper Stockham: 23.0% (85,213)

• Diana DeGette: 73.8% (272,892)

• Raymon Anthony Doane: 3.1% (11,606)

**Election Winner Statistics**

• Winner: Diana DeGette

• Winning Vote Count: 272,892

• Winning Percentage: 73.8%

## Recommendations to Colorado Board of Elections
### Adapting Code for Use in Auditing all State Elections

Ladies and gentlemen, while the code I have delivered for you is specifically tailored to the precint you requested an analysis of, I can (for a reasonable consulting fee), adapt the code to be applicable to all voting precints in the state of Colorado, that you may have the same confidence in the data you use to conduct you audit(s) for all precincts.  The two main changes I would make are:

1) Altering the "file_to_load" syntax in line 9 to merge multiple CSV files, even if the formatting is different (from all reporting precincts), so the program can run on the entire state's results. 

2) 

