# Credit_card_fruad_detection
# Credit Card Fraud Detection


## Setup


1. Create virtual env and install requirements


python -m venv venv
source venv/bin/activate # or venv\Scripts\activate on Windows
pip install -r requirements.txt


2. Download dataset:
- Use the Kaggle "Credit Card Fraud" dataset (284,807 rows). Save as `data/creditcard.csv`.
- Kaggle link: https://www.kaggle.com/mlg-ulb/creditcardfraud


3. Train models


cd models
python train.py --data ../data/creditcard.csv


This will create `saved_models/best_model.joblib` and csv reports in `saved_models/`.


4. Run the Flask app


cd ..
python app.py


5. Open http://localhost:5000 in your browser. Use the same number and order of features used during training.


## No
