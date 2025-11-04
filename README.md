# Grocery Sales Forecasting - Streamlit App

##  Corporación Favorita Sales Forecasting

Interactive forecasting application for Guayaquil stores.

##  Quick Start

### Local Deployment

1. Install requirements:
```bash
pip install -r requirements.txt
```

2. Run the app:
```bash
streamlit run app.py
```

3. Open browser to: http://localhost:8501

##  Project Structure
```
streamlit_app/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── data/              # Data files
│   ├── model_registry.json
│   └── forecast_*.csv
└── models/            # Trained models
    ├── lgb_*.pkl
    └── config_*.json
```

##  Features

- **Interactive Forecasting**: Select store and product family
- **Customizable Horizon**: Choose forecast length (7-90 days)
- **Visualizations**: Line charts and weekly aggregations
- **Statistics**: Detailed forecast statistics
- **Export**: Download forecasts as CSV

##  Data

- **Forecast Period**: January - March 2014
- **Location**: Guayaquil, Guayas Province, Ecuador
- **Model**: LightGBM with engineered features

##  Model Performance

Best model: LightGBM
- MAE: ~750-1000 (varies by store-family)
- Incorporates: holidays, paydays, promotions, oil prices

##  Support

For questions or issues, refer to the main project documentation.

---

Built with ❤️ for demand planners in Guayaquil
"""
