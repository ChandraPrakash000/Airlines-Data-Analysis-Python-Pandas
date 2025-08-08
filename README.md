
# ✈️ Airlines Analysis Project
Overview
This project explores airline booking data to uncover insights into:

Favorite destinations and source cities
Price variations based on:
Duration of the flight
Number of days left before departure
Other relevant factors
The goal is to help travelers, analysts, and airline companies better understand booking trends and pricing strategies.

📊 Features

Top Destinations & Source Cities: Identify the most popular travel routes.
Price Trend Analysis:
How prices change with flight duration
Impact of booking lead time (days left before departure)
Interactive Visualizations: Charts and graphs for easy interpretation.
Data Cleaning & Preprocessing: Ensures accurate and reliable analysis.

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook for analysis and visualization
CSV/Excel data sources


📁 Project Structure


airline-analysis/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Jupyter notebooks with analysis
├── visuals/               # Generated plots and charts
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies


Install dependencies:

pip install pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns


Run the Jupyter notebook:

jupyter notebook notebooks/airline_analysis.ipynb


📈 Sample Insights

Delhi to Mumbai is the most popular route.
Prices tend to increase sharply as the departure date approaches.
Longer flights generally have higher prices, but exceptions exist.


🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests.
