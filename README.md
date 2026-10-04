# Transformational AI: Analyzing Ecommerce Large Datasets for Machine Learning

Author: Dennis O'Higgins

This repository contains my Udacity PCEP project notebook. It streams a 100-item sample from the Hugging Face Amazon Reviews 2023 Electronics datasets (reviews and product metadata), analyses them with pandas, visualises them with seaborn and matplotlib, and exports a cleaned set of top-rated products to CSV and Parquet.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dohigg1987/transformational-ai-amazon-reviews/blob/main/transformational_ai_project.ipynb)

Open in Colab: https://colab.research.google.com/github/dohigg1987/transformational-ai-amazon-reviews/blob/main/transformational_ai_project.ipynb

## Contents

- `transformational_ai_project.ipynb`: the project notebook
- - `top_products.csv`: cleaned top-rated products (title, average rating, price)
  - - `top_products.parquet`: the same data in Parquet format
    - - `user_inputs.txt`: written answers to the seven reflection questions
     
      - ## How to run
     
      - Open the notebook in Google Colab using the link above and choose Runtime, then Run all. No API key is needed. The first code cell pins `datasets<4.0.0`, which is required for the dataset's loading script to work.
      - 
