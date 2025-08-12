# ice-cream-revenue-prediction
A data analysis project that uses Linear Regression to predict ice cream revenue based on temperature. Includes a Jupyter/Google Colab Notebook, dataset, and a Looker Studio dashboard.

# Ice Cream Revenue Analysis & Prediction

This project analyzes the relationship between temperature and ice cream sales revenue. A simple linear regression model was developed to predict revenue based on temperature fluctuations.

The entire analysis process, from data cleaning to modeling and visualization, is documented in the Jupyter Notebook included in this repository.

[![Looker Studio Dashboard](https://img.shields.io/badge/Looker%20Studio-Dashboard-blue?style=for-the-badge&logo=looker)](https://lookerstudio.google.com/reporting/312a8405-a3f1-4d25-ba32-d7b3fb73eee7/page/WYKUF)

## 📊 Interactive Dashboard

An interactive dashboard was created in Looker Studio to visualize the data and the model's predictions. You can explore the relationship between temperature and revenue, view averages, and filter the data using a temperature slider.

**[Click here to view the interactive dashboard](https://lookerstudio.google.com/reporting/312a8405-a3f1-4d25-ba32-d7b3fb73eee7/page/WYKUF)**

![Dashboard Screenshot](dashboard.jpg)

## 📈 Analysis and Key Findings

The analysis revealed a strong positive linear relationship between temperature and revenue. A linear regression model was trained using Scikit-learn to quantify this relationship.

### Linear Regression Model

The model learned the following equation to represent the data:

$$ \text{Revenue} = 21.44 \times \text{Temperature} + 44.27 $$

-   **Slope ($m$):** `21.44`
-   **Intercept ($c$):** `44.27`

**Conclusion:** The model indicates that for every 1°C increase in temperature, the ice cream revenue is expected to increase by approximately **$21.44**.

### Model Prediction

To test the model, we can predict the revenue for a given temperature.
* **For a temperature of 25°C, the predicted revenue is $580.31.**

### Visualization

The scatter plot below shows the data points and the fitted linear regression line, visually confirming the positive correlation.

![Linear Regression Plot](linear_regression.png)

## 💾 Dataset

This project uses the "Ice Cream Sales Dataset". The original data was sourced from Kaggle and can be found at the following link:

* **Source:** [Ice Cream Sales Dataset on Kaggle](https://www.kaggle.com/datasets/sakshisatre/ice-cream-sales-dataset)
* **Author:** Sakshi Satre

The file `df_final_ice_cream.csv` included in this repository is the cleaned version of the dataset used for this analysis. It contains two columns:
* `Temperature`: The temperature in Celsius (°C).
* `Revenue`: The corresponding sales revenue.

## 🛠️ Tools and Libraries Used

* **Programming Language:** Python
* **Libraries:**
    * Pandas (for data manipulation and analysis)
    * Matplotlib & Seaborn (for data visualization)
    * Scikit-learn (for building the Linear Regression model)
* **Environment:** Jupyter Notebook
* **BI Tool:** Looker Studio (for the dashboard)

## 🚀 How to Run this Project

To run the analysis on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/OYanEnrique/ice-cream-revenue-prediction.git
    cd ice-cream-revenue-prediction
    ```
2.  **Install the required libraries:**
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyterlab
    ```

3.  **Start Jupyter Lab:**
    ```bash
    jupyter lab
    ```

4.  Open and run the `ice_cream_data.ipynb` notebook to see the full analysis.
