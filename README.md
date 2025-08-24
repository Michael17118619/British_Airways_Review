# ✈️ British Airways Review & Visualisation



## A Tableau dashboard project analyzing customer reviews of British Airways.
The project explores customer satisfaction, ratings distribution, sentiment analysis, and service quality trends, helping uncover insights into factors that shape passenger experiences.

# 📸 Preview

<img width="1199" height="799" alt="British Review Dashboard" src="https://github.com/user-attachments/assets/34bac7f5-6886-4581-b92a-a1365f9c300d" />


## ✨ Key Features

⭐ **Overall Rating Distribution** – Understand how customers rate their British Airways experience.

🛫 **Class & Cabin Insights** – Compare customer satisfaction across travel classes (Economy, Business, First).

🧳 **Service Dimensions** – Analyze reviews across food, comfort, staff service, and entertainment.

💬 **Sentiment Analysis** – Identify positive vs. negative review patterns.

📊 **Trend Analysis** – Track customer experience ratings over time.

🌍 **Customer Demographics** – Explore review distribution by region and traveler type.

✈️ **Aircraft-Level Insights** – Satisfaction scores by aircraft model.


## 🛠 Tech Stack

**Visualization Tool**: Tableau

**Data Sources**:

ba_reviews.csv – British Airways customer review dataset

Countries.csv – Country-level mapping data

**Optional Preprocessing**: Python / Excel (for data cleaning)


## 🚀 Getting Started

Clone the repository

git clone https://github.com/Michael17118619/british-airways-review-project.git

Open the Tableau Project

**File**: British Airways Review Project.twbx

Ensure datasets (ba_reviews.csv, Countries.csv) are available in the /data folder.

Explore the Dashboard

Interact with filters (metric, traveller type, seat type, continent).

Drill down by month, aircraft, and region for deeper insights.


## 🔎 Steps for Analysis & Visualization

### 1️⃣ Data Preparation

Imported Countries.csv and ba_reviews.csv into Tableau.

Cleaned the data to remove errors and ensure accuracy.

Performed a 1:1 join between review data and country information to enable geographic insights.

### 2️⃣ Data Analysis

Extracted key metrics: average ratings, satisfaction distribution, and common feedback themes.

Segmented the data by travel class, destination, and review date for deeper insights.

### 3️⃣ Visualization

Designed multiple charts to highlight patterns:

📊 Bar Charts – distribution of customer ratings.

📈 Line Charts – satisfaction trends over time.

🌍 Maps – geographic distribution of reviews.

Built interactive dashboards with filters and drill-downs to enhance exploration.

### 4️⃣ Dashboard Design

Focused on creating a clear and intuitive layout for users.

Added interactive elements like filters, tooltips, and drill-downs to improve usability.


## 📂 Repository Structure

├── data/
│   ├── ba_reviews.csv         # Customer review dataset
│   ├── Countries.csv          # Country mapping data
├── British Airways Review Project.twbx   # Tableau packaged workbook
├── British Review Dashboard.png          # Dashboard screenshot
└── README.md                             # Documentation


## 📌 Insights for Stakeholders

**✅ Airline Management** – Identify service strengths and weaknesses.
**✅ Customer Experience Teams** – Improve passenger satisfaction strategies.
**✅ Marketing Teams** – Understand customer sentiment for targeted campaigns.
**✅ Travel Analysts** – Benchmark British Airways against industry standards.

## 🔮 Future Improvements

🌐 Deploy Interactive Dashboard Online using Tableau Public / Server.

🤖 Advanced NLP Analysis – Deeper sentiment insights using machine learning.

📲 Mobile-Friendly Dashboard for executives and managers.

📡 Automated Data Updates from live review feeds.

## 🤝 Contributing

Contributions are welcome!




Commit changes (git commit -m "Added new visualization")

Push to branch & open a Pull Request
