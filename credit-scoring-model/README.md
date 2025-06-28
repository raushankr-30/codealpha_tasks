# Credit Risk Prediction with the German Credit Dataset

This repository presents a complete, end‑to‑end workflow for building, evaluating and optionally deploying a binary classification model that predicts the credit risk of loan applicants. The project uses the canonical **Statlog (German Credit Data)** set from the UCI Machine‑Learning Repository.

---

## Project Overview
Financial institutions routinely assess the probability that a borrower will default on a loan.  
This project demonstrates:

* **Data ingestion and cleaning** for the German Credit dataset  
* **Exploratory data analysis** to understand class balance and key feature distributions  
* **Pre‑processing** (one‑hot encoding of categorical variables and feature scaling)  
* **Baseline modelling** with Logistic Regression  
* **Ensemble modelling** with Random Forests  
* **Performance evaluation** using accuracy, precision, recall, F1‑score and confusion matrix  
* **Feature importance analysis** to interpret model drivers  
* **Optional deployment** via a lightweight Streamlit web interface  

Everything is contained in a single, well‑commented Jupyter notebook for clarity and ease of review.

---

## Dataset
| Source | UCI Machine Learning Repository – Statlog (German Credit Data) |
| ------ | ---------------------------------------------------------------- |
| Records | 1 000 |
| Features | 20 customer attributes |
| Target | `credit_risk` (1 = good credit, 2 = bad credit) |

During pre‑processing the original `credit_risk` column is mapped to a binary label `Risk`  
(`0` = good, `1` = bad).

---
