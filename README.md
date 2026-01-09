# A Typology of American Voters (2024)
![Slide1](https://github.com/user-attachments/assets/17034b71-1227-4fbe-bb6e-56433200ce64)

## Project Overview
Using the American National Election Survey data from 2024, this project created a typology of American voters. K-means clustering results revealed 4 clusters of voters: (1) working class Christian tradtionalists; (2) progressive educated urbanites; (3) white conservative investor men; (4) diverse women with immigrant ties.

## Features
- Cleaned and recoded the survey responses.
- Implemented Multivariate Imputation by Chained Equations (MICE) for missing data on selected variables.
- Conducted Principal Component Analyses (PCA) to reduce dimensionality of survey items into 4 components.
- Implemented K-Means clustering and identified 4 clusters of voters.

## A Closer Look
### Context
Traditionally, in political science research, voters are classified on two dimensionality: social ideology and economic ideology. This classification results in 4 main clusters: (1) the right; (2) the left; (3) libertarians; (4) communitarians. While this typology has been immensely useful in helping us understand people's political attitudes and behaviors, we want to introduce a different classification, one that takes Americans' lived experiences and identities into account. 

### Methods and Data
We used data from the 2024 American National Election Studies. To begin, we cleaned and recoded the survey responses. Upon doing so, we noticed that there was a number of missing responses to the various measures of interest. To deal with this, we implemented MICE and then PCA to reduce dimensionality. A total of 41 survey items were reduced down to 4 principal components. We then used the 4 principal components to create our cluster of voters. 

### Main Findings
The results revealed a total of 4 clusters: 
- (1) working class Christian traditionalists
- (2) progressive educated urbanites
- (3) white conservative investor men
- (4) diverse women with immigrant ties




