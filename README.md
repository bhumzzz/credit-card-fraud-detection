Credit Card Fraud Detection

Project Overview
This project uses Machine Learning to detect fraudulent credit card transactions. The primary challenge was the extreme class imbalance (fraudulent transactions are rare), which I addressed using **SMOTE** and **LightGBM**.

Tech Stack
- Language: Python
- Modeling: LightGBM, Scikit-learn
- Data Handling: Pandas, NumPy, SMOTE (for class imbalance)
- Deployment: Streamlit (via `app.py`)

 Key Results
- Recall:92% (Priority for fraud detection to minimize missed cases)
- Accuracy: 99.8%
- Feature Engineering: Included geographical distance calculations and transaction frequency analysis.

 How to Run
1. Clone the repo: `git clone https://github.com/bhumzzz/credit-card-fraud-detection.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `streamlit run app.py`
