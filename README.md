# A Typology of American Voters (2024)
![Slide1](https://github.com/user-attachments/assets/17034b71-1227-4fbe-bb6e-56433200ce64)

## Project Overview
Using the American National Election Survey data from 2024, this project created a typology of American voters. K-means clustering results revealed 4 clusters of voters: (1) working class Christian tradtionalists; (2) progressive educated urbanites; (3) white conservative investor men; (4) diverse women with immigrant ties.
<img width="1280" height="720" alt="Slide2" src="https://github.com/user-attachments/assets/dfdb6e99-a779-42e5-8339-cfe7af8ef401" />

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

![Slide3](https://github.com/user-attachments/assets/d83b3bd7-3124-4eb4-9fb6-51d85aa9f9ce)

![Slide4](https://github.com/user-attachments/assets/468cf084-acad-4954-a7e2-b24779739c8d)

![Slide5](https://github.com/user-attachments/assets/e6ce5157-c624-4637-98f2-4d61a81d4be0)

![Slide6](https://github.com/user-attachments/assets/b622a577-6026-4d2b-9cee-351ceb2c0507)

![Slide7](https://github.com/user-attachments/assets/01fabcd7-9ab0-4dac-b4f8-4d717c8e3dda)

![Slide8](https://github.com/user-attachments/assets/691daaa8-2473-4a29-8e1a-cbbb06f43ad4)

### Main Findings
The results revealed a total of 4 clusters: 
- (1) working class Christian traditionalists
  ![Slide9](https://github.com/user-attachments/assets/02cb9ca4-51ab-4a08-b939-1ccfb7a259c8)
- (2) progressive educated urbanites
  ![Slide10](https://github.com/user-attachments/assets/e70d3de7-9e0b-4bba-aea8-dbd23ba9b55c)
- (3) white conservative investor men
  ![Slide11](https://github.com/user-attachments/assets/96a71c56-953e-4ccf-8f2d-f2db74d4d74a)
- (4) diverse women with immigrant ties
  ![Slide12](https://github.com/user-attachments/assets/18f62390-6874-47e5-81f1-dff409d4c887)





