# Customer Churn Prediction Using Artificial Neural Networks (ANN)

## Overview

This repository contains a Jupyter Notebook designed to predict customer churn using Artificial Neural Networks (ANN). The project uses a dataset from a telecom company to build and evaluate a model that can forecast customer churn, helping businesses to identify at-risk customers and implement targeted retention strategies.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It includes 7043 records and 21 features, covering various aspects such as customer demographics, service subscription details, customer interactions, and usage patterns. The target variable is a binary indicator representing whether a customer churned.

## Features

- **Customer Demographics**: age, gender, location, etc.
- **Service Subscription Details**: subscription type, tenure, plan features, etc.
- **Customer Interactions**: call duration, frequency of interactions, complaints raised, etc.
- **Usage Patterns**: data usage, service utilization, etc.

## Requirements

To run the notebook, you need the following Python libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow

You can install these dependencies using `pip`:

```sh
pip install pandas numpy matplotlib scikit-learn tensorflow
```

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Open the Jupyter Notebook:
   ```sh
   jupyter notebook Customer_Churn_Prediction.ipynb
   ```

3. Follow the steps in the notebook to load the data, preprocess it, build and evaluate the ANN model.

## Notebook Structure

1. **Importing Required Modules**: Import essential libraries for data manipulation, visualization, and model building.
2. **Data Loading and Exploration**: Load the dataset and perform initial data exploration.
3. **Data Preprocessing**:
    - Handle missing values and convert data types.
    - Encode categorical variables and normalize numerical features.
4. **Data Visualization**: Visualize the data to understand the distribution and identify trends.
5. **Model Development**: Construct and train an ANN model using TensorFlow/Keras.
6. **Model Evaluation**: Evaluate the model performance using metrics like accuracy, precision, recall, and F1-score.
7. **Deployment**: Instructions for deploying the model to production environments.

## Data Preprocessing Steps

- **Handling Missing Values**: Convert `TotalCharges` to numeric after removing records with blank values.
- **Encoding**: Transform binary columns to 0/1 and apply one-hot encoding to categorical columns.
- **Normalization**: Normalize numerical features for better model performance.

## Visualization Examples

- **Tenure vs. Churn**: Visualize the correlation between customer tenure and churn rate.
- **Monthly Charges vs. Churn**: Analyze how monthly charges impact customer churn.

## Conclusion

This project provides a comprehensive approach to building a customer churn prediction model using Artificial Neural Networks. By following the steps outlined in the notebook, users can gain valuable insights into customer churn dynamics and develop robust predictive models to support business decisions.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

If you have any questions or suggestions, please open an issue or contact me at [your.email@example.com](mailto:omrajeetambe@gmail.com).
