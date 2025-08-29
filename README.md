# Fraud Detection using Exploratory Data Analysis (EDA)

This project applies **Exploratory Data Analysis (EDA)** techniques to a fraud detection dataset to uncover hidden trends, imbalances, and anomalies in transactions.

---

## Project Overview
Fraudulent transactions are a critical problem in the financial sector. The objective of this project is to:
1. Explore and understand dataset structure.  
2. Detect anomalies and class imbalance in transaction types.  
3. Visualize patterns and relationships between features.  
4. Provide insights that can guide machine learning model development.

---

## Repository Structure
- `01_eda.ipynb` → Jupyter Notebook with step-by-step analysis.  
- `requirements.txt` → Python libraries used.  
- `README.md` → Documentation of the project.  


---

##  Dataset
The dataset (`Fraud.csv`) is ~470 MB, too large for GitHub.  

You can download it here:  
[📥 Download Fraud.csv](https://drive.google.com/file/d/1JUvAV1qMO_3rwppHNgJunhgblJpyJ72P/view?usp=sharing)

> Place the dataset inside a `data/` folder before running the notebook.

---

## Tools & Libraries
- **Python** (3.8+)  
- **Pandas** – data manipulation  
- **NumPy** – numerical operations  
- **Matplotlib / Seaborn** – data visualization  
- **Jupyter Notebook** – analysis environment  

## 📸 Project Visuals

### 1. Transaction Distribution
![Transaction Distribution]

<img width="600" height="400" alt="fraud_vs_normal" src="https://github.com/user-attachments/assets/8fe942f1-b181-4b53-a0c9-b961a9c9abad" />
  
*Shows the imbalance between normal and fraud transactions.*

### 2. Correlation Heatmap
![Correlation Heatmap]

<img width="500" height="400" alt="Confusion_matrix" src="https://github.com/user-attachments/assets/64df65ac-ecd1-4c92-a094-f9ccac610fbe" />

*Highlights relationships between numerical features.*

### 3. Transaction Amount Distribution
![Ammount Distribution]

<img width="600" height="400" alt="fraud_rate_by_transaction" src="https://github.com/user-attachments/assets/045c39d6-9826-4474-bf83-03de04ae8e61" />

*Displays the distribution of transaction amounts.*

