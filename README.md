# Election Analysis

## Overview of Election Audit
Using a Python script and data provided for the below three counties, an analysis was completed by counting the votes submitted for three candidates. The .csv file is in the /Resources folder and the completed script results are located in the /Analysis directory. 

The voting data represent the election for U.S. House Colorado District 1 held on 11/06/2018. 

**Counties:** 
 - Jefferson
 - Denver
 - Arapahoe

**Candidates:**
 - Diana DeGette (D)
 - Charles Casper Stockham (R)
 - Raymon Anthony Doane (L)

## Election Audit Results
Using the data provided the largest county which had the highest voter turnout was Denver. The winner of the specific election was the incumbent Diana DeGette with 73% (272,892) of the votes cast. 
![Election_Results_ScreenGrab](Resources/ElectionResults.jpg) 


## Election Audit Summary
The current script only looks at the county, not county / state combination for a given election dataset. In this example one of the counties (Denver) can have more than one different state. This will come into play during the end of the script where the election summary is created. 
Another update which could be implemented would be to change the output file name to include the County and winning Candidate name. This information could be then parsed or collated as a file structure to easily access the results of the election. 
