# Transit Delay Predictor

## Overview
This is my first end-to-end data science project. It uses machine learning to predict public transport delays based on external factors like weather conditions and city events. 

## Dataset
The data for this project was sourced from Kaggle:
* **Kaggle Dataset:** [Public Transport Delays with Weather and Events](https://www.kaggle.com/datasets/khushikyad001/public-transport-delays-with-weather-and-events)

Key features studied in this dataset include categorical variables like `event_type` and numerical targets like `actual_departure_delay_min`.

## Tech Stack
* **Language:** Python
* **Environment:** Visual Studio Code (VS Code) utilizing Jupyter Notebooks (`.ipynb`) for iterative, block-by-block development.
  
* **Libraries:**
  * `pandas`: Used for data manipulation, handling missing values, and one-hot encoding.
  * `scikit-learn`: Used to split the data and train the machine learning model.

## Model & Results
* **Algorithm:** Linear Regression
* **Performance:** The baseline model achieved a Mean Squared Error (MSE) of 44.16, which translates to a Root Mean Squared Error (RMSE) of **6.65 minutes**. 
* **Interpretation:** This indicates that on average, the model's predictions regarding transit delays are off by roughly 6.65 minutes. 

## How to Run This Project
To recreate this work locally on your machine:
1. Clone this repository to your local computer.
2. Download the raw dataset from the Kaggle link provided above.
3. Place the extracted `.csv` file directly into the same folder as the Jupyter Notebook.
4. Run the notebook cells from top to bottom to view the data cleaning process and final model evaluation.
