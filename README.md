# Analysis-and-Prediction-of-Crop-Yield

In this project, Several datasets of rainfall, temperature, pesticides and reliable information about crop yield history were used to produce predictions for the future.
Data Set Source: 
Pesticide, Yield - FAO(http://www.fao.org/home/en/)
Temperature and Rain Fall - World Bank Open Data(https://data.worldbank.org/)

Data: Data is merged from different datasets for crop yield prediction. The datasets merged are yield, rainfall, pesticides and temperature datasets. It is done using Year and Area features which are the common attributes in all the datasets.

Machine Learning Models:

We obtain from the preprocessing stage the final data frame. It consist of rainfall, temperature (average), and pesticide data. this data is sorted by area and the type of crop- for example rice, paddy, sorghum, etc. The main objective is to develop a yield prediction model.
We apply the following models-
1. Multiple Linear Regression Model
2. Decision Tree Regressor
3. Classification Based Approach for Yield Prediction

Final Result:
Classification Based Approach gives a higher accuracy than the other 2 models while predicting the crop yield.

Things to Consider for a better Result:
A lot of missing variables like soil quality, humidity, pest like locust etc 
Can look for a relation between abnormal yields and absolute deviations of factors (rainfall, fertilizer, temperature) from their ideal values
Could explore non-linear relationships (other than using decision tree- ANN)
