# Election-Analysis

## Project Overview

A Colorado Board of Elections employee gave me the following tasks to do for the election Audit of a recent local congression election.

My job was to...
  1. Calculate the total number of votes.
  2. Get a complete list of candidates who recieved votes.
  3. Calculate the total number of votes each candidate recieved.
  4. Calculate the percentage of votes each candidate won.
  5. Determine the winner based on popular vote.

## Challenge Overview
### Purpose
To provide additional information, requested by the election commission, to complete the audit:

  1. The voter turnout for each county
  2. The percentage of votes from each county out of the total count
  3. The county with the highest turnout

## Resources

Data Source: election_results.csv
Software: Python 3.8.8

## Summary
### Election-Audit Results

The analysis of the election show that:

* There were 369,711 votes cast in the election.

* The counties were
  * Jefferson
  * Denver
  * Arapahoe
  
* The county results were
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801) 
  
* The candidates were
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane
  
* The candidate results were
  * Stockham: 23.0% (85,213)
  * DeGette: 73.8% (272,892)
  * Doane: 3.1% (11,606)
  
* The county with the largest number of votes was:
  * Denver, which recieved 82.8% of the votes and 306,055 number of votes.
  
* The winner of the election was:
  *  Diana DeGette, who recieved 73.8% of the vote and 272,892 number of votes.

### Election-Audit Summary:

This script can be used with certain modifications for any election going forward. These modifications include...
  1. Before defining the variable "file_to_load", at the beginning of the script, have the code ask the user to input the folder name that contains the CSV file, and, also, the CSV file its-self that has the data. This way, no matter what election data, as long as it is in the same format as the "election_results.csv, it will run successfully.
  2. Promptly after, have the computer ask the user for a foler name they would like to save their text file to, as well as the text file that will have the election information on it.
