# Election Analysis Challenge
***University of Toronto - Data Analytics Boot Camp - Module 3 - PyPoll with Python***

---

## Project Overview
A raw election data is provided by Colorado Board of Election. The following tasks and calculations has been requested.
  1. Total number of votes
  2. Votes and percentages based on counties
  3. County with the largest number of votes
  4. Votes and percentages based on candidates
  5. Winner candidate
  
---

## Resources
Data Source: election_reslutls.csv
Software: Python 3.7.6, Visual Studio 1.71.0

---

## Results Summary

* Total number of votes: ***369711***

* Counties' names, number of votes, and percentages
  * Jefferson: ***10.5%*** (38,855)
  * Denver: ***82.8%*** (306,055)
  * Arapahoe: ***6.7%*** (24,801
  
* Counties with the largest number of votes:
  * Name: ***Denver***
  * Votes: ***306,055***
  * Percentage: ***82.8%***

* Candidates' name, number of votes, and percentage:
  * Charles Casper: Stockham: ***23.0%*** (85213)
  * Diana DeGette: ***73.8%*** (272892)
  * Raymon Anthony: Doane: ***3.1%*** (11606)

* Election Winner:
  * Name: ***Diana DeGette***
  * Votes: ***272982***
  * Percentage: ***73.8%***
  
---

  ## Outputs
  
  * .txt file including detailed results of the analysis
  * Terminal, showing the detailed results of the analysis

  ***There are pictures of Input and Outputs at the end of this report.***
  
---

## Election-Audit Summary

The script can be used for any elections. However, following regulations should be taken into consideration in order to make the script work.
  * The input data should be a .csv file, named "election_results.csv"
  * The input data should be saved inside a directory named "Resources". The .py file should be in the upper directory.
  * The input file should be in a tabular context, with a header row and three columns.
  * These three columns should be in the following order, containig specific information:
    * Voters ID (Template is not important)
    * County
    * Candidate
    
### **Can the script be used for different kind of elections?**
Yes, it can be used for any election in case the aforementioned regulations are followed.
However, it should be modified accordingly. There are two of examples here:

  * Different scale
    In case of using for different scale election (e.g. Provinces, Cities, Cummunities) the word "county" should be replaced all over the script with a proper one.
  
  * Different Input and/or Output file address
    In this case, input and/or output address should be replaced between " " in lines 8 and/or 10.
  
---

## Input File

![](/Resources/Input_file.png)


---

## Output Terminal

![](/Resources/Terminal.png)

---

## Output File

![](/Resources/Output_file.png)
