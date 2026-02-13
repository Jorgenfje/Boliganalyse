# Housing Market Analysis - Østfold, Norway

AI-powered housing market analysis with web scraping, machine learning, and interactive dashboard.

![Dashboard Preview](screenshots/Oversikt.png)

## Project Description

Full-stack data science project that:
- Scrapes housing data from Finn.no (Norwegian real estate platform)
- Analyzes price trends and patterns
- Trains ML model for price prediction
- Presents results in an interactive dashboard

**Results:**
- 1,026 properties analyzed from Østfold region
- ML model with R² = 0.51
- Interactive dashboard with 4 analysis tabs

## Technologies

- **Data Collection:** BeautifulSoup, requests
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** scikit-learn (Linear Regression)
- **Visualization:** Plotly, Streamlit
- **Version Control:** Git, GitHub

## Installation

### Prerequisites
- Python 3.11 or 3.12
- pip

### Step 1: Clone repository
```bash
git clone https://github.com/yourusername/boliganalyse.git
cd boliganalyse
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

## Usage

### 1. Scrape housing data
```bash
python scraper.py
```
Takes 5-10 minutes and saves data to `boliger_ostfold.csv`.

### 2. Run dashboard
```bash
streamlit run app.py
```
Opens automatically in browser at `localhost:8501`.

## Features

### 📊 Overview
- Price distribution (histogram)
- Price spread (box plot)
- Size vs price analysis

### 🗺️ Regional Analysis
- Municipality comparison
- Price per sqm analysis
- Property type distribution

### 🤖 AI Price Calculator
- ML model for price prediction
- Input: size, municipality, property type
- Comparison with similar properties

### 📈 Detailed Analysis
- Statistics per municipality
- Raw data with filtering

## Developed by

Jørgen A. Fjellstad  

## License

MIT
