# Background Information that you need for classification

- There are multiple samples for each timepoint.
- We consider each unique timepoint/ patient combination (e.g. each row in our matrix)
- For stimulated features, we found the matching timepoint/patient unstimulated sample and subtracted stim-unstim. We always subtract unstim.
- Make sure that patients are kept together in cross validation 

Class_Y.Rdata --> The class of each patient (e.g. your response variable for classification) --> `Class_Y`

patient_name.Rdata --> the name of each patient. Use these to keep the same patients together in cross validation. --> `patient_name`

# Unstimulated Features
Joint_Unstim.RData --> the data matrix for unstim. --> `Joint`

# Stimulated Features
There are four different stimulations, TNFa, INFa, Cocktail, and P. gingavalis.

It should be straightforward to find their feature matrices in the folder

For example, 

INFa_Joint.RData --> Feature matrix for INFa --> `Joint_Stim` 
