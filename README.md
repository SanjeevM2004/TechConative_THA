# TechConative_THA - House Sales Price Prediction Analysis - SANJEEV M - BE21B034

This project analyzes and predicts house sales prices based on historical sales data, using multiple machine learning models such as **Random Forest** and **Ridge Regression**. The project includes preprocessing steps for handling numerical and categorical data, feature encoding, and model evaluation using metrics such as RMSE (Root Mean Squared Error) and R² Score.

## Project Structure

- **data_analysis.ipynb**: Main notebook containing the code for data preprocessing, model training, and evaluation.
- **README.md**: Documentation and instructions for using the project.

## Data

This project requires a dataset with columns labeled as `SalePrice` (target variable) and other relevant features including both categorical and numerical data. Please ensure that:
- **SalePrice** is the target column for prediction.
- Other columns include relevant features, such as property details, location, or time-based features like year.

## Installation and Setup

1. Clone the repository (or download the files if not hosted on GitHub):

   ```bash
   git clone https://github.com/yourusername/house-sales-prediction.git
   cd house-sales-prediction
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Place your dataset file (e.g., `data.csv`) in the project folder and ensure it contains `SalePrice` and other relevant features.

## Usage

### Running the Analysis

1. Open `data_analysis.ipynb` in Jupyter Notebook:

   ```bash
   jupyter notebook data_analysis.ipynb
   ```

2. Run each cell to execute the code for:
   - **Data Preprocessing**: Identifies and encodes categorical features while retaining numerical features.
   - **Model Training**: Trains several models, including **Random Forest** and **Ridge Regression**.
   - **Evaluation**: Computes RMSE and R² Score for each model.

### Code Overview

#### Data Preprocessing

The dataset is preprocessed by:
- **Encoding Categorical Features**: One-hot encoding is used to convert categorical columns.
- **Handling Missing Values**: Numerical columns are filled with the mean value, and categorical columns are filled with the most frequent value.

#### Model Training

Several regression models are applied to predict house prices, including:
- **Random Forest Regressor**
- **Ridge Regression**

Each model’s performance is measured with RMSE and R² score, allowing for comparison of prediction accuracy.

### Example Output

After running the notebook, you should see model evaluation metrics similar to this:

```
Random Forest - Root Mean Squared Error (RMSE): 24000.00, R^2 Score: 0.85
Ridge Regression - Root Mean Squared Error (RMSE): 28000.00, R^2 Score: 0.80
```

## Contributing

Feel free to contribute to the project by adding more models, improving preprocessing, or enhancing documentation. 

1. Fork the repository.
2. Make your changes.
3. Create a pull request.

## License

This project is licensed under the MIT License.

---

Let me know if there are additional details or customization you’d like included in this README.