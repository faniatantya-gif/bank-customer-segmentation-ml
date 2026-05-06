# Bank Customer Segmentation & Classification

## Project Overview
Project ini bertujuan untuk melakukan segmentasi nasabah bank dan membangun model klasifikasi untuk memprediksi kategori nasabah baru berdasarkan pola transaksi dan karakteristik pengguna.

## Objectives
- Mengelompokkan nasabah berdasarkan karakteristik transaksi menggunakan K-Means Clustering
- Membangun model klasifikasi untuk prediksi kategori nasabah
- Memberikan insight bisnis dan rekomendasi strategi pemasaran

## Dataset
Dataset terdiri dari ±2.500 data transaksi nasabah bank dengan berbagai fitur seperti:
- Transaction Amount
- Account Balance
- Customer Age
- Transaction Duration
- Customer Occupation
- Channel
- Location

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Machine Learning Workflow
1. Data Cleaning & Preprocessing
2. Feature Encoding & Scaling
3. Customer Segmentation using K-Means
4. Model Training using:
   - Decision Tree
   - Random Forest
5. Hyperparameter Tuning using GridSearchCV
6. Model Evaluation

## Results
- Successfully segmented customers into 2 main clusters
- Achieved model accuracy up to 100%
- Generated business recommendations based on customer behavior patterns

## Project Structure
```text
notebook/     -> Jupyter notebooks
dataset/      -> Dataset files
model/        -> Saved machine learning models
