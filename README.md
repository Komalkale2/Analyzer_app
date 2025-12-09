Here is the full Markdown code for your `README.md` file. It prominently features the Streamlit Cloud URL you provided and details the functionality of your **Multi-Graph Data Analysis Web App**.

You can copy and paste the code below directly into a new file named `README.md` in the root of your GitHub repository.

````markdown
# 📊 Multi-Graph Data Analysis Web App

## 🚀 Live Application
This application is deployed on Streamlit Cloud and is currently running live. Click the badge below to launch the app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://analyzerapp-e3uzkbtn3yxkmsnp5auaf3.streamlit.app/)

**Live URL:** [https://analyzerapp-e3uzkbtn3yxkmsnp5auaf3.streamlit.app/](https://analyzerapp-e3uzkbtn3yxkmsnp5auaf3.streamlit.app/)

---

## 💡 Project Overview
This web application provides an intuitive, no-code interface for quickly analyzing and visualizing data from uploaded CSV files.

Built using **Streamlit**, it allows users to seamlessly upload their data, view descriptive statistics using **Pandas** and **NumPy**, and generate various plots using **Matplotlib**. It's the perfect tool for initial data exploration and quality checks.

---

## ✨ Key Features

* **CSV Upload:** Easily upload and load data from any standard CSV file.
* **Data Preview:** View the first few rows of the uploaded dataset.
* **Descriptive Statistics:** Generate full statistical summaries and calculate custom data ranges (Max - Min).
* **Interactive Visualization:** Generate three main plot types based on user selection:
    * **Histograms** (for single numerical distribution analysis).
    * **Bar Charts** (to visualize category counts).
    * **Scatter Plots** (to show the relationship between two numerical variables).

---

## 🛠️ Local Installation and Setup
If you want to run or contribute to this application locally, follow these steps:

### 1. Clone the Repository
```bash
git clone [https://github.com/Komalkale2/Analyzer_app.git](https://github.com/Komalkale2/Analyzer_app.git)
cd Analyzer_app
````

### 2\. Install Dependencies

Ensure you have Python installed. Install the required libraries using the corrected `requirements.txt` file:

```bash
pip install -r requirements.txt
```

*(This command assumes you have created the `requirements.txt` file containing `streamlit`, `pandas`, `numpy`, and `matplotlib`.)*

### 3\. Run the Application

Execute the Streamlit command, pointing it to your main file (`Analyzer_app.py` based on the deployment path):

```bash
streamlit run Analyzer_app.py
```

The application will automatically open in your default web browser (usually at `http://localhost:8501`).

-----

## 📚 Dependencies

This project relies on the following major Python libraries, listed in `requirements.txt`:

  * `streamlit`
  * `pandas`
  * `numpy`
  * `matplotlib`

<!-- end list -->

```
```
