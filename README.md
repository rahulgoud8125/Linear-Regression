# 🏠 Linear Regression

This project predicts house prices using Linear Regression.
We used the Housing.csv dataset and built a machine learning model step by step.


**1️⃣ Loaded the Dataset**

We imported the Housing.csv file into Python and checked the data.

**2️⃣ Cleaned & Preprocessed the Data**

Some columns had text values like Yes/No or unfurnished/furnished.
Machine Learning models only understand numbers, so we converted them.

✔ Ordinal Encoding

For furnishingstatus (it has order):

unfurnished → 0

semi-furnished → 1

furnished → 2

✔ Label Encoding

For Yes/No columns:

mainroad

guestroom

basement

hotwaterheating

airconditioning

prefarea

Yes → 1
No → 0

**3️⃣ Split the Data**

We divided the data into:

Training data (80%) – used to teach the model

Testing data (20%) – used to check how well the model predicts

**4️⃣ Built Linear Regression Model**

We used LinearRegression() to train the model.

The model learned the relationship between:
✔ area
✔ bedrooms
✔ bathrooms
✔ mainroad
✔ furnishingstatus
✔ and many more…

and price.

**5️⃣ Predicted House Prices**

The model was used to predict prices for the test data.

**6️⃣ Evaluated the Model**

We measured how accurate the predictions were using:

MAE – average error

MSE – squared error

RMSE – root of error

R² Score – how well the model fits the data

**7️⃣ Plotted Graphs**

To better understand the model, we created:

✔ Actual vs Predicted graph

Shows how close predictions are to real prices.

✔ Simple Regression Line (Area vs Price)

Used only the area column to draw a straight regression line.

✔ Area vs Price scatter plot

Shows direct relationship between area and price.

✔ Correlation Heatmap

Shows which features strongly affect the price.
