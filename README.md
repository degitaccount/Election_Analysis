# Overview:
The purpose of this analysis is to audit, tabulate and summarize the congressional election results for the Colorado Board of Elections.

## Election Results
* Total Votes Cast: 369,711

*Percentage and Total Votes by County*
* Jefferson: 10.5% (38,855)
* Denver: 82.8% (306,055)
* Arapahoe: 6.7% (24,801)
* Largest County Turnout: Denver

*Percentage and Total Votes by Candidate*

* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)

*Winning Candidate information*

* Winner: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8%

## Summary
The code used to produce the results that were presented can be modified for other elections.  

For example, if we receive an election file in the same format for a group of cities instead of counties, I could make the following modifications:

>>>> f"***County*** Votes: \n" would be changed to:

>>>> f"***City*** Votes: \n"
	
>>>> ...and...

>>>> f"Largest ***County*** Turnout: {winning_county}\n" would be changed to:
	
>>>> f"Largest ***City*** Turnout: {winning_county}\n

*Note: {winningcounty} does not to be updated for the code to work for city level data.  However, the code can be misleading so updating all the variables, lists, dictionaries and calculations to replace “county” references with “city” would be better coding hygiene.*

The code can also be repurposed for statewide elections with the same changes described above, except that “county” would be replaced by “state”.  Of course, this continues to assume the results are received in the same format as the county data.




