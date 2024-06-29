# Mileage Prediction Using Regression Analysis

This project is aimed at predicting the miles per gallon (MPG) of vehicles using linear regression based on various features.

# Dataset

The dataset used for this project includes the following columns:
- mpg: Miles per gallon
- cylinders: Number of cylinders
- displacement: Engine displacement (cu. in.)
- horsepower: Engine horsepower
- weight: Vehicle weight (lbs)
- acceleration: Time to accelerate from 0 to 60 mph (seconds)
- model_year: Model year of the car
- origin: Origin of the car (e.g., USA, Europe, Japan)
- name: Name of the car model

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Steps:

**1. Data Preprocessing**
- Load the dataset.
- Handle missing values by imputing or removing them.
- Normalize or standardize the data if necessary.

**2. Feature Selection**
- Analyze the features and their correlation with the target variable (MPG).
- Select features that contribute the most to the prediction.

**3. Model Training**
- Split the data into training and testing sets.
- Train the linear regression model using the training set.
- Tune hyperparameters to improve model performance.

**4. Model Evaluation**
- Use the testing set to evaluate the model.
- Calculate metrics such as Mean Squared Error (MSE) and R-squared.
- Plot the predicted vs. actual MPG values to visualize model performance.

# Conclusion

Linear regression effectively predicts the MPG of cars using features like horsepower, weight, and displacement. This model provides valuable insights into the factors influencing vehicle fuel efficiency, aiding in the design and selection of more efficient cars.
