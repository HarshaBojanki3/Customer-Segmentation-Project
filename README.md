# Customer Segmentation Project

## Objective
Segment customers based on their purchasing behavior to help a retail company understand different customer groups and tailor marketing strategies.

## Data Description
The dataset contains transactions from a UK-based online retail company from December 2010 to December 2011. It includes details such as invoice number, stock code, quantity, invoice date, unit price, customer ID, and country.

## Steps Taken
1. **Data Cleaning:** Removed missing values, handled outliers, and created a TotalPrice column.
2. **Exploratory Data Analysis (EDA):** Analyzed total sales and number of orders by country.
3. **Feature Engineering:** Calculated Recency, Frequency, and Monetary value for each customer.
4. **Model Selection:** Used K-Means clustering to segment customers.
5. **Model Training and Evaluation:** Evaluated clustering using the silhouette score.
6. **Visualization:** Visualized clusters in 2D and 3D plots.

## Key Findings
- Identified 4 distinct customer segments.
- Detailed characteristics of each segment.

## How to Run the Code
1. Clone the repository.
2. Install required libraries:
    ```
    pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
    ```
3. Run the Jupyter notebook.

## Files
- `Customer_Segmentation_Project.ipynb`: Jupyter Notebook containing the code for the project.
- `README.md`: Documentation for the project.
