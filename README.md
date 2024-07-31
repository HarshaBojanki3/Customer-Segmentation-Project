# Customer Segmentation Project

## Objective
Segment customers based on their purchasing behavior to help a retail company understand different customer groups and tailor marketing strategies.

## Data Description
The dataset contains transactions from a UK-based online retail company from December 2010 to December 2011. It includes details such as invoice number, stock code, quantity, invoice date, unit price, customer ID, and country.

## Steps Taken
1. **Data Collection:** Loaded the dataset from the UCI Machine Learning Repository.
2. **Data Cleaning:** Removed missing values, handled outliers, and created a TotalPrice column.
3. **Exploratory Data Analysis (EDA):** Analyzed total sales and number of orders by country.
4. **Feature Engineering:** Calculated Recency, Frequency, and Monetary value for each customer.
5. **Model Selection:** Used K-Means clustering to segment customers.
6. **Model Training and Evaluation:** Evaluated clustering using the silhouette score.
7. **Visualization:** Visualized clusters in 2D and 3D plots.

## Key Findings
- Identified 4 distinct customer segments.
- Detailed characteristics of each segment.

## How to Run the Code
1. Clone the repository.
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    ```
2. Navigate to the project directory.
    ```bash
    cd yourrepository
    ```
3. Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
    ```
4. Run the Jupyter notebook.
    ```bash
    jupyter notebook Customer_Segmentation_Project.ipynb
    ```

## Files
- `Customer_Segmentation_Project.ipynb`: Jupyter Notebook containing the code for the project.
- `README.md`: Documentation for the project.

## Additional Notes
- This project demonstrates skills in data cleaning, exploratory data analysis, feature engineering, clustering, and visualization.
- The dataset was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).

## References
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
