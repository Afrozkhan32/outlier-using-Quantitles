# outlier-using-Quantitles
# Interquantile Analysis with Boxplot and Outlier Detection

This project provides a simple and visual explanation of **Interquartile Range (IQR)**, **Boxplots**, and **Outlier Detection** using Python. It is ideal for those who want to understand descriptive statistics, particularly the identification of outliers in a dataset.

## 📌 What’s Included

- Calculation of Q1, Q2 (median), and Q3
- Interquartile Range (IQR) computation
- Detection of outliers based on IQR
- Visualization using boxplots
- Example using a synthetic dataset

## 🧪 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib

## 📊 Sample Output

The notebook includes visualizations such as:

- Boxplot showing the quartiles and outliers
- Printed output of IQR values and identified outliers

## 🚀 How to Use

1. Clone this repository or download the `.ipynb` file.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Run all cells to view the analysis and visualizations.

## 🧠 Concepts Covered

- **Q1 (25th percentile):** Lower quartile
- **Q2 (50th percentile):** Median
- **Q3 (75th percentile):** Upper quartile
- **IQR = Q3 - Q1**
- **Outlier thresholds:** 
  - Lower bound: Q1 - 1.5 * IQR
  - Upper bound: Q3 + 1.5 * IQR

Any data points outside these bounds are considered outliers.

## 📂 File Structure

