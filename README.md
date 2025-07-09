# 📊 Analyzing the Relationship Between Education and Income Using UCI Adult Dataset

This is a soft-stakes data science project centered around analyzing a person's *level of education* against their *income* using the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult).

Here’s what the project entails:

- Obtaining and preprocessing the real-world census data
<br>- Visualizing income distribution in relation to education
<br>- Creating a simple predictive model to determine whether an individual earns above $50,000 annually.

---

## 🧠 Goals

To address the following

> **Is income influenced by education?**

---

## 📁 Dataset

- **Link:** [UCI Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)

- **Filename:** `adult_data.csv`

- **Features:** Age, Education, Hours-per-week, Income and others (full list provided below)

---

## 📊 Actions Taken

1. **Dataset Formatting**

   - Completed form submissions

   - Segregation of data into structured tables with the use of Pandas DataFrame

2. **Exploratory Data Analysis**

   - Counted the number of individuals in each income bracket and categorized them by their level of education 

   - Calculated the ratio of individuals earning above 50K with each level of education 

   - Developed bar graphs using Matplotlib and Seaborn 

3. **Model Development**

   - Utilizing Logistic Regression with the predictors `education-num`, `age`, and `hours-per-week` 

   - Obtained an Accuracy of **~78%**

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Seaborn & Matplotlib
- Scikit-learn (Logistic Regression)

## 🚀 How to Run This

1. Download the dataset (`adult.data` or `adult_data.csv`)
2. Run the Jupyter Notebook in Google Colab or Jupyter Lab
3. Make sure required libraries are installed

## 📄 License

This project is for educational use only. Dataset © UCI Machine Learning Repository.
