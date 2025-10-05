🧠 Competitive Intelligence Tracker for Startups



🚀 Overview

Startups struggle to keep track of competitors’ product launches, feature updates, and marketing campaigns.
Competitive Intelligence Tracker is an AI-powered solution that monitors competitors’ websites, social media, and press releases — summarizes key updates, and sends actionable insights via Slack, Telegram, and an interactive Streamlit dashboard.

Goal: Turn scattered competitor data into structured, actionable intelligence for startup decision-makers.

🧩 Key Features

🌐 Real-Time Monitoring: Websites, blogs, Twitter, Reddit, and news portals.

🤖 AI Summarization: Highlights critical updates with NLP & Gemini API.

💬 Slack & Telegram Alerts: Instant notifications for the team.

📊 Streamlit Dashboard: Trend visualization, competitor movements, actionable metrics.

🗄️ Persistent Storage: SQLite database for historical and analytical purposes.

⚙️ Installation & Run

Clone Repo:

git clone https://github.com/Projects6677/competitive_intel_tracker.git
cd competitive_intel_tracker


Install Dependencies:

pip install -r requirements.txt


Run Core Pipeline:

python run_ci.py


Launch Streamlit Dashboard:

streamlit run dashboard.py

🧪 Workflow

Scrapes competitor content across multiple channels.

AI agent analyzes and summarizes changes.

Sends instant notifications via Slack/Telegram.

Streamlit dashboard displays insights, trends, and analytics.

🏗️ Project Structure
competitive_intel_tracker/
│
├── main/                 # Core pipeline logic
├── run_ci.py             # Orchestrator script
├── dashboard.py          # Streamlit dashboard
├── utils/                # Helper modules
├── database.sqlite       # Local storage
├── requirements.txt
└── README.md

🎥 Demo Video

Experience the tracker live in action — real-time competitor monitoring, AI summarization, Slack alerts, and dashboard analytics:

The demo showcases:https://youtu.be/fAN2hSShfMY

Automated competitor scraping

AI summarization of feature & marketing changes

Slack & Telegram notifications

Streamlit dashboard interaction

📥 Access the Full Project

➡️ Download the ZIP file from GitHub:
🔗 https://github.com/Projects6677/competitive_intel_tracker/archive/refs/heads/main.zip

Unzip and follow the Installation & Run steps above.

🏆 Hackathon Goals

Modular AI agent pipeline

Automated competitor insights for startups

Real-time Slack/Telegram notifications

Streamlit visualization for actionable intelligence

🔮 Future Roadmap

Expand data sources (LinkedIn, ProductHunt, Crunchbase)

Add email digest summaries

Voice-based AI reporting

Cloud deployment via Streamlit Cloud or AWS

🏷️ Hashtags

#AIHackathon2025 #CompetitiveIntelligence #DataScience #Python #Streamlit
#SlackBot #TelegramBot #Automation #AIAgents #StartupTools #RealTimeMonitoring
