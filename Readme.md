# Global Human Trafficking Analysis Project

> This project, born from the intense collaborative energy of Datathon—a hackathon proudly hosted by the Data Science Club at VIT-AP University—embarks on a crucial mission: to delve deep into the intricate web of global human trafficking vulnerability data, ultimately forging a path toward meaningful insights and powerful predictions.

## Overview
This project isn't just about numbers, it's a journey into the heart of global human trafficking vulnerability. We meticulously dissect this sensitive data, not only to pinpoint the subtle risk factors at play and forecast potential vulnerability hotspots, but also to craft compelling, interactive visualizations that bring these complex issues to life. Our core endeavor is to illuminate the intricate patterns of human trafficking across diverse nations and regions, all while harnessing the power of machine learning to anticipate and ultimately, help mitigate future risks.

## Project Structure
```
Datathon/
├── data/                 # Data files and cleaning scripts
│   ├── data.xlsx        # Raw data
│   ├── cleaned_data.csv # Processed dataset
│   └── data_clean.ipynb # Data cleaning notebook
├── src/
│   ├── Global Human Trafficking Vulnerability Map/
│   │   └── interactive_map.ipynb    # Interactive choropleth map
│   └── risk prediction/
│       └── risk_prediction.ipynb    # ML model for risk prediction
├── requirements.txt      # Project dependencies
└── README.md
```

## Key Features

### 1. Interactive Global Vulnerability Map
![Vulnerability Map](src/Global%20Human%20Trafficking%20Vulnerability%20Map/vulnerability_map.png)
- Interactive choropleth map showing trafficking vulnerability scores worldwide
- Country-specific detailed statistics
- Color-coded risk levels

### 2. Risk Factor Analysis
![Correlation Heatmap](src/risk%20prediction/correlation_heatmap.png)
- Analysis of key risk factors
- Correlation studies between different variables
- Feature importance visualization

### 3. Predictive Modeling
![Feature Importance](src/risk%20prediction/feature_importance.png)
- Random Forest Classification model
- Prediction of vulnerability scores
- Feature importance analysis

## Setup Instructions
1. Clone the repository
2. Create and activate virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
### Data Cleaning
- Run `data/data_clean.ipynb` to process raw data
- Outputs cleaned dataset to `data/cleaned_data.csv`

### Visualization
- Execute `src/Global Human Trafficking Vulnerability Map/interactive_map.ipynb` for interactive map
- View `src/risk prediction/risk_prediction.ipynb` for statistical analysis

## Data Sources
- Global Slavery Index 2023
- Features include:
  - Government response metrics
  - Risk factors
  - Modern slavery estimates
  - Conflict effects
  - Vulnerability scores

## Technologies Used
- Python 3.12
- Pandas & NumPy for data processing
- Plotly for interactive visualizations
- Scikit-learn for machine learning
- Seaborn & Matplotlib for statistical plots

## License
This project is licensed under the MIT License - see the LICENSE file for details.
