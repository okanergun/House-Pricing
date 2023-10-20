# House Pricing

This project represents a data analysis and prediction project accomplished using a series of Python libraries and data analysis methods. The main libraries used in the project include ngboost, pandas, geopy, and scikit-learn. Below are explanations and code snippets for the main steps performed in the project:

1. Data Preparation:

The project imports necessary Python libraries before beginning data analysis. These libraries provide essential tools for data analysis and machine learning.

2. Retrieving Location Information with Nominatim:

The main issue with this problem was getting the neighbourhoods that model can't see, this issue was essential because in the real World we can not always have all the data in every subjects. Therefore my task was finding and filling the gap for the unknown neighbourhoods.
Location information for neighborhoods required for data analysis is obtained using Nominatim, an open-source geocoding service. This step represents the project's capability to work with geographical data.

3. Filling Missing Neighborhood Information:

The missing_mahalle_filling_geo function is used to fill missing neighborhood information. This is essential to prepare missing data for data analysis.

4. Data Encoding and Transformation:

The project includes encoding and transformation processes to convert categorical data into numerical data. This makes it easier for machine learning algorithms to be used.

5. Data Merging and Cleaning:

Relevant data frames are merged, unnecessary columns are removed, and data cleaning processes are performed. This prepares the data for data analysis.

6. Training a Machine Learning Model:

The project builds a prediction model on the training data using a machine learning model called ngboost. This provides a fundamental infrastructure for making predictions in the future.

7. Predictions and Results:

Predictions are made using the trained model, and the results are evaluated. This represents the primary goal of the project.
