🎬 Netflix Data Analysis (Exploratory Data Analysis)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover insights about content distribution, release trends, popular genres, and country-wise production. The goal is to understand Netflix’s content strategy using data visualization and statistical analysis.

📊 Dataset Information

Dataset Name: Netflix Movies and TV Shows

Source: Kaggle

Records: ~8,800

Features:

show_id

type (Movie / TV Show)

title

director

cast

country

date_added

release_year

rating

duration

listed_in (genre)

description

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔍 Exploratory Data Analysis Steps
1️⃣ Data Loading & Understanding

Loaded dataset using Pandas

Inspected data structure using head(), info(), and describe()

2️⃣ Data Cleaning

Identified missing values

Handled null entries in columns like director, country, and cast

Removed duplicates if present

3️⃣ Data Visualization

Movies vs TV Shows distribution

Content release trend by year

Top genres on Netflix

Country-wise content distribution

4️⃣ Insights Generation

Identified dominant content types and genres

Analyzed Netflix’s growth over the years

Observed country-level contribution patterns

📈 Key Insights

Netflix has more Movies than TV Shows

Content production increased significantly after 2015

Drama is the most common genre

United States contributes the highest number of titles

India is among the top content-producing countries

📂 Project Structure
netflix_data_analysis/
│── Data/
│   └── netflix_titles.csv
│── netflix_eda.ipynb
│── README.md
│── requirements.txt

▶️ How to Run the Project

Clone the repository

git clone https://github.com/vrajrupareliya/netflix_data_analysis.git


Navigate to the project directory

cd netflix_data_analysis


Install required libraries

pip install -r requirements.txt


Open the notebook

jupyter notebook netflix_eda.ipynb

🎯 Use Cases

Understanding streaming platform content trends

Business decision-making using data insights

Beginner-friendly data science project

Portfolio project for placements and internships

📄 Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can be used to gain meaningful insights from real-world datasets. Through visualization and statistical analysis, we better understand Netflix’s content distribution and growth strategy.

👤 Author

Rokkam Karthikeye Reddy
(Data Science / Machine Learning Enthusiast)
