------------------------------
## 🧹 Automated Data Cleaner GUI
An interactive web application built with Python and Streamlit that automates the tedious process of cleaning messy datasets. Upload any CSV or Excel file, let the tool instantly fix common formatting errors, and download your polished data with one click.


## ✨ Features

* Drag-and-Drop GUI: Interactive web browser layout powered by Streamlit. [3] 
* Smart Format Support: Seamlessly processes both .csv and .xlsx (Excel) formats.
* Auto-Deduplication: Identifies and permanently purges 100% identical duplicate rows. [4] 
* Whitespace Correction: Automatically trims invisible spaces from text columns.
* Missing Value Imputation:
* Blanks in Text columns are labeled as "Unknown".
   * Blanks in Numeric columns are auto-filled using the statistical Median.
* Before & After Previews: Displays interactive snapshots of your raw vs. cleaned tables.

## 🚀 Quick Start## Prerequisites
Make sure you have Python installed on your machine.
## 1. Clone the Repository

git clone https://github.com
cd Data_Cleaner_Tool-for-Data-Analysis

## 2. Install Required Packages

pip install streamlit pandas openpyxl

## 3. Launch the Application

streamlit run app.py

The app will automatically open in your local browser window at http://localhost:8501.
## 📂 Project Structure

├── app.py          # Streamlit UI configuration and cleaning algorithms
├── README.md       # Project documentation
└── test_data.csv   # Mock dataset with structural issues for evaluation

## 🛠️ Built With

* [Streamlit](https://streamlit.io/) - Web UI framework for Python data apps.
* [Pandas](https://pandas.pydata.org/) - High-performance data manipulation and restructuring.
* [OpenPyXL](https://openpyxl.readthedocs.io/) - Excel spreadsheet read/write engine.

------------------------------
