# mFRR
Data and files related to mFRR data analysis
The code in the analysis is in no way optimized, and does require a little work if to be used for other types of analysis.

In the ActivationAnalasis folder the mFRR_2023_15min file is the main file for comparison where initially the plan was to look at both the times before new year and after, where these times are the aggregated bids after the Norwegian mFRR market changed from 1 hour bids to 15 minutes. Because both price files from before and after new year were missing data points, the time after new years was considered a long enough time interval to get a decent analysis of the how much money was in the system. 
The analysis is all done in one file, and there are a lot of unused data that is collected and unused variables that should have been coded as local, and not global. A decent amount of extra work went into reading the data from the csv files, as the readability of the files is negatively impacted if they are opened and saved excel, even without changes to the files. The files prices files for 2024 were incomplete, and to make it easier to run the script the data files were modified by inserting prices of 0 in both directions for the missing timeslots. 

In spotpriceanalaysis there are a 7 different analysis files, each corresponding to a specific set of constraints for the optimization. 
