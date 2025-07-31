🏦 Loan Risk Categorization - MLOps Project
📌 Overview
A machine learning project to classify loan applicants into Low, Medium, or High risk categories using XGBoost. It features a clean Streamlit UI, automated data processing, and modular design built with MLOps best practices.

🚀 Features
✅ Automated data preprocessing & encoding

✅ XGBoost model training and evaluation

✅ Single & batch prediction support via UI

✅ Logging for monitoring and debugging

✅ Ready for CI/CD and cloud deployment

📁 Structure
MLOPS_LAST
├── Scripts/             # All core Python scripts
├── Data/                # Raw, processed, and output files
├── Artifacts/           # Trained model & pipeline objects
├── Logs/                # Runtime logs
├── requirements.txt     # Python dependencies
└── README.md

🛠️ How to Run
# Setup
git clone https://github.com/yourusername/loan-risk-mlops.git
cd loan-risk-mlops
python -m venv venv && source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt

# Train model
python Scripts/main.py

# Launch UI
streamlit run Scripts/app.py

👤 Author
Lavanya – https://github.com/Lavanya-hue/MLOPS_LAST
📄 Licensed under MIT License
