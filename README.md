# **Cyberbullying Detection Benchmark: Classical vs Transformer Models**

## **Overview**

This repository contains a **comprehensive benchmark study** comparing classical machine learning models and transformer-based models for detecting cyberbullying in tweets. 

**Dataset Source / Credit:**  
This dataset was obtained from [Kaggle: Cyberbullying Classification](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification/data)  
---

## **Repository Structure**

| Folder                                   | Description                                                                                                                                      |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| `01_data_cleaning`                       | Scripts and notebooks for **data preprocessing and cleaning** of the tweet datasets.                                                             |
| `02_exploratory_data_analysis`           | Exploratory analysis to **understand dataset characteristics and patterns**.                                                                     |
| `03_classical_models`                    | Implementation and evaluation of **classical ML models** (Logistic Regression, SVM, Naive Bayes, Random Forest).                           |
| `04_transformer_models`                  | Implementation and evaluation of **transformer models** (BERT-base, DistilBERT, RoBERTa).                                                  |
| `05_Classical_vs_Transformers_Benchmark` | **Final benchmark analysis** comparing classical and transformer models, including **visualizations, metric rankings, and actionable insights**. |

---

## **Usage**

* Run notebooks in **sequence (01 → 05)** to reproduce the benchmark study.
* Explore visualizations, metric tables, and **trade-off analyses** in the final benchmark notebook (`05_Classical_vs_Transformers_Benchmark`).
* Compare models using **F1, Precision, Recall**, and **weighted scores**.

---

## **Results**

* **Transformers** (e.g., BERT-base, RoBERTa) outperform classical models in **accuracy (up to 0.866)** and **recall-macro (up to 0.856)**.
* **Classical models** (e.g., SVM) achieve decent performance (**accuracy \~0.835**) but generally lag behind transformers.
* The final notebook provides **metric-driven insights, rankings, and recommendations** for model selection in real-world applications.

---

## **Contributing**

Feel free to:

* **Fork** the repository
* **Submit issues**
* **Create pull requests** to improve code, visualizations, or documentation

