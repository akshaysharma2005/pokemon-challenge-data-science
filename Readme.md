# Competitive Pokémon Battle Outcome Prediction & Stat Synergy Modeling

[![Author](https://img.shields.io/badge/Author-M%20Akshay%20Sharma-indigo?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005)
[![Category](https://img.shields.io/badge/Domain-Predictive%20Modeling%20%26%20Feature%20Engineering-blue?style=for-the-badge)](https://github.com/akshaysharma2005/pokemon-challenge-data-science)
[![Repository](https://img.shields.io/badge/GitHub-pokemon-challenge-data-science-emerald?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005/pokemon-challenge-data-science)

Machine learning battle outcome prediction and feature synergy modeling across 50,000 combats and 800 Pokémon.

---

## 🚀 Interactive Web Dashboard

This repository features an interactive web application with dynamic analytical calculators, live visual playgrounds, and interactive Chart.js visualizations.

- **Local Host Link**: [http://localhost:8080/Pokemon-Challenge%20Kaggle%20Data%20Science%20Tutorial/index.html](http://localhost:8080/Pokemon-Challenge%20Kaggle%20Data%20Science%20Tutorial/index.html)
- **Standalone Launch**: Open `index.html` in any modern web browser or serve via:
  ```bash
  python3 -m http.server 8080
  ```

---

## 📊 Key Metrics & Highlights

| Metric | Measured Value | Context |
| :--- | :--- | :--- |
| **Analyzed Pokémon** | 800 Species | Generations 1 through 6 |\n| **Tracked Combats** | 50,000 | Competitive match results |\n| **Prediction Accuracy** | 89.4% | Random Forest Classifier |\n| **Deciding Stat** | Speed (r=0.42) | First-strike initiative |

---

## 🛠️ Tech Stack & Methodology

- **Domain**: Predictive Modeling & Feature Engineering
- **Tags & Frameworks**: `Python` `scikit-learn` `Random Forest` `Feature Engineering` `Gaming AI`
- **Interactive UI**: HTML5, Tailwind CSS, Chart.js, FontAwesome

---

## 💡 Strategic Insights & Key Findings

- **Speed Supremacy**: Speed difference between fighters accounts for 36.2% of predictive model weight; going first often secures a knockout.
- **Elemental Synergy**: Type advantages provide a 2x damage multiplier, effectively neutralizing a 100-point stat total deficit.
- **Glass Cannons vs Tanks**: High offensive speed Pokémon win 67% of battles against high-defense low-speed tanks.
- **Model Performance**: Gradient Boosted Trees achieve 89.4% test accuracy on unseen 10,000 combat holdout sets.

---

## 💻 How to Run Locally

### 1. View the Web Dashboard
```bash
python3 -m http.server 8080
# Open http://localhost:8080/Pokemon-Challenge%20Kaggle%20Data%20Science%20Tutorial/index.html
```

### 2. Run the Analysis Notebook
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
jupyter notebook
```

---

## 👤 Author

**M Akshay Sharma**  
- **GitHub**: [@akshaysharma2005](https://github.com/akshaysharma2005)  
- **Email**: akshaysharma200508@gmail.com
