# 🍽️ Zomato Restaurant Votes & Rating Analysis

An Exploratory Data Analysis (EDA) project focused on analyzing customer votes and evaluating their correlation with restaurant ratings using Python data science tools.

---

## 📌 Project Overview
The primary objectives are:
1. Identifying restaurants receiving the **highest** and **lowest** number of customer votes.
2. Analyzing whether a statistical **correlation** exists between the total number of votes and the average rating (`rate`) of a restaurant.

---

## 📚 Libraries & Tech Stack Used

* **[Pandas](https://pandas.pydata.org/):** Data loading, filtering, missing value handling, and calculating Pearson correlation coefficients.
* **[NumPy](https://numpy.org/):** Numerical computations and array manipulations.
* **[Matplotlib](https://matplotlib.org/):** Customizing plots, setting figure dimensions, titles, and layout configurations.
* **[Seaborn](https://seaborn.pydata.org/):** High-level statistical data visualization (Scatter plots).

---

## 🛠️ Key Workflows & Insights

* **Extreme Values Analysis:**
  * Extracted top-performing restaurants with maximum user traction using `df['votes'].max()`.
  * Highlighted newly established outlets or less popular spots with minimum votes.

* **Correlation & Visualization:**
  * Computed Pearson correlation between `votes` and `rate`.
  * Generated Seaborn scatter plots to display how highly-rated restaurants consistently attract significantly more votes due to social proof and customer popularity.

---
