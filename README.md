# Smart_BI
Smart BI Dashboard with Predictive Analytics – An end-to-end solution that cleans and analyzes retail data, visualizes trends, and applies machine learning to forecast sales. Built with FastAPI and Streamlit, it helps businesses make smarter, data-driven decisions.


📊 Smart BI Dashboard with Predictive Analytics

An end-to-end Business Intelligence solution that combines data analysis, predictive machine learning, and interactive dashboards. This project uses a retail dataset to demonstrate how businesses can analyze historical sales, identify trends, and forecast future demand using AI-powered insights.

🚀 Features

Data Processing & Cleaning → Raw retail data transformed into structured, clean datasets.

Exploratory Data Analysis (EDA) → Visual insights into sales, customer behavior, and product performance.

Predictive Analytics → Machine learning model forecasts sales for future months.

FastAPI Backend → Serves predictions and analytics through an API.

Streamlit Frontend (Glassmorphism UI) → Beautiful, interactive dashboard to view insights and predictions.

Full-Stack Workflow → From raw data → processed insights → deployed web app.

🛠️ Tech Stack

Programming: Python

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-learn (Regression, Time Series)

Backend: FastAPI, Uvicorn

Frontend: Streamlit (with Glassmorphism UI)

Deployment Ready: Easily extendable to Docker, AWS/GCP/Azure

📂 Project Structure:


Smart_BI/
│── backend/
│   ├── main.py                 # FastAPI app entry point
│   ├── training/
│   │   └── train_model.py      # Model training script
│   ├── models/                 # Saved ML models
│   └── utils/
│       └── data_processing.py  # Data cleaning & preprocessing functions
│
│── frontend/
│   ├── streamlit_app.py        # Streamlit dashboard
│   ├── assets/                 # Logo & background images
│   │   ├── logo.jpeg
│   │   └── background.jpg
│
│── data/
│   ├── raw/                    # Original dataset (from Kaggle)
│   │   └── vendas.csv
│   ├── processed/              # Cleaned dataset & visualizations
│   └── notebooks/
│       └── eda.ipynb           # Exploratory data analysis notebook
│
│── requirements.txt            # Dependencies
│── README.md                   # Documentation (this file)



📈 Real-World Use Case

Retailers can forecast demand to optimize stock and reduce over/under inventory.

Businesses can track KPIs and sales performance in one interactive dashboard.

Managers can make data-driven decisions for marketing, pricing, and supply chain.

Extendable to finance, healthcare, and logistics as a predictive BI tool.

🌍 Impact

Efficiency Boost → Automates reporting and forecasting, saving time.

Data-Driven Decisions → Helps businesses plan better and reduce risks.

Scalable Solution → Can be adapted across industries with minimal changes.

Portfolio Value → Demonstrates full-stack skills: data, ML, backend, frontend.

📌 Example Prediction Workflow

User enters a month (e.g., 2025-01).

Frontend (Streamlit) sends request to backend API (/predict).

Backend runs ML model and returns predicted sales.

Frontend displays results in an interactive card.



✨ Future Improvements

Add time series forecasting (ARIMA/Prophet/LSTM) for more accurate predictions.

Connect to a real-time database (PostgreSQL/MySQL).

Deploy full-stack app using Docker + AWS/GCP/Azure.

Add user authentication & role-based dashboards.
