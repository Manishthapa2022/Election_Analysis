# **Election_Analysis**

## Project Overview
A Colarado board employee requested me to perform the following tasks to complete the election audit of a recent local congressional election. 

- Calculate the Total number of votes cast
- Provide a complete list of candidates who received votes
- Calculate the total number of votes each candidate received
- The percentage of votes each candidate won
- The winner of election based on popular vote
- The voter turnout in each county
- The percentage of votes from each country out of the total count
- the county with the highest tournout
## Resources 
- Data Source: election_results.csv
Software: Python 3.9.7, Visual Studio Code 1.71.1

## Election Audit Results

![Analysis Results Snapshot](https://github.com/Manishthapa2022/Election_Analysis/blob/main/Resources/Pypoll_Challenge_VisualStudio_Output.png)
----
The analysis of the elections show that:
- There were total 369711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham recieved 23% of the vote and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the vote and 272,892  number of votes.
  - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes.
- The winner of the election was Diana DeGette who recieved 73.8 % of the vote and 272,892 number of votes. 
- The % turnout and the total voter turnout in each county were as follows:
  - Jefferson: 10.5% with a total of 38,855 votes
  - Denver: 82.8% with a total of 306,055 votes
  - Arapahoe: 6.7% with a total of 24,801 votes
- Denver had the highest turnout at 82.8% and 306,055. 


## Election Audit Summary 

The ways in which the file script can be modified to suite other Elections are as follows:

* When the Pypoll_Challenge file was created to accomodate for Election Commision's additional request, two variables were created i.e. NAME_COL and COUNTY_COL to prevent hardcoding the numbers, which can espcially help incase the Names and County are under different coloumn numbers. So, we can always avoid hardcoding and assign variables at the beginning of the code so that easy changes can be made if the script has to be used for other election polls. 
* Pseudocoding is another great way how we can identify why specific codes are added in the script. All along, both the Pypoll and Pypoll Challenge has been Pseudo coded so that in case of any future assignments, relevant changes can be made by referring to the Pseudo codes. **In our case, it helps to exactly find out where the external files have been linked to the PyPoll Challenge file and make the necessary changes in case a different file needs to be attached and also a different file type needs to be Imported.It also helps team members to quickly grasp the concepts and make the changes**.

![Image](https://github.com/Manishthapa2022/Election_Analysis/blob/main/Resources/Pseudocoding_helps.png)
    
* Apart from Pseudo coding, Comment headers can also be used where required to identify key codes and key turning points in the code. Also, the script can be split up where required so that minimum information can be loaded and least changes required to prevent coing errors. In our cse, we could use both PyPoll and Pypoll_Challenege accoridingly as per the information required in the future with minimum hard cooding and plenty of Pseudo codes. 
