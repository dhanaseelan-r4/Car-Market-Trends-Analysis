# Car Market Trends Analysis

Car market trends analysis using Python and basic machine learning.

## About the Project

This project focuses on analyzing car market data to understand the factors that affect the selling price of used cars.

The analysis looks at car prices, fuel type, seller type, transmission, vehicle age, kilometers driven, and popular car models. A basic Linear Regression model is also used to predict car selling prices.

## Objectives

- Understand the car dataset and its basic characteristics.
- Check and clean the data before analysis.
- Identify factors related to car selling prices.
- Compare selling prices across different categories.
- Study the relationship between car age, present price, and selling price.
- Find the most commonly listed car models.
- Build a basic model to predict selling prices.

## Dataset

The project uses a CarDekho car dataset containing information about used cars.

The main columns used in the analysis are:

- "Car_Name" – Name of the car
- "Year" – Manufacturing year
- "Selling_Price" – Selling price of the car
- "Present_Price" – Present/showroom price
- "Kms_Driven" – Kilometers driven
- "Fuel_Type" – Type of fuel used
- "Seller_Type" – Type of seller
- "Transmission" – Transmission type
- "Owner" – Number of previous owners

A new column, "Car_Age", was created to represent the age of each car.

## Data Cleaning and Preparation

The dataset was checked for:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Unique values in categorical columns

Duplicate records were removed where found.

The "Car_Age" feature was then created from the manufacturing year.

## Analysis

The following areas were explored during the project.

### Price and Data Distribution

The distributions of Selling Price, Present Price, and Kilometers Driven were examined using histograms.

### Category-wise Price Comparison

Average selling prices were compared across:

- Fuel Type
- Seller Type
- Transmission

### Relationship Between Variables

Scatter plots and a correlation matrix were used to study the relationship between selling price and numerical variables such as Present Price, Car Age, Kilometers Driven, and Owner count.

### Popular Car Models

The 10 most frequently listed car models were identified. Their number of listings and average selling prices were also compared.

## Key Findings

Some of the main observations from the analysis are:

- Present Price has a strong positive relationship with Selling Price, with a correlation of approximately 0.88.
- Car Age has a negative relationship with Selling Price, with a correlation of approximately -0.23.
- Automatic cars have a higher average selling price than manual cars in this dataset.
- Diesel cars have a higher average selling price among the fuel categories analyzed.
- Dealer listings have a higher average selling price than individual listings in this dataset.
- Honda City, Corolla Altis, and Hyundai Verna are among the most frequently listed models.
- Toyota Fortuner and Toyota Innova have relatively high average selling prices among the analyzed models.

## Predictive Modeling

A Linear Regression model was used to predict the selling price of cars.

The categorical variables were converted into numerical variables using one-hot encoding.

# The dataset was divided into:

- 80% training data
- 20% testing data

# The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. Load the dataset
2. Inspect the data
3. Clean duplicate records
4. Create the "Car_Age" feature
5. Perform exploratory data analysis
6. Create visualizations
7. Analyze correlations and popular models
8. Build the Linear Regression model
9. Evaluate the model
10. Summarize the findings

## Conclusion

The analysis provides an overview of the factors associated with used-car selling prices. Present Price, Car Age, Fuel Type, Seller Type, and Transmission show noticeable relationships with selling price in this dataset.

The Linear Regression model provides a basic approach to predicting car selling prices and demonstrates how data analysis and machine learning can be applied to a real-world car market dataset.
