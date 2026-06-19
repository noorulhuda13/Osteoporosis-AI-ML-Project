📋 Overview

OsteoScan PRO is a machine learning system that predicts osteoporosis risk using patient clinical data. Features include a Random Forest + Gradient Boosting ensemble, interactive Gradio web interface, and real-time risk assessment with visualizations.

📊 Performance

Metric	Value
Accuracy	83.67%
Precision	85.82%
Recall	83.67%
F1-Score	83.42%
5-Fold CV	85.39% ± 1.63%
🏥 Problem

Traditional DEXA scans are expensive and not scalable. This model predicts osteoporosis risk using routine, non-invasive patient data.

📁 Dataset

1,958 patient records
15 clinical features
Target: Osteoporosis (Yes/No)
🚀 Installation

bash
git clone https://github.com/yourusername/osteoscan-pro.git
cd osteoscan-pro
pip install -r requirements.txt
python app.py
💻 Input Parameters

Age, Gender, Race/Ethnicity
Hormonal Status, Family History
Calcium & Vitamin D Intake
Physical Activity, Smoking
Body Weight, Alcohol
Medical Conditions, Medications
Prior Fractures
📈 Top Risk Factors

Hormonal Changes (0.184)
Prior Fractures (0.163)
Age (0.152)
Calcium Intake (0.119)
Vitamin D Intake (0.099)
📊 Visualizations

Risk factor contributions
Population risk comparison
10-year bone density trajectory
Multi-dimensional risk radar
Detailed risk breakdown
Confusion matrix & feature importance
👥 Authors

Minahil Fawad (FA23-BCE-048)
Noor-ul-Huda (FA23-BCE-082)
