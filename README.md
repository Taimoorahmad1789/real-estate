[3_REALESTATE_README.md](https://github.com/user-attachments/files/29437126/3_REALESTATE_README.md)
<div align="center">

# 🏠 RealEstatePro
### Islamabad Property Intelligence — Predict · Analyse · Recommend

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)](https://plotly.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

*A full-stack ML application combining property price prediction, market analytics, and similarity-based recommendations for the Islamabad real estate market.*

</div>

---

## 📌 Overview

RealEstatePro is a Streamlit-based real estate intelligence platform that helps buyers, sellers, and investors make data-driven decisions. It unifies three core capabilities — ML price prediction, interactive analytics, and property recommendations — in a single, polished dashboard.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💰 **Price Prediction** | Trained ML regression pipeline for accurate property price estimation |
| 📊 **Market Analytics** | Interactive geospatial and distribution visualisations of the Islamabad market |
| 🔍 **Smart Recommendations** | Cosine similarity-based property recommendation engine |
| ☁️ **Word Cloud Analysis** | Feature text analysis by location to reveal dominant property characteristics |

---

## 🖼️ App Preview

> *(Add a screenshot here: drag & drop an image into this file on GitHub, then paste the generated URL below)*

```
![App Screenshot](screenshot.png)
```

---

## 🗂️ Project Structure

```
real-estate/
│
├── Home.py                   # Main Streamlit application entry point
├── requirements.txt          # Python dependencies
│
├── pipeline (1).pkl          # Trained price prediction pipeline
├── df (1).pkl                # Base dataset for prediction inputs
├── data_viz1.xls             # Dataset for analytics visualisations
├── wordcloud_df.xls          # Feature text dataset for word cloud
├── feature_text.pkl          # Preprocessed feature text for word cloud
├── location_distance.pkl     # Location distance matrix for recommendations
│
├── cosine_sim1               # Similarity matrix (part 1)
├── cosine_sim2               # Similarity matrix (part 2)
└── cosine_sim3               # Similarity matrix (part 3)
```

---

## ⚡ Quick Start

### Prerequisites
- Python 3.9+

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Taimoorahmad1789/real-estate.git
cd real-estate

# 2. Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run Home.py
```

Open your browser at `http://localhost:8501`

> **Note:** Keep all `.pkl`, `.xls`, and `cosine_sim*` files in the project root. If any analytics or recommendation files are missing, the app will display a warning for that section only.

---

## 🔬 How It Works

### Price Prediction
```
User Inputs (location, size, type, bedrooms)
        ↓
Scikit-learn Regression Pipeline
        ↓
Estimated Property Price (PKR)
```

### Recommendation Engine
```
Selected Property Features
        ↓
Cosine Similarity Matrix (precomputed)
        ↓
Top N Similar Properties Ranked by Score
```

---

## 🛠️ Tech Stack

- **Language**: Python 3.9+
- **ML**: Scikit-learn (regression, similarity)
- **Data**: Pandas, NumPy
- **Frontend**: Streamlit
- **Visualisation**: Plotly, Matplotlib, Seaborn
- **NLP**: Word Cloud generation

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Taimoor Ahmad** — Junior Machine Learning Engineer

[![Portfolio](https://img.shields.io/badge/Portfolio-6366f1?style=flat-square)](https://taimoorahmad1789.github.io/taimoor-portfolio)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square)](mailto:taimoor.ahmad.ai@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Taimoorahmad1789)
