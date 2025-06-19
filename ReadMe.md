# Retail Demand Forecast
This project develops a comprehensive sales forecasting system for Corporación Favorita grocery stores in Ecuador's Guayas region. Using historical sales data and multiple machine learning approaches, accurate sales predictions are made  to optimize inventory management, prevent stockouts, and improve promotional strategies.


## 🎯 Project Overview

This project implements end-to-end retail demand forecasting using various time series models and machine learning algorithms. It includes data preprocessing, exploratory data analysis, model training and evaluation, experiment tracking, and an interactive Streamlit web application for visualization.

## 📁 Project Structure

```
Retail_Demand_Forecast/
│
├── data/                    # Raw and processed datasets (not tracked in git)
├── notebooks/               # Jupyter notebooks for EDA, modeling, and experiments
├── src/                     # Source code for data processing and modeling
├── Forecasting_app/         # Streamlit app for interactive forecasting
│   ├── app.py
│   └── forecasts/
├── mlflow_results/          # MLflow experiment tracking results (ignored in git)
├── Data_Kaggel_&_Guayas/   # External data sources (ignored in git)
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
└── .gitignore
```

## ✨ Key Features

- **Data Preprocessing**: Comprehensive scripts and notebooks for cleaning and preparing retail sales data
- **Exploratory Data Analysis**: In-depth visualizations and insights into sales trends, seasonality, and anomalies
- **Advanced Modeling**: Implementation of various forecasting models including:
  - ARIMA (AutoRegressive Integrated Moving Average)
  - XGBoost
  - Additional time series models
- **Model Evaluation**: Comprehensive metrics and visualizations to compare model performance
- **Experiment Tracking**: MLflow integration for reproducible and trackable experiments
- **Interactive Web App**: Streamlit-based application for real-time forecast visualization by store and item

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NuzhatJabeen19/retail_demand_forecast.git
   cd retail_demand_forecast
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare your data:**
   - Place raw data files in the `data/` folder
   - (Optional) Add external data sources to `Data_Kaggel_&_Guayas/`

### Usage

1. **Explore the data and models:**
   - Navigate to the `notebooks/` directory
   - Run the Jupyter notebooks for EDA and modeling experiments

2. **Launch the forecasting application:**
   ```bash
   cd Forecasting_app
   streamlit run app.py
   ```
## Screenshots

*Add screenshots here to showcase the UI and plots.*
*![alt text](image.png)*


3. **Access the web interface:**
   - Open your browser and go to the URL displayed in the terminal (typically `http://localhost:8501`)
   - Use the interactive interface to explore forecasts by store and item

## 📊 Models Implemented

- **ARIMA**: Classical statistical approach for time series forecasting
- **XGBoost**: Gradient boosting framework optimized for time series prediction
- **Additional Models**: Various other time series and machine learning approaches

## 🔧 Technologies Used

- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical computing
- **Scikit-learn**: Machine learning library
- **XGBoost**: Gradient boosting framework
- **MLflow**: Experiment tracking and model management
- **Streamlit**: Web application framework
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebooks**: Interactive development environment

## 📈 Data Sources

- Corporación Favorita Grocery Sales Forecasting (Kaggle)
- Additional external datasets for enhanced forecasting accuracy

## 🎯 Performance Metrics

The project evaluates models using various metrics including:
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Additional time series-specific metrics

## 📝 Important Notes

- Large data files and results (`data/`, `mlflow_results/`, `Data_Kaggel_&_Guayas/`) are excluded from version control via `.gitignore`
- The forecasting app expects precomputed forecasts to be available in `Forecasting_app/forecasts/`
- This project is designed for educational and research purposes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is for educational and research purposes.

## 🙏 Acknowledgments

- Kaggle for providing the Corporación Favorita dataset
- XGBoost developers for the gradient boosting implementation
- Streamlit team for the web application framework

## 📧 Contact

For questions or suggestions, please open an issue in this repository.

---

*Built with ❤️ for retail demand forecasting*
    ``` 

