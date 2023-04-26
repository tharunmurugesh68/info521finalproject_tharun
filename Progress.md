# Final project progress report
### ISTA421/INFO521

-------

Project: Detection and Visualization of Earthquake Data with respect to Tectonic Plates
Names:
- Tharun Murugesh R
- Shanmuganathan C

-------


## Instructions

You report should be a short summary of your project progress. This report is relevant to to us, your instructors, and probably to the rest of the class.

Please use this report as a chance to organize your thoughts about what you are trying to do with your project, and to get feedback on your ideas, and the approaches that you have tried so far.

## Submission

Please commit this file to your GitHub repo (progress.md) AND to D2L.


-------

### GitHub repo usage
_Describe the current structure of your repo, the number of commits, and the steps you have taken to ensure the reproducibility of your code_
Our GitHub repo consists of files relevant to our project. It includes our initial proposal and our work done so far with respect to this project. 4 commits have been done so far from the beginning.

### Summarize your data
_Describe the characteristics of your data, any transformations that you have considered, or potential issues that you have faced (e.g. missing data)_
The data to be used for this project is from the website of the National Centers for Environmental Information, which is part of the National Oceanic and Atmospheric Administration wing. The dataset comprises of 41 columns and 3969 rows. Our data consists of numeric, character, integer and factor data. We have added few more columns to the data set to categorize the earthquake epicenters with respect to country , continent and tectonic plate. The dataset had a few potential issues like missing values and presence of redundant columns.

### Describe your initial analysis strategy
_What was your initial plan?_
We had initially planned to pre-process the entire dataset by removing the NA values and adding new columns which were helpful for our analysis. We wanted to visualize the earthquake data with respect to Continent, Tectonic Plate and Country to see which were most affected due to earthquakes. We had categorized the observations on the basis of the latitude and longitude i.e. coordinates of the earthquake's epicenter. We also wanted to visualize the earthquake epicenters on a world map as well and carry out multiple linear regression to predict magnitudes of earthquakes. 

### What you have tried so far?
_Describe your current implementation_
We have created new columns on the basis of epicenter coordinates for continent, country and tectonic plate. We have successfully visualized the earthquake data with respect to geographical parameters using world maps, bar plots and boxplots. We have also made use of loops to categorize the earthquake magnitude with respect to the Richter scale. We have tried to implement multiple linear regression to predict the earthquake magnitude with respect to the 1800s (testing data) using the data from 1900s till date as the training data. 

### What worked and what did not
We were able to categorize the data with respect to continent, country and tectonic plate and able to get insights about each geographical parameter. The visualization plots and maps have come out well. But we had faced a few issues while pre-processing our data due to the presence of NA values and it has impacted our multiple linear regression model by giving inaccurate results.

### What you plan to do next...
We look to further pre-process our data which will be suitable for future implementations. We also wish to compute pairwise correlations and visualize the same. We will once again implement multiple linear regression using the newly pre-processed data and carry out classification algorithms as discussed in our initial proposal. 

- Week 1: Further pre-process data and once again implement regression models 
- Week 2: Implement Classification algorithms for classifying earthquake magnitude on basis of magnitude class and evaluate model performance
- Week 3: To try and implement raster maps for projecting risky areas (prone to earthquakes) and proceed with code corrections and report drafting

### Author contributions
_Describe the contributions of each of the members to the current version of the project_

Student 1: Tharun Murugesh R
- [x] Development of question / hypothesis;
- [x] Data research: search for relevant data to contribute to question;
- [ ] Literature review;
- [x] Analysis strategy;
- [x] Analysis code;
- [x] Code review;
- [x] Work planning and organization;
- [x] Improving teamwork and collaboration;
- [x] Testing code and procedures;
- [ ] Writing report.
- [ ] Additional comments:

Student 2: Shanmuganathan C
- [ ] Development of question / hypothesis;
- [x] Data research: search for relevant data to contribute to question;
- [x] Literature review;
- [x] Analysis strategy;
- [x] Analysis code;
- [x] Code review;
- [x] Work planning and organization;
- [x] Improving teamwork and collaboration;
- [x] Testing code and procedures;
- [ ] Writing report.
- [ ] Additional comments:
