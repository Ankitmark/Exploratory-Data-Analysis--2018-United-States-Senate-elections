# Exploratory-Data-Analysis--2018-United-States-Senate-elections
Perform Exploratory Data Analysis on 2018 United States Senate elections

Given the following datasets:
• election_train.csv with results of the 2018 United States Senate elections, including the
number of votes received by each party (Democratic or Republican).
• demographics_train.csv with demographic information for United States counties
collected from 2012 to 2016 by the United States Census Bureau, including population,
age, gender, race and ethnicity, education, income, and other statistics
(www.census.gov/quickfacts/table/PST045215/00).

Perform the following tasks:
1. Reshape dataset election_train from long format to wide format. Hint: the
reshaped dataset should contain 1205 rows and 6 columns.
2. Merge reshaped dataset election_train with dataset demographics_train. Make
sure that you address all inconsistencies in the names of the states and the counties
before merging. Hint: the merged dataset should contain 1200 rows.
3. Explore the merged dataset. How many variables does the dataset have? What
is the type of these variables? Are there any irrelevant or redundant variables? If so,
how will you deal with these variables?
4. Search the merged dataset for missing values. Are there any missing values?
If so, how will you deal with these values?
5. Create a new variable named “Party” that labels each county as Democratic or
Republican. This new variable should be equal to 1 if there were more votes cast for the
Democratic party than the Republican party in that county and it should be equal to 0
otherwise.
6. Compute the mean median household income for Democratic counties and
Republican counties. Which one is higher? Perform a hypothesis test to determine
whether this difference is statistically significant at the 𝜶 = 𝟎. 𝟎𝟓 significance level. What
is the result of the test? What conclusion do you make from this result?
7. Compute the mean population for Democratic counties and Republican
counties. Which one is higher? Perform a hypothesis test to determine whether this
difference is statistically significant at the 𝜶 = 𝟎. 𝟎𝟓 significance level. What is the result
of the test? What conclusion do you make from this result?
8. Compare Democratic counties and Republican counties in terms of age, gender,
race and ethnicity, and education by computing descriptive statistics and creating plots
to visualize the results. What conclusions do you make for each variable from the
descriptive statistics and the plots?
9. Based on your results for tasks 6-8, which variables in the dataset do you think
are more important to determine whether a county is labeled as Democratic or
Republican? Justify your answer.
10. Create a map of Democratic counties and Republican counties using the
counties’ FIPS codes and Python’s Plotly library (plot.ly/python/county-choropleth/).
Note that this dataset does not include all United States counties.
