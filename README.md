# Sherly's Portfolio
A portfolio showcasing projects in Data Analytics &amp; Data Science, including data cleaning, EDA, statistical analysis, predictive modeling, and dashboards. Topics include e-commerce, and stock price prediction forecasting using Python, Excel, and Power BI.

# [Project 1: Stock Price Prediction for BIRD.JK](https://github.com/sherly07yulianty/Stock-Price-Modeling)

This project analyzes and predicts the stock price of **BIRD.JK** using two models: **Markov Switching Autoregressive (MS-AR)** and **Prophet**.

| Model  | MAPE |
|--------|-------|
| MS-AR  | 4.6%  |
| Prophet| 3.29% |

---

## Key Features
- Data cleaning & preprocessing  
- Time series forecasting  
- Comparative analysis of two models  
- Visualization of actual vs predicted prices  

---

### Methodology
1. Data: Historical stock prices of BIRD.JK  
2. Models: MS-AR & Prophet  
3. Metric: Mean Absolute Percentage Error (MAPE)  

---

### Prediction Plots
![MS-AR Prediction](https://github.com/sherly07yulianty/Stock-Price-Modeling/blob/main/prediksi_harga_saham_dengan_state_mape4.6.png)
![Prophet Prediction](https://github.com/sherly07yulianty/Stock-Price-Modeling/blob/main/prediksi_harga_saham_error_baru2.png)

---

### Insights
Prophet model outperformed MS-AR in this dataset, achieving lower error.  
These results may support **investors in making stock-buying decisions**.

---

### Highlight
The Prophet model achieved **==3.29% MAPE==**, making it more accurate for this stock.


# [Project 2: Diabetes Prediction using KNN, Random Forest, and Decision Tree](https://github.com/sherly07yulianty/Classification-Model/tree/main)

Diabetes is a disease with a rising number of cases, causing **1.5 million deaths globally in 2019**.  
This project compares three classification methods: **K-Nearest Neighbor (KNN)**, **Random Forest**, and **Decision Tree**  
for diabetes prediction using the following features:

- Pregnancies  
- Glucose  
- Insulin  
- Body Mass Index (BMI)  
- Age  

Target variable: **Outcome**

---

## Key Highlights

- Without Min-Max normalization:  
  - **Decision Tree** achieved the highest accuracy (79.35%)  
  - **KNN** had the fastest computation time (1.57 s)  

- With Min-Max normalization:  
  - **KNN** accuracy improved (77.53%) and remained the fastest (1.53 s)  
  - **Decision Tree** and **Random Forest** accuracy decreased  

==Min-Max normalization is most beneficial when applied with KNN==.

---

## Model Evaluation

### Before Min-Max Normalization
| Model          | Accuracy  | Computation Time (s) |
| -------------- | --------- | -------------------- |
| KNN            | 74.07%    | 1.5739               |
| Random Forest  | 78.01%    | 4.7255               |
| Decision Tree  | **79.35%**| 3.4833               |

### After Min-Max Normalization
| Model          | Accuracy  | Computation Time (s) |
| -------------- | --------- | -------------------- |
| KNN            | **77.53%**| 1.5288               |
| Random Forest  | 75.46%    | 4.6285               |
| Decision Tree  | 73.71%    | 3.2686               |

---

## Conclusion

KNN benefits significantly from Min-Max normalization,  
while Decision Tree performs better without it.  
These findings can guide future implementations of diabetes prediction systems.

---

© 2025 Sherly Yulianty – Data Analytics & Data Science Portfolio


