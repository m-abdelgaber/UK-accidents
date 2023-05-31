# Preprocessing UK Road Accidents Dataset

This repository contains a Jupyter notebook that provides a step-by-step guide on how to preprocess the UK road accidents dataset from 1990 using Python libraries such as pandas, numpy, and sklearn.

## Dataset

The UK road accidents dataset from 1990 contains 258441 entries and 35 columns. It is a valuable resource for anyone interested in analyzing or modeling road accidents in the UK.

## Preprocessing Steps

The notebook covers several preprocessing steps that are essential for cleaning and preparing data for analysis or machine learning models. These steps include:

- Handling missing data
- Removing duplicates
- Encoding categorical variables
- Scaling numerical features
- Detecting/removing outliers

To handle missing data, the notebook shows how to identify NaN values in the dataset and how to fill them with appropriate values such as mean or median. It also demonstrates how to remove duplicate data using pandas' drop_duplicates() function.

For encoding categorical variables, the notebook uses one-hot encoding to convert categorical variables into numerical features that can be used in machine learning models. It also shows how to scale numerical features using StandardScaler from sklearn.preprocessing.

To detect and remove outliers from the dataset, the notebook uses LocalOutlierFactor from sklearn.neighbors. It explains how this algorithm works and provides code examples on how to use it.

Additionally, the notebook shows how to convert the CSV dataset into parquet format and save it to Google Drive for future use. It also includes visualizations such as scatter plots and histograms to help users understand the data better.

## Usage

To use this notebook, you will need Jupyter Notebook installed on your computer along with Python libraries such as pandas, numpy, matplotlib.pyplot, seaborn, datetime, scipy.stats, sklearn.preprocessing, sklearn.neighbors, and csv.

You can download the UK road accidents dataset from [data.gov.uk](https://data.gov.uk/dataset/road-accidents-safety-data). Once you have downloaded the dataset, you can open the Jupyter notebook and follow the step-by-step guide to preprocess the data.

## Conclusion

This notebook provides a comprehensive guide on how to preprocess datasets effectively using Python libraries. It is useful for anyone who works with data analysis or machine learning models and wants to learn best practices for cleaning and preparing datasets.
