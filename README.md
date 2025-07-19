<p align="center"><img src="assets/Picture1.jpg" width="200"/></p>

# Greenearth Connect – Showcase 🌱🌍

**AI-powered platform for personalized outdoor safety and air quality guidance.**  
_A curated portfolio of my contributions to the Greenearth Connect Capstone project._

> 🌐 Live Demo: [greenearthconnect-2.onrender.com](https://greenearthconnect-2.onrender.com)  
> 🧪 Source Repo (Team): [github.com/DC-Capstone1W25/greenearthconnect](https://github.com/DC-Capstone1W25/greenearthconnect)

---

## 🔍 Project Overview

**Greenearth Connect** is a smart environmental health platform that helps users make safer outdoor decisions by providing real-time air quality forecasts, health-based recommendations, personalized activity suggestions, and AI-powered news summaries.

Users can input their personal health and activity preferences and receive:
- Air Quality Index (AQI) forecasts using **XGBoost** and **LSTM**
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>
- Tailored activity recommendations using **Random Forest Classifier**
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>
- News and safety updates powered by **HuggingFace NLP pipelines**
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>
- Map-based AQI visualizations for real-time and historical data
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>

---

## 💼 My Role & Contributions

As part of a five-member capstone team, I focused on:

### 🧠 Machine Learning Development
- Developed the **AQI Forecasting Engine** using:
  - `XGBoost` models on emissions + weather datasets
  - `LSTM` for time-series AQI prediction
  - Data sourced from [EPA’s Outdoor Air Quality Dataset](https://www.epa.gov/outdoor-air-quality-data/download-daily-data)
- Performed hyperparameter tuning and validation using **RMSE**, achieving improved prediction accuracy (RMSE ↓ from 9.96 to 7.03)
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>

### 🧘‍♂️ Activity Recommender
- Designed and implemented a **Random Forest Classifier** that recommends activities based on:
  - Health status, environmental conditions, age, preferences, etc.
- Engineered a mock dataset and generated **25+ test cases** for model validation
- Tuned with `GridSearchCV` and achieved **100% accuracy** (note: overfitting addressed in future scope)
  <p align="center"><img src="assets/Picture1.jpg" width="200"/></p>

### 📰 Newsfeed AI
- Built a news summarization module using:
  - `BeautifulSoup`, `GoogleNews RSS`
  - HuggingFace Transformers (`Summarization`, `Sentiment Analysis`, `Text Generation`)
- Delivered contextual environmental tips & updates via chatbot integration

---

## 🧱 Tech Stack

| Layer              | Tools & Frameworks                               |
|-------------------|---------------------------------------------------|
| Frontend          | React.js, Folium, Google Maps API                |
| Backend/API       | Node.js, Express, GraphQL, Python                |
| Machine Learning  | XGBoost, Random Forest, LSTM, Scikit-learn       |
| Data Handling     | Pandas, NumPy, Mongoose, BeautifulSoup           |
| NLP / AI Pipelines| HuggingFace Transformers, OpenAI GPT API         |
| Deployment        | Docker, Render                                    |
| Database          | MongoDB                                           |

---

## 🧠 Models at a Glance

| Model                        | Purpose                                      | Tools Used                    |
|-----------------------------|----------------------------------------------|-------------------------------|
| **XGBoost / LSTM**          | Predict AQI based on emissions + weather     | EPA Data, XGBoost, LSTM       |
| **Random Forest Classifier**| Recommend personalized activities            | Custom Dataset, Scikit-learn  |
| **HuggingFace Pipelines**   | Summarize and deliver air quality news       | Transformers, BeautifulSoup   |

---

## 🗂️ Key Features

- 🌫 **AQI Forecast Dashboard** – Predict air pollution levels for user-specific zones
- 🏃 **Activity Recommender** – Suggest indoor/outdoor activities based on conditions
- 🧠 **AI News Summarizer** – Pulls relevant air quality news with AI-generated summaries
- 🗺 **Map Visualization** – Interactive AQI heatmaps using GEOJSON and Folium
- 🧾 **Health Insights** – Personalized alerts based on medical history and preferences

---

## 📦 Dataset Sources

- **EPA Daily Air Quality Data**  
  [https://www.epa.gov/outdoor-air-quality-data/download-daily-data](https://www.epa.gov/outdoor-air-quality-data/download-daily-data)
- **Weather & Environmental Data**  
  Weather Underground, WeatherSource (Real-time + Forecasted)
- **Custom Mock Data**  
  Simulated datasets for activity modeling & health condition mapping

---

## 🚀 Deployment & Architecture

- **Monorepo** with frontend (`React`) + backend (`Node/Python`)
- Dockerized services deployed via **Render**
- Uses **GraphQL API** for efficient data exchange
- AQI and recommendation models are served via Python APIs

---

## 🛠️ Challenges Tackled

- Limited dataset availability for certain use cases (e.g., AQI impact on health conditions)
- Integration of multiple AI pipelines in a unified frontend
- Docker + Render deployment issues during multi-service setup
- Web scraping blocked by major news providers — switched to RSS feeds and summarization

---

## 👥 Team

| Name                      | Role                                       |
|---------------------------|--------------------------------------------|
| **Agilan Sivakumaran**    | ML Engineer – AQI Forecasting, Recommendations, News AI |
| Thedyson Luzon            | Project Manager, Full-Stack Development    |
| Rodrigo Rangel-Alvarado   | ML Engineer – Data Modeling & API Integration |
| Thao Tran                 | Full-Stack Developer – Frontend & UI       |
| Athira Raj Vijaya Sree    | UI/UX Designer                             |

---

## 📽️ Demo

> 🔗 Live Website: [greenearthconnect-2.onrender.com](https://greenearthconnect-2.onrender.com)

![AQI Forecast Screenshot](assets/aqi-dashboard.png)
![Activity Recommendation Screenshot](assets/activity-recommend.png)

_(More screenshots and video demo coming soon)_

---

## 📣 License & Disclaimer

This is a **personal showcase repo** highlighting my specific contributions to the Greenearth Connect Capstone project. For full team collaboration history and source code, please visit the [original GitHub repo](https://github.com/DC-Capstone1W25/greenearthconnect).

---

