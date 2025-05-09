# Steam Game Popularity Dashboard

An interactive and elegant Streamlit dashboard to visualize Steam game trends over time. Analyze player engagement, gain/loss trends, and identify top games based on peak and average player counts.

## Features

-  **Top 10 Games** by average vs peak player counts
-  **Trend Visualizations**: Monthly trends for average/peak players, drop ratio, gain/loss
-  **Dynamic Game Filter**: Choose a game to visualize customized stats
-  **Fully Interactive** UI with dropdowns, metrics, and hover tooltips
-  Clean layout with light background and zero scroll clutter

##  Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (Pandas, Plotly)
- **Data**: Parquet format from a cleaned SteamCharts dataset

##  How to Run Locally

Clone this repo and install the required packages:

```bash
git clone https://github.com/your-username/steam-dashboard.git
cd steam-dashboard
pip install -r requirements.txt
streamlit run dashboard.py

