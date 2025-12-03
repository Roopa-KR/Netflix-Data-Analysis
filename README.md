📊 Netflix Movie Data Analysis

A Data Science Project using Python & Jupyter Notebook

📌 Problem Statement

Netflix heavily relies on data science, AI, and machine learning to understand customer behavior and create strong recommendation systems.
As a data analyst, you are given a dataset containing 9,000+ Netflix movies, and your job is to extract meaningful insights that support informed business decisions.

This project analyzes the dataset across genres, popularity, votes, and release trends.

📁 Dataset Overview

Your dataset contains the following columns:

Column Name	Description
Release_Date	Date when the movie was released
Title	Movie title
Overview	Summary/description of the movie
Popularity	Popularity score (numeric)
Vote_Count	Number of votes received
Vote_Average	Average rating given by viewers
Original_Language	Language in which the movie was originally made

Note: Genre is not present in your dataset, but can be extracted/engineered if you have an additional dataset or API.
If not, questions related to genre will be adjusted based on available data.

🎯 Objectives / Questions to Solve

Using the provided dataset, you must answer the following key questions:

Which movie has the highest vote average (Vote_Average)?

Which movie has the highest popularity (Popularity)?

Which movie has the lowest popularity?

Which year has the most filmed/released movies?
→ Requires extracting the year from the Release_Date column.

(Optional if you add genre) What is the most common movie genre on Netflix?

🛠️ Tools & Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib / Seaborn

(Optional) Plotly

📘 Project Structure
├── README.md                     # Documentation
├── netflix_analysis.ipynb        # Python notebook with analysis & visualizations
└── dataset/
      └── netflix_movies.csv      # Your dataset (example filename)

🚀 How to Run This Project

Clone the repository

Install dependencies

pip install -r requirements.txt


Launch the notebook:

jupyter notebook netflix_analysis.ipynb


Run the cells to generate insights and plots.