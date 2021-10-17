# Election_Analysis

# Overview of Election Audit: Explain the purpose of this election audit analysis.

The purpose of this analysis is to assist a Board of Elections employee, Tom. He wants to perform an audit of the US Congressional Pricint election in Colorado. The analysis will display the total votes cast, total votes for each candidate, percentage of votes for each candidate, The voter turnout for each county, The percentage of votes from each county out of the total count, The county with the highest turnout, and the winner based on popular vote. We are using Python programing language with VS Code software to calculate the results. 


# Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

## How many votes were cast in this congressional election?
Total Votes: 369,711

## Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

## Which county had the largest number of votes?
County with the largest number of votes: Denver
Total Voter Turnout: 306055


## Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)


## Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

# Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

The code will work well and precise with other elections where there is either more or less counties. Even with any other nuumber of candidates the loops funcitons can keep iterating until all names are displayed. However for elections that have upwards of perhaps 50 counties, the results will have a long list of counties to display. An if statement can be made to display only the top 3 counties with the largest voter count. 

When dealing with tight margins another modification can be made to display the percentage to another decimal point. This can come in useful for elections with tight margins. To do this we would modify line 130 in our code to write:

f"{candidate_name}: {vote_percentage:.2f}% ({votes:,})\n")

Where the floating point goes to two decimal places instead of one. 


