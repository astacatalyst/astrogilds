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
│
├── data/
│   ├── raw/              # Raw data from external sources
│   ├── processed/        # Cleaned and processed data
│   └── external/         # External reference data
│
├── notebooks/
│   ├── data_exploration.ipynb      # EDA and data analysis
│   ├── feature_engineering.ipynb    # Feature creation and transformation
│   └── model_training.ipynb         # Model training and evaluation
│
├── src/
│   ├── data_collection/
│   │   └── collect_data.py          # Data collection module
│   │
│   ├── preprocessing/
│   │   └── preprocess.py            # Data preprocessing and cleaning
│   │
│   ├── feature_engineering/
│   │   └── feature_builder.py       # Feature engineering functions
│   │
│   ├── models/
│   │   ├── train.py                 # Model training pipeline
│   │   ├── predict.py               # Prediction module
│   │   └── evaluate.py              # Model evaluation metrics
│   │
│   ├── risk_assessment/
│   │   └── risk_classifier.py       # Risk classification module
│   │
│   └── visualization/
│       └── radiation_maps.py        # Visualization and mapping functions
│
├── dashboard/
│   └── app.py                       # Interactive web dashboard
│
├── models/
│   ├── saved_models/                # Trained model files
│   └── checkpoints/                 # Model training checkpoints
│
├── results/
│   ├── plots/                       # Generated visualizations
│   ├── reports/                     # Analysis reports
│   └── predictions/                 # Prediction outputs
│
├── docs/
│   ├── architecture.md              # System architecture documentation
│   ├── methodology.md               # Methodology and approach
│   └── references.md                # References and resources
│
├── requirements.txt                 # Python dependencies
├── README.md                        # This file
└── LICENSE                          # License information
```

---

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd space-radiation-prediction
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 Quick Start

### 1. Data Exploration
Start with exploratory data analysis:
```bash
jupyter notebook notebooks/data_exploration.ipynb
```

### 2. Feature Engineering
Create and engineer features:
```bash
jupyter notebook notebooks/feature_engineering.ipynb
```

### 3. Model Training
Train the prediction model:
```bash
jupyter notebook notebooks/model_training.ipynb
```

### 4. Run the Dashboard
Launch the interactive web interface:
```bash
python dashboard/app.py
```

---

## 💻 Usage Examples

### Collect Data
```python
from src.data_collection.collect_data import collect_data
data = collect_data()
```

### Preprocess Data
```python
from src.preprocessing.preprocess import preprocess_data
processed_data = preprocess_data(data)
```

### Build Features
```python
from src.feature_engineering.feature_builder import build_features
features = build_features(processed_data)
```

### Train Model
```python
from src.models.train import train_model
model = train_model(features, labels)
```

### Make Predictions
```python
from src.models.predict import make_prediction
predictions = make_prediction(model, new_data)
```

### Assess Risk
```python
from src.risk_assessment.risk_classifier import classify_risk
risk_level = classify_risk(predictions)
```

---

## 🎓 Dependencies

- numpy >= 1.21.0
- pandas >= 1.3.0
- scikit-learn >= 1.0.0
- matplotlib >= 3.4.0
- seaborn >= 0.11.0
- jupyter >= 1.0.0
- plotly >= 5.0.0
- flask >= 2.0.0
- tensorflow >= 2.7.0

See `requirements.txt` for complete dependencies.

---

## 📚 Documentation

- **[System Architecture](docs/architecture.md)**: Detailed system design and components
- **[Methodology](docs/methodology.md)**: Approach, algorithms, and techniques
- **[References](docs/references.md)**: Related papers and external resources

---

## 📁 Key Directories

| Directory | Purpose |
|-----------|---------|
| `data/` | All project data (raw, processed, external) |
| `notebooks/` | Jupyter notebooks for exploration and analysis |
| `src/` | Main source code modules |
| `models/` | Trained models and checkpoints |
| `results/` | Output plots, reports, and predictions |
| `docs/` | Documentation files |

---

## 🤝 Contributing

Instructions for contributing will be added here.

---

## 📄 License

See the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For questions or inquiries, please contact the project maintainers.
