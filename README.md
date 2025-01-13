# Sales Prediction

Welcome to the **Sales Prediction** repository! This project demonstrates time-series forecasting to predict future sales based on historical data.

## Dataset
The dataset used for this project can be downloaded from Kaggle:

[Sales Dataset on Kaggle](https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input)

## Steps to Run the Model

### 1. Download the Dataset
1. Visit the Kaggle link provided above.
2. Sign in or create a Kaggle account if you haven't already.
3. Download the dataset as a `.csv` file to your local machine.

### 2. Open the Colab Notebook
1. Click on the provided Google Colab link to open the notebook.
2. Alternatively, upload the `.ipynb` notebook file from this repository to Google Colab.

### 3. Upload the Dataset
1. In the Colab notebook, locate the cell with the following code snippet:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
2. Execute the cell. A file upload prompt will appear.
3. Upload the `.csv` dataset you downloaded from Kaggle.

### 4. Execute the Notebook
1. Run each cell in the Colab notebook sequentially by clicking on the play button next to each cell.
2. Observe the output for each step, including data exploration, preprocessing, model training, and evaluation.

## Project Overview
The notebook is divided into the following sections:

1. **Data Loading and Preprocessing**
   - Loading the dataset and handling missing values.
   - Formatting date features and extracting relevant time-based information.

2. **Feature Engineering**
   - Creating features like day of the week, month, and quarter to capture seasonal and temporal patterns.

3. **Exploratory Data Analysis (EDA)**
   - Visualizing trends, seasonality, and anomalies in the sales data.

4. **Model Building**
   - Using the ARIMA (AutoRegressive Integrated Moving Average) model for time-series forecasting.
   - Splitting the data into training and testing sets.

5. **Model Evaluation**
   - Evaluating the model using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Dependencies
The following Python libraries are required to run the notebook:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`

These dependencies are installed in the Colab environment by default. If you're running the notebook locally, install them using:
```bash
pip install numpy pandas matplotlib statsmodels
```

## Additional Notes
- Ensure that the dataset filename matches the one used in the notebook code. If the filename is different, update the relevant code cell.
- For time-series analysis, ensure the date column is correctly parsed and set as the index.
- For any issues or questions, feel free to open an issue in this repository.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
