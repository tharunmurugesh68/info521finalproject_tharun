# Final projects (Fall 2022)
### ISTA 421/ INFO 521
------
# Project Overview
### The purpose of our study is to establish a relationship between earthquakes and tectonic plates, taking into account the magnitude and focal depth and see which tectonic plates have incurred most impact. 
### We also aim to create a model that is able to predict the scale and depth of an earthquake and try to forecast disaster prone areas with respect to past occurrences.
### The above mentioned tasks are to be fulfilled with the help of sufficient EDA, visualizations, regression, classification algorithms and time-series forecasting.

# Methods
## Data Manipulation/Preprocessing
### Data Loading -> Using read.csv() function
### Usage of if-else loops -> For categorizing the recorded earthquakes based on its scale and focal depth 
### Data type conversion -> Character columns into factor columns
### Data Preprocessing ->Creation of subset (without NAs) from main dataset to be used for carrying out analysis, regression and classification

## Visualization
### Tables -> Categorizing earthquake data according to country, continent, tectonic plate, magnitude and depth classes. 
### Bar plots -> 
### Number of occurrences in each continent and tectonic plate.
### Frequency of Strong, Major quakes and Shallow, Intermediate quakes.
### Box plots -> Variations in Magnitude and Focal depth. 
### Line plots -> Frequency of earthquakes and variations in magnitude over a time period.
### Maps -> Visualizing earthquake coordinates on a world map. 
### Correlogram -> Establishing a relationship among the variables used.

## Models
### Multiple Linear Regression -> To predict the magnitude of an earthquake that has taken place before 1976.
### Training and Testing Data ->
### Training set comprises of data from 1976 till 2022.
### Testing set comprises of data from 1880 till 1975.
### Backward approach -> For eliminating statistically insignificant variables.
### Implement linear model with variables having p-value < 0.05 for predicting magnitude of quakes before 1976.

### Classification -> 
### To predict the scale of an earthquake 
### To predict focal depth of an earthquake
### Algorithms -> 
### Logistic Regression
### Random Forest
### Boosting
### Decision Tree
### Confusion Matrices -> To compute the accuracy and other statistical information with respect to the particular model.

### Raster Map -> Low quality pixel-map used for visualizing forecasted coordinates.
### Time series -> Separate for Latitude & Longitude. 
### Parameters -> Starting and Ending dates, Frequency.
### ARIMA (Autoregressive Integrated Moving Average )-> Forecasting the coordinates of epicenters of future occurrences based on the time series created.

## Results/Discussion

### Upon carrying out classification models like random forest, boosting and logistic regression for classifying the earthquakes on basis of magnitude and depth class, boosting model obtained the highest accuracy when compared with the other models.

## Our file fpquake.Rmd contains our entire code chunk and report enclosed together.
