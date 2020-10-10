# Dataset description:
- dataset constain 30 variables: 13 numeric and 17 non numeric variables
- variable studytime, granular had negative values -> it was make a desicion to delete the variable

# In PART I we analysed all numeric variable. 
- There were many missing values, which were replaced by the most frequent value.
- some values were deleted, which do not pass to the answers in the dataset due to mistake in the surves
- score variable was cleaned from outliers and checked for distibution, to do further analysis with non numeric variables: score is normal distributed due to test- qq plot is not very clear as the histogram also
- looked for correlation between score and all numeric variables. 
- The correlation is not very strong in all of the variables, but it was made a decition to take the following: age, medu, studytime, failures, goout, absence

# In PARt II anasis of non numeric varibales
- the most of them had many missing values, replaced through all the values in the variable, equally distributed, so the distibution is not changed
- checked the uniques values
- analysed boxplots
- made ttest to fild statistical significant dependencies between score and all non numeric variables

CONCLUSION:
- new dataset consists following variables: score, age, medu, studytime, failures, goout, absences, sex, address, mjob, schoolsup 
