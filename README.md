# python_challengee

## Background

We were asked to create this repository, python-challenge and complete two Python Challenges, PyBank and PyPoll. 

### Preliminaries

* First, we created this repository on GitHub and then cloned it to my computer.

* Inside my local git repository,we created a directory for both Python programs. 

* Inside both `PyBank` and `PyPoll` folders, we were tasked to add:

  * A new file called `main.py`. This would be the main script we would be running for each analysis.
  * A `Resources` folder that would hold the respective CSV files we would use in each program. 
  * An `analysis` folder that would hold a text file that has the results from our analysis.

* We then pushed the above changes to GitHub or GitLab.

## PyBank

* This portion of the project required us to create a Python script for analyzing the financial records of a company. We were given a set of their financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). Within the dataset there were two columns: `Date` and `Profit/Losses`. 

* Our task was to create a Python script that analyzed the records to calculate each of the following:

  * The total number of months included in the dataset.

  * The net total amount of "Profit/Losses" over the entire period.

  * The average of the changes in "Profit/Losses" over the entire period.

  * The greatest increase in profits (date and amount) over the entire period.

  * The greatest decrease in losses (date and amount) over the entire period.

* Over the 86 month period, it was interesting to note that their average changes in profit skewed negative, with their biggest loss in September of 2013.

* Our final script both prints the analysis to the terminal and exports a text file to the `analysis` folder with the results.

## PyPoll


* In this part of the project, We were tasked with helping a small, rural town modernize its vote counting process. We were given a poll dataset called [election_data.csv](PyPoll/Resources/election_data.csv). This dataset had three columns: `Voter ID`, `County`, and `Candidate`. 

* Our task was to create a Python script that analyzed all of the votes and calculated each of the following:

  * The total number of votes cast.

  * A complete list of candidates who received votes.

  * The percentage of votes each candidate won.

  * The total number of votes each candidate won.

  * The winner of the election based on popular vote.

* Through this script, we were able to discover that this town's vote was decisively in favor of Khan.

* Our final script both prints the analysis to the terminal and exports a text file to the `analysis` folder with the results.
* This marks the end of group 1's analysis.