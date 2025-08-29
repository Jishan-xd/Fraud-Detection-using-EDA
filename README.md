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
- `images/` → Visualizations and charts generated during EDA.  

---

##  Dataset
The dataset (`Fraud.csv`) is ~470 MB, too large for GitHub.  

You can download it here:  
[📥 Download Fraud.csv](YOUR_DATASET_LINK_HERE)

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
![Transaction Distribution](<img width="600" height="400" alt="fraud_vs_normal" src="https://github.com/user-attachments/assets/3a0c3410-dc21-4c7e-8716-b5ac1157a7b0" />)
  
*Shows the imbalance between normal and fraud transactions.*

### 2. Correlation Heatmap
![Correlation Heatmap]()  
*Highlights relationsh<img width="500" height="400" alt="Confusion_matrix" src="https://github.com/user-attachments/assets/755f4fe8-10c4-47ca-a11e-b8a7f85f6f10" />
ips between numerical features.*

### 3. Transaction Amount Distribution
<img width="600" height="400" alt="fraud_rate_by_transaction" src="https://github.com/user-attachments/assets/586b02c8-4435-468c-ba26-fe8ca0315c54" />

![Amount Distribution] 
*Displays the distribution of transaction amounts.*

