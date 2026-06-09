# 🏏 IPL Win Probability Predictor

A Machine Learning web application built with Streamlit that predicts 
the win probability of IPL teams based on live match conditions.

## 🚀 Live Demo
[[Click here to view the app](https://ipl-match-probability.streamlit.app/)]

## 📌 Features
- Predicts win probability for both teams in real-time
- Based on match conditions like score, overs, wickets, target
- Clean and interactive UI built with Streamlit
- Trained on historical IPL match data

## 🛠️ Tech Stack
- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy

## ⚙️ How to Run Locally
1. Clone the repo
   git clone https://github.com/Sakshitha-reddy/IPL-WINNING-TEAM-PREDICTION.git

2. Install dependencies
   pip install -r requirements.txt

3. Run the app
   streamlit run app.py

## 📁 Project Structure
ipl-win-predictor/
├── app.py
├── pipe.pkl
├── dataset.csv
├── requirements.txt
└── README.md

## 🧠 Model Info
- Algorithm: Logistic Regression / Random Forest
- Trained on IPL match data (2008–2024)
- Features: batting team, bowling team, city, 
  target, current score, overs, wickets

## 👨‍💻 Author
Sakshitha Reddy
GitHub:  [sakshitha-reddy](https://github.com/sakshitha-reddy)
