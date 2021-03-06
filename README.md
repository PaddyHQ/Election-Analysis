# Election-Analysis

## Overview

The purpose of this analysis is to help audit congressional election results by providing data on the

* voter turnout for each county
* percentage of votes from each county out of the total count
* county with the highest turnout

## Results

![](./Resources/total_votes.PNG)

* above is the total number of votes cast in this election

![](./Resources/county.PNG)

* Denver county had a whopping 83% of the vote during this election (about 300k votes). This is by far the most of all the counties. Jefferson, the next most, only had 10%.

![](./Resources/winner.PNG)

* Diana DeGette won the election with 73.8% of the vote (about 273k votes), completely outshining the others. The next most votes went to Charles Casper Stockham with 23%.

## Audit Summary

Using this simple, straightforward code, we were able to tally up county results and confirm Diana DeGette won the election. Given that a code like this is simple enough and could be open sourced, it would be good for transparency reasons to use something like this to tally results following an election. A program like this could be run on multiple computers to check for errors/issues.