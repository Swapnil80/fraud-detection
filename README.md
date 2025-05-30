
# 🛡️ Fraud Detection using Machine Learning

This project aims to build a machine learning model that detects fraudulent bank transactions based on structured data. It includes exploratory data analysis, data preprocessing, model training, and evaluation.

## 📊 Dataset

The dataset used in this project was sourced from Kaggle:  
**[Bank Transactions Fraud Detection Dataset](https://www.kaggle.com/datasets)**  
(https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection)

> ⚠️ Due to licensing restrictions, the dataset is not included in this repository.  
> To run the notebook, download the dataset manually from Kaggle and place it in the root directory as `bank_transactions_data_2.csv`.

## 🧠 Features and Workflow

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Handling imbalanced data (e.g., fraud class imbalance)
- Training and evaluation of classification models:
  - Logistic Regression
  - Random Forest
- Accuracy, precision, recall, and F1-score analysis
- Optional: ROC-AUC curve, confusion matrix, etc.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it as:
   ```
   ./bank_transactions_data_2.csv
   ```

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook fraud_detection.ipynb
   ```

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib
- seaborn

You can create a `requirements.txt` using:
```bash
pip freeze > requirements.txt
```

## 📈 Sample Output (Screenshots)

Include visualizations like confusion matrix, feature importance, or ROC curve here if you want.

## 📂 Project Structure

```
fraud-detection/
├── fraud_detection.ipynb        # Jupyter notebook with full analysis
├── bank_transactions_data_2.csv # <Ignored in .gitignore, downloaded manually>
├── README.md                    # Project overview
└── requirements.txt             # Python dependencies
```

## 👨‍💻 Author

**Swapnil Kadam**  
MSc Advanced Computer Science | AI & Machine Learning  
📫 [swapnil8kadam@gmail.com](mailto:swapnil8kadam@gmail.com)

---

## ⭐ Acknowledgments

- [Kaggle](https://www.kaggle.com/) for providing the dataset
- scikit-learn for ML models
- matplotlib & seaborn for visualizations

---
