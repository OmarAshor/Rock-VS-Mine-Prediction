# Sonar Data Classification

This repository contains a Python script that demonstrates the process of loading and analyzing sonar data, as well as training a logistic regression model for classification. The dataset used in this script is assumed to be named 'sonar data.csv'.

## Requirements
- Python (>=3.6)
- NumPy
- pandas
- scikit-learn

## Usage

1. Install the required dependencies:

```bash
pip install numpy pandas scikit-learn
```

2. Download the 'sonar data.csv' dataset and place it in the same directory as the script.

3. Run the script:

```bash
python sonar_classification.py
```

The script performs the following steps:

1. **Load and Explore Data:**
   - Load the sonar dataset into a Pandas DataFrame.
   - Display the first 5 rows of the dataset.
   - Print the shape (number of rows and columns) of the dataset.
   - Provide statistical measures of the data.

2. **Data Preprocessing:**
   - Explore the distribution of classes ('M' and 'R') in column 60.
   - Display the mean of the values in column 60.
   - Separate the labels ('M' or 'R') from the features and store them in variables `x` and `y`.

3. **Train-Test Split:**
   - Split the data into training (85%) and testing (15%) sets using stratified sampling.

4. **Logistic Regression Model:**
   - Create a logistic regression model.
   - Train the model using the training data.

5. **Model Evaluation:**
   - Evaluate the accuracy of the model on both training and testing data.

6. **Predictive System:**
   - Demonstrate the use of the trained model for making predictions.
   - Provide an example input data point.
   - Output whether the object is predicted to be a "Rock" or "Mine."

Feel free to modify the input data in the script for making predictions on different instances.

Note: Make sure to replace 'sonar data.csv' with the actual name of your dataset if it's different.
