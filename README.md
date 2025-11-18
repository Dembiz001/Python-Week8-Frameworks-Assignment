CORD-19 Data Analysis & Dashboard
A comprehensive analysis of COVID-19 research papers with an interactive Streamlit dashboard.

📁 Project Structure
text
Frameworks_Assignment/
├── data_exploration.py       # Initial data analysis
├── data_cleaning.py          # Data preprocessing
├── analysis_visualization.py # Charts and insights
├── app.py                    # Streamlit dashboard
├── requirements.txt          # Dependencies
└── README.md
🚀 Quick Start
1. Setup Environment
bash
# Create virtual environment
python -m venv cord19_env

# Activate (Windows)
cord19_env\Scripts\activate

# Activate (Mac/Linux)
source cord19_env/bin/activate

# Install packages
pip install -r requirements.txt
2. Get Data
Download metadata.csv from Kaggle CORD-19 Dataset and place in project folder.

3. Run Analysis
bash
python data_exploration.py
python data_cleaning.py
python analysis_visualization.py
4. Launch Dashboard
bash
streamlit run app.py
📊 Features
Data Analysis: 500K+ research papers exploration

Visualizations: Publication trends, top journals, word frequency

Interactive Dashboard: Filters, real-time metrics, multiple chart types

Insights: COVID-19 research patterns and trends

🛠️ Technologies
Python, Pandas, Matplotlib, Seaborn

Streamlit for web dashboard

WordCloud for text visualization

📈 Key Insights
Publication surge starting 2020

Top journals concentration

Common research themes analysis

Abstract completeness statistics

Course: Frameworks Assignment
Skills: Data Analysis, Visualization, Web App Development



