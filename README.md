# AMD_MBApro - Market-Basket Analysis — IMDB

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1whxQ1dm4G2neBsotM4gt_pNz89dIWuzl?usp=sharing)

Project for **Algorithms for Massive Data** (MSc Data Science for Economics, Università degli Studi di Milano).

Each movie of the [IMDB Top-1000 dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows) is treated as a *basket* and its four leading actors (`Star1`–`Star4`) as *items*. The notebook finds **frequent itemsets** of co-starring actors and the **association rules** (confidence, lift) between them, implementing three algorithms from scratch: **Apriori**, **PCY**, and **SON** (the latter on Apache Spark for scalability).

## How to run

1. Open the notebook in Colab via the badge above.
2. Replace the `"xxxxxx"` placeholders with your own [Kaggle API](https://github.com/Kaggle/kaggle-api) username and key.
3. `Runtime → Run all` (the first cells install Java + Spark and download the dataset).

## Contents

- `Market_Basket_Analysis_IMDB.ipynb` — code (Apriori, PCY, SON, association rules, scalability test).
- `Report_Market_Basket_Analysis.pdf` — project report.

## Author

Matteo Hasa — 56269A
