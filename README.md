🎾 Tennis Match Data Analysis

Project Overview

This project was completed as a university group assignment.
The objective was to analyze scraped tennis match data and answer a set of analytical questions about players, matches, and performance metrics.

The dataset was provided as parquet files containing structured information about professional tennis matches. The analysis was performed using Python in a Jupyter Notebook environment.

---

Project Objectives

The main goals of this project were:

- To work with real-world scraped data
- To clean and preprocess raw datasets
- To perform exploratory data analysis (EDA)
- To answer analytical questions using statistical methods
- To extract meaningful insights from player and match data

---

Dataset Description

The dataset contains multiple tables with information about:

- Player profiles (height, nationality, etc.)
- Match results and winners
- Match duration
- Number of sets played
- Performance statistics such as aces

The data was originally scraped from a tennis-related website and distributed as parquet files.

---

Steps Performed in the Analysis

1. Data Loading

- Loaded multiple parquet files into dataframes
- Inspected the structure and columns of each dataset
- Checked data types and initial statistics

2. Data Cleaning

- Handled missing and inconsistent values
- Standardized column names and formats
- Removed invalid or duplicate records

3. Data Exploration

- Calculated descriptive statistics
- Analyzed distributions of player attributes
- Explored match characteristics such as duration and number of sets

4. Analytical Queries

The notebook answered several analytical questions, including:

Player-Based Analysis

- Number of unique players in the dataset
- Average height of players
- Country-wise player distribution
- Identification of top-performing players

Match-Based Analysis

- Total number of matches
- Longest recorded match
- Average match duration
- Typical number of sets per match

Performance Metrics

- Player with the highest number of wins
- Average number of aces per match
- Relationship between match duration and performance
- Identification of dominant players based on multiple statistics

---

Key Skills Demonstrated

- Data cleaning and preprocessing
- Working with parquet datasets
- Exploratory Data Analysis (EDA)
- Aggregations and statistical analysis
- Answering structured analytical questions
- Using Pandas and Polars for data manipulation

---

Tools & Technologies

- Python
- Pandas
- NumPy
- Polars
- Jupyter Notebook

---

Project Structure

data/       → raw parquet datasets (not uploaded due to size)
notebooks/  → main analysis notebook
README.md

---

Getting Started

Clone the repository

git clone https://github.com/soniasafaii/tennis_project.git
cd tennis_project

Install dependencies

pip install -r requirements.txt

Open the notebook

notebooks/TennisProject.ipynb

---

Contributors

- Sonia Safaei 
- Zeynab Jabarzade 
- Amir Ahmadi 
