# Predictive Analytics Using Historical Data

## Project Overview

This project focuses on building a predictive model using historical data to forecast future trends. It uses Linear Regression to analyze historical monthly sales data and predict sales for the next six months.

## Objective

* To clean and preprocess historical data.
* To build a predictive model using Linear Regression.
* To forecast future sales trends.
* To evaluate model accuracy using performance metrics.
* To visualize historical data and future predictions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* VS Code

## Dataset

The project uses a CSV file named `historical_data.csv`, containing monthly sales records.

**Note:** The dataset contains synthetic sample data created for learning and demonstration purposes. It is not real company data.

## Project Features

1. Data loading and preprocessing.
2. Handling missing and invalid values.
3. Removing duplicate records.
4. Training a Linear Regression model.
5. Evaluating model performance using MAE, RMSE, and R².
6. Forecasting sales for the next six months.
7. Visualizing historical sales and predicted trends.
8. Exporting future predictions to a CSV file.

## Project Structure

* `historical_data.csv` – Historical monthly sales dataset.
* `predictive_analytics.py` – Python source code for the predictive model.
* `requirements.txt` – Required Python libraries.
* `README.md` – Project documentation.
* `prediction_plot.png` – Graph generated after running the program.
* `future_forecast.csv` – File containing future sales predictions.

## Installation and Execution

### Step 1: Install Dependencies

Open the terminal in VS Code and run:

```bash
pip install -r requirements.txt
```

### Step 2: Run the Program

```bash
python predictive_analytics.py
```

### Step 3: View the Results

The program displays model evaluation metrics and forecasts for the next six months. It also generates a prediction graph and saves the forecast results to a CSV file.

## Model Evaluation

* **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
* **RMSE (Root Mean Squared Error):** Measures prediction error while giving more weight to larger errors.
* **R² Score:** Indicates how well the model explains variations in the test data.

Lower MAE and RMSE values generally indicate smaller prediction errors.

## Expected Outcome

The project demonstrates how historical data can be used to identify trends and forecast future sales. It provides practical experience in data preprocessing, regression modeling, model evaluation, and data visualization.

## Conclusion

This project helped me understand the fundamentals of predictive analytics and how machine learning can be used to forecast future trends based on historical data. It also improved my understanding of data cleaning, model evaluation, and visualization.

## Future Improvements

* Use real-world datasets.
* Explore time-series forecasting models.
* Include seasonal trends and additional variables.
* Compare multiple models to improve forecasting performance.
