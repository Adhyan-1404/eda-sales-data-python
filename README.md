
# Overview of EDA on Sales Data

This project performs Exploratory Data Analysis (EDA) focused on cleaning and preprocessing a raw sales dataset (`k_circle_sales.csv`) sourced from Kaggle. 
The primary goal is to transform raw, messy sales data into a consistent, structured, and machine-learning-ready format. 
This preparation ensures high data quality for downstream predictive modeling and analysis.

In this project, popular Python libraries which are utilized for data manipulation and visualization are :

* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**

**Note:** The `warnings` module in Python is used to manage and suppress warning messages during execution.

___

### Key Steps Performed :

* Handling and imputing **Missing Values** to ensure dataset completeness.
* **Feature Engineering** to create meaningful variables for machine learning models
* **Detecting** and **Treating Outliers** to improve data robustness
* **Correcting incorrect** or **Inconsistent Values** (e.g., negative sales, invalid dates)
* Generating **Summary Statistics** for data validation
* Reducing **Skewness** and applying **Transformations** to approximate **Normality**, optimizing model performance

These steps were accomplished using a combination of data transformations, imputation techniques, and visualizations to get a comprehensive understanding of the dataset.

### How to run the code :

Make sure to update the **file path** for `k_circle_sales.csv` in the notebook **EDA on Sales Data.ipynb** to match your local directory. Failing to do so will result in a **error**. Also make sure all the necessary **Python libraries** (Numpy, Pandas, Matplotlib, Seaborn) are already installed.

You can run the notebook directly in Jupyter or use an online service like [Google Colab](https://colab.research.google.com) by uploading the notebook file.

* Interactive Notebook : [Click to Open](./eda_sales_data.ipynb)
* Static HTML : [Click to Open](./eda_sales_data.html)

---

### Repository Files :

* `EDA on Sales Data.ipynb` – Jupyter Notebook containing the full code and detailed workflow of the data cleaning and EDA process.
* `EDA on Sales Data.html` – Rendered HTML version of the notebook showcasing code and output (non-editable).
* `k_circle_sales.csv` - Raw sales data sourced from Kaggle.
* `README.md` - This project overview.
