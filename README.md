# A Personal Project on Product Analytics & User Behavior Insights 
A personal data science project that analyzes user behavior, feature usage, funnels, and retention using simulated/public app data.  
The goal is to practice **product-style analytics** and **light ML modeling** to understand what drives activation, engagement, and churn, and to present those insights in an interactive Streamlit dashboard.

---

## 🔍 Motivation

I’ve always been curious about how people actually use products—why they tap some features and ignore others, why they come back one week and disappear the next. During my externship at Wayfair as an AI Agent developer, I saw firsthand how trends, behavior, and competitive signals drive real business decisions. At the same time, my earlier ML projects (SystemFit, FarmGuide, Loan Risk) were very model-focused, and I realized I needed to grow the “product analytics” side of data science too.

This project is my way of combining those ideas: I built a product analytics and user behavior dashboard to model activation, engagement, funnels, retention, and churn. Instead of just optimizing accuracy, I wanted to practice thinking in of real product metrics that data teams care about. Metrics I used for this  DAU/WAU, conversion, and churn risk.

---

## 🧱 Tech Stack

- **Languages:** Python, SQL  
- **Libraries:** pandas, NumPy, scikit-learn, Plotly  
- **App Framework:** Streamlit  
- **Data:** Simulated / public-style app data (users, sessions, events)

---

## ✨ What This Project Does

- Analyzes **user behavior** across users, sessions, and events  
- Computes **product metrics**:
  - DAU / WAU (Daily / Weekly Active Users)  
  - Activation rate  
  - Funnel conversion (e.g., visit → activation → core action → purchase)  
  - Retention and churn indicators  
- Uses **light ML modeling** (e.g., clustering / simple churn prediction) to:
  - Identify high-impact behaviors  
  - Segment users by engagement level  
- Exposes all of this through an **interactive Streamlit dashboard** so someone in a product/DS role can:
  - Slice by segments  
  - Inspect funnels  
  - See retention patterns  
  - Explore what drives engagement

---

## 📊 Example Questions This Dashboard Helps Answer

- Which features are most strongly associated with **retained users**?  
- Where are users dropping out in the **activation funnel**?  
- How do engagement metrics differ by **segment** (e.g., heavy vs light users)?  
- What behaviors correlate with **churn risk**?  

---

## 📁 Project Structure


```bash
product-analytics-user-behavior-insights/
├── data/
│   ├── users.csv
│   ├── sessions.csv
│   └── events.csv
├── notebooks/
│   └── analysis.ipynb
├── app/
│   └── streamlit_app.py
├── generate_mock_data.py
├── requirements.txt
└── README.md
