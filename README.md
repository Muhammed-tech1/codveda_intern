House Price Data Collection and Preprocessing
Project Overview

This project was completed as part of my Data Science Internship task.
The goal was to collect real estate data from a property listing website and prepare the dataset for machine learning by performing data cleaning and preprocessing.

The project is divided into two main stages:

Web Scraping – Collect house listing data from an online real estate website.

Data Understanding and Preprocessing – Clean and prepare the dataset for future machine learning models.

Task 1: Web Scraping

House listing data was collected from an online property website using Python.

The scraping process extracted information such as:

House Price

Location

Number of Bedrooms

Number of Bathrooms etc.

Other available property features

The scraped data was stored in a structured dataset using Pandas and exported to a CSV file for further analysis.

Task 2: Data Understanding and Preprocessing

After collecting the dataset, several preprocessing steps were performed to prepare the data for machine learning.

1. Data Understanding

The dataset structure was inspected to understand:

Feature types

Missing values

Data distribution

2. Data Cleaning

Cleaning steps included:

Handling missing values

Removing irrelevant data

Formatting numerical values

3. Feature Engineering

Relevant features were organized and transformed to improve model usability.

4. Outlier Detection

Outliers were identified using statistical techniques such as boxplots and the Interquartile Range (IQR) method.

5. Categorical Feature Encoding

Categorical variables such as location or property type were converted into numerical values using Label Encoding.

6. Feature Scaling

Numerical features were standardized using StandardScaler to ensure consistent feature scaling for machine learning models.

Tools and Libraries Used

The project was implemented using the following tools:

Python

Pandas

Scikit-learn

BeautifulSoup / Requests (for web scraping)

Output

The final output of this project is a cleaned and processed dataset saved as a CSV file, which can be used to build machine learning models for house price prediction.

Author

Muhammed Bello Abdullahi

Data Science Intern
