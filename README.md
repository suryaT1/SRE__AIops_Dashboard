# 📊 SRE AIOps Dashboard

An interactive, AI-powered dashboard built to assist **Site Reliability Engineers (SREs)** in monitoring, forecasting, and gaining intelligent insights from operational incident data using machine learning and large language models.

---

## 🔍 Overview

This project was developed using 3 years of real-world incident data from a customer environment. It focuses on forecasting, visualizing patterns, and generating AI-based insights to enhance operational efficiency and proactive issue resolution.

---

## 🚀 Key Features

- **📈 Incident Forecasting**: Utilizes the ARIMA model to predict future incident trends and alert engineers in advance.
- **🤖 AI Insights**: Integrates with LLMs such as **Mistral AI**, **Tiny Llama**, and **Ollama** to derive probable causes and enhance root cause analysis.
- **🧠 Pattern Detection**: Applies machine learning and data analysis algorithms to identify recurring incident patterns and hot zones.
- **📊 Visual Analytics**: Displays metrics such as performance, availability, and error budgets with heatmaps, trend graphs, and interactive filters.
- **💡 Trend Categorization**: Analyzes incidents with respect to categories and timelines to understand evolving system behaviors.

---

## 🧰 Tech Stack

| Tool/Tech        | Purpose                                  |
|------------------|------------------------------------------|
| Python           | Core development language                |
| Dash & Plotly    | Building interactive dashboard UI        |
| Pandas, NumPy    | Data wrangling and preprocessing         |
| Statsmodels      | ARIMA time-series forecasting            |
| Scikit-learn     | Pattern detection and ML analysis        |
| Mistral AI, Tiny Llama, Ollama | LLMs for generating insights      |

---

## 📁 Dataset

- Incident data collected over **3 years**.
- Includes timestamps, categories, priorities, and resolution data.
- Preprocessed and structured for time-series forecasting and ML models.

---

## 📌 Metrics Tracked

- ✅ Availability
- ⚙️ Performance
- ❌ Error Budget Consumption
- 📉 Incident Frequency & Volume
- 📊 Category-Wise Trend Analysis

---

## 🧪 AI Capabilities

- **Root Cause Prediction** using LLMs (Mistral, Tiny Llama via Ollama)
- **Incident summarization and insight generation**
- **Anomaly correlation** with historical trends

---

## 🖥️ Dashboard

- Fully interactive, built with **Dash**.
- Supports zoom, filter, category-wise breakdown, and real-time updates.
- Heatmaps for visualizing problem-prone areas across time and category.

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sre-aiops-dashboard.git
   cd sre-aiops-dashboard
