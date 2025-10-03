# Cancer-Subset-Predictor

This project aims to develop a machine learning pipeline for predicting cancer subtypes based on gene expression data in the form of an RNAseq counts matrix. It includes [data preprocessing](https://github.com/StevenN2021/Cancer-Subset-Predictor/blob/main/notebooks/preprocess.ipynb), [exploratory data analysis](https://github.com/StevenN2021/Cancer-Subset-Predictor/blob/main/notebooks/eda.ipynb#:~:text=eda.-,ipynb,-preprocess.ipynb), and [model training + evaluation](https://github.com/StevenN2021/Cancer-Subset-Predictor/tree/main/notebooks#:~:text=2%20minutes%20ago-,model_train.ipynb,-model%20trained%20%2B%20eval) using the random forest classifier. 

## Data information 

### **Data Source** 
- **Dataset**: gene expression cancer RNA-Seq
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/)

### **Dataset Statistics**
| Metric | Value | Description |
|--------|-------|-------------|
| **Cancer Types** | 5 | Different cancer subtypes |
| **Training Examples** | 801 | 801 sequenced samples |
| **Test Set Size** | 20% | Stratified split |

### **Cancer Type Distribution**
| Cancer Type | # of Examples | Percentage |
|-------------|------------|------------|
| BCRA (Breast Invasive Carcinoma) | 300 | 37% |
| COAD (Colon adenocarcinoma) | 78 | 9% |
| KIRC (Kidney Renal Clear Cell Carcinoma ) | 146 | 18% |
| LUAD (Lung Adenocarcinoma) | 141 | 17% |
| PRAD (Prostrate Adenocarcinoma) | 136 | 16% 

