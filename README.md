# Statistical Analysis - Python
#### Statistical analysis of House sales in King County USA. This analysis showcases linear regression / multi-linear regression and predictions. 

### DATA SOURCE
#### [kaggle.com](www.kaggle.com)

### PROJECT AIM
#### This project aims to showcase my Python skills. I have built models and made predictions that would be useful for solving real-world problems. 

### PYTHON LIBRARIES USED : 
- Pandas
- Matplotlib
- Numpy
- Seaborn and
- Sklearn

## STEPS TAKEN 
#### Import
imported the required Python libraries. In this case, I imported Pandas, Matplotlib, Numpy, Seaborn, and Sklearn. This step also involves loading the data set into a dataframe using pandas. I also went ahead and checked data types for all columns before I began the next step. 
#### Data Wrangling
This step involves cleaning or scrubbing data. I started this step by removing columns Id and Unnamed : as these were not purposeful for further use. Then, I checked for missing values and replaced those missing values with mean values. 
#### Exploratory data analysis
I started this step by checking for outliers which can negatively affect by data. I created a boxplot to see if there are any outliers existing in regards to waterfront and price. I also used a scatterplot to see if there was any positive or negative correlation between the square feet of the house and the price. 
#### Model development
I started this step by making a single linear regression model to predict price using the longitude and square feet of the house and went further to calculate R^2. After that, I decided to use a multi-linear regression model to predict price using all the features of the house and location. As  these models are repetitively used, I created a pipeline using scale, polynomial, and model as estimators and StandardScaler, PolynomialFeatures, and LinearRegression as model constructors. After that, I predicted the price and calculated R^2 again.  
#### Model refinement
I started this step by importing the models required. I imported cross_val_score and train_test_split. Then, I segregated data into 2 portions each to be used for training and testing respectively. Then calculated R^2 using the ridge regression object. After that, I performed a second polynomial on the training and testing data set to find out their respective R^2. 

## CONCLUSION
This project was part of a graded assignment where I was graded based on the syntax and calculations. This assignment was to test my knowledge and experience with Python, Statistics, and Data analysis. 
