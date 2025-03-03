# Data Cleaning with Pandas - House Price Prediction Dataset

## Project Description

This project focuses on data cleaning techniques using Python's powerful libraries, such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The dataset used is the **House Price Prediction Dataset**, which contains various features of homes (such as size, location, and amenities) and the corresponding prices. The goal of this project is to clean the dataset by addressing missing values, handling columns with high missing data, and preparing the dataset for further analysis or machine learning.

## Key Steps

The project follows the typical data cleaning pipeline:

1. **Data Loading and Initial Exploration**:
   - Loaded the dataset using `pandas.read_csv()` and explored the structure of the data.
   - Displayed dataset shape and info to understand the number of rows, columns, and types of data.

2. **Missing Value Analysis**:
   - Checked for missing values using `isnull().sum()` and visualized them with heatmaps.
   - Identified and visualized columns with a significant number of missing values.

3. **Handling Missing Data**:
   - Dropped columns that have more than 17% missing data as they are unlikely to contribute meaningful information.
   - Dropped rows with missing values to ensure the dataset is clean and ready for further analysis.

4. **Data Visualization**:
   - Used heatmaps to visualize missing data patterns and confirm that missing data was handled properly.

## Dataset Description

The dataset used in this project contains various features of houses and their sale prices. Each row represents an individual house, and the columns represent different features related to the house's characteristics. Below is a description of some key columns in the dataset:

- **OverallQual**: Overall material and finish quality.
- **GrLivArea**: Above grade (ground) living area square feet.
- **TotRmsAbvGrd**: Total rooms above grade (does not include bathrooms).
- **GarageCars**: Size of the garage in terms of car capacity.
- **GarageArea**: Size of the garage in square feet.
- **BsmtQual**: Evaluates the height of the basement.
- **PoolQC**: Pool quality (if applicable).
- **SalePrice**: The target variable representing the sale price of the house.

For a complete column-by-column description, please refer to the **[Dataset Description File](dataset_description.csv)** that outlines all features and provides insights into each attribute in the dataset. This will help you understand the relevance of each column and its role in the analysis.

## Key Libraries Used

- **Pandas**: For data manipulation, cleaning, and handling missing data.
- **NumPy**: For numerical operations and array manipulations.
- **Matplotlib & Seaborn**: For data visualization, including heatmaps to visualize missing data patterns.

## Dataset

The dataset used in this project is the **House Price Prediction Dataset**. It contains several features related to houses, such as the number of rooms, location, square footage, and more, along with their corresponding sale prices.

- Dataset source: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/BhavinDabhi29/House-price-prediction-data-clean.git
   ```

2. Navigate into the project directory:

   ```bash
   cd house-price-data-cleaning
   ```

3. Run the Jupyter notebook or Python script:

   ```bash
   jupyter notebook House_Price_Datacleaning.ipynb
   ```

## Results

After data cleaning, the dataset is ready for further analysis or machine learning tasks such as regression models to predict house prices. The cleaned data can now be used to build models and gain insights from the features of the dataset.

## License

This project is open-source and available under the [MIT License](LICENSE).
