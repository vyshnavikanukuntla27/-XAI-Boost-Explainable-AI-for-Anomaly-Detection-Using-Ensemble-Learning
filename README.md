🌐 Network Anomaly Detection
Machine Learning for Cybersecurity Threat Detection

📌 Overview
This project detects malicious network activities using:

Supervised Learning: Random Forest (98% accuracy)

Unsupervised Learning: Isolation Forest (for novel attacks)

Explainability: SHAP for model transparency

Dataset: KDD Cup 99

🚀 Features
Dual-model approach for comprehensive threat detection

SHAP visualizations (Beeswarm, Waterfall plots)

End-to-end pipeline: Preprocessing → Training → Evaluation

Optimized for recall (minimizes false negatives)

🛠️ Tech Stack
Python 3.8+

scikit-learn, SHAP, pandas, matplotlib

📂 Repository Structure
Copy
├── data/                    # Preprocessed datasets  
├── notebooks/               # Jupyter notebooks  
│   ├── 1_data_preprocessing.ipynb  
│   ├── 2_model_training.ipynb  
│   └── 3_shap_analysis.ipynb  
├── models/                  # Saved models (.h5, .pkl)  
├── utils/                   # Helper scripts  
├── README.md  
└── requirements.txt  
⚡ Quick Start
Install dependencies:

bash
Copy
pip install -r requirements.txt
Run Jupyter notebooks:

bash
Copy
jupyter notebook notebooks/
📊 Results
Model	Accuracy	Precision	Recall
Random Forest	98.2%	97.8%	98.5%
Isolation Forest	92.1%	89.3%	94.2%
SHAP Beeswarm Plot

📜 License
MIT License - See LICENSE

🔗 Connect:
GitHub
Open in Colab

🎯 Why This Project?
Real-world cybersecurity application

Explainable AI for security analysts

Modular code adaptable to other datasets
