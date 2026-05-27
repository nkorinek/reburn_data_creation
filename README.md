# reburn_data_creation
Code used to generate the reburn dataset for "Fire history and atmospheric drying jointly control reburn severity" paper.

# Notebook order
In order to recreate this workflow, the notebooks should be run in the following order:

1. reburns.ipynb - This was the initial dataset creation workflow
2. missing_data_fix.ipynb - This modified the initial dataset to fill in missing GRIDMET values and add Elevation variables, alongside other variables that weren't written out in the first notebook but were later needed for the analysis.
3. forest_threshold_test.ipynb - This removes a few events that were outside of the states we wanted to focus on, and fixes the forest filtering to be more in line with CBI requirments. 