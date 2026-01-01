# 🚀 New Year Resolution Predictor (ML)

Predict whether someone will keep their New Year resolution using simple lifestyle habits like sleep, study, exercise, and screen time.

## 🔍 Project Overview

This project uses an XGBoost classifier trained on a synthetic lifestyle dataset:

- `sleep_hours`
- `study_hours`
- `exercise_days`
- `screen_time`
- `kept_resolution` (target: 0 = No, 1 = Yes)

The notebook includes:
- Data loading and exploration  
- Visualizations (counts, boxplots, heatmap)  
- Model training and accuracy evaluation  
- A simple "plug your own habits" prediction cell  

## 📂 Structure

- `notebooks/New_Year_Resolution_Predictor.ipynb` – full Colab/Jupyter workflow  
- `data/resolutions.csv` – dataset used for training  
- `src/train_model.py` – minimal script to train and test the model  
- `requirements.txt` – Python dependencies  

## ⚙️ Setup

```bash
git clone https://github.com/<your-username>/New-Year-Resolution-Predictor-ML.git
cd New-Year-Resolution-Predictor-ML
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
