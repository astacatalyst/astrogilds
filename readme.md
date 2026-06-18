# 🚀 Space Radiation Prediction and Risk Assessment System

## 🌌 Overview

Space missions operating in Earth orbit are exposed to hazardous radiation environments, primarily caused by trapped energetic particles within the Van Allen Radiation Belts. This project develops an AI-powered radiation prediction and risk assessment system that forecasts radiation intensity and identifies hazardous orbital regions using space weather and satellite data.

---

## 🎯 Problem Statement

Develop a system capable of:

- Predicting radiation levels in near-Earth space.
- Assessing mission risk due to radiation exposure.
- Providing radiation heatmaps and risk zones.
- Supporting spacecraft mission planning and safety.

---

## 🔬 Background

The Earth's magnetosphere traps energetic charged particles, forming the Van Allen Radiation Belts.

### Inner Belt
- High-energy protons
- ~1,000 km – 12,000 km altitude

### Outer Belt
- High-energy electrons
- ~13,000 km – 60,000 km altitude

Radiation levels change due to:

- Solar flares
- Coronal Mass Ejections (CMEs)
- Geomagnetic storms
- Space weather disturbances

---

## 💡 Proposed Solution

Our solution combines Space Physics and Artificial Intelligence to predict radiation intensity and classify mission risks.

### Key Components

1. Data Acquisition
2. Data Preprocessing
3. Feature Engineering
4. Radiation Prediction Model
5. Risk Assessment Engine
6. Visualization Dashboard

---

## 🏗️ System Architecture

```text
Space Weather Data
        │
        ▼
 Data Collection
        │
        ▼
 Data Processing
        │
        ▼
 Feature Engineering
        │
        ▼
 AI Prediction Model
        │
        ▼
 Radiation Forecast
        │
        ▼
 Risk Assessment
        │
        ▼
 Visualization Dashboard

 space-radiation-prediction/

---

##📂 Project Structure


│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   ├── data_exploration.ipynb
│   ├── feature_engineering.ipynb
│   └── model_training.ipynb
│
├── src/
│   ├── data_collection/
│   │   └── collect_data.py
│   │
│   ├── preprocessing/
│   │   └── preprocess.py
│   │
│   ├── feature_engineering/
│   │   └── feature_builder.py
│   │
│   ├── models/
│   │   ├── train.py
│   │   ├── predict.py
│   │   └── evaluate.py
│   │
│   ├── risk_assessment/
│   │   └── risk_classifier.py
│   │
│   └── visualization/
│       └── radiation_maps.py
│
├── dashboard/
│   └── app.py
│
├── models/
│   ├── saved_models/
│   └── checkpoints/
│
├── results/
│   ├── plots/
│   ├── reports/
│   └── predictions/
│
├── docs/
│   ├── architecture.md
│   ├── methodology.md
│   └── references.md
│
├── requirements.txt
├── README.md
└── LICENSE