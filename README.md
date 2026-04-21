# 🏏 IPL Score Predictor
<img width="1083" height="712" alt="230604545-5df8eb47-a183-4594-b131-f55a234dae0d" src="https://github.com/user-attachments/assets/c4568b05-e8ab-48ef-9421-fbafa12726d7" />
## 📌 Project Overview

The **IPL Score Predictor** is a deep learning-based project that predicts the **final score of an IPL match** using match-related features such as teams, venue, current runs, wickets, and overs.

This project uses **data preprocessing, feature engineering, and a neural network model** to make predictions.

---

## 🚀 Features

* Predicts final IPL score in real-time
* Uses historical IPL match data
* Applies data preprocessing and encoding techniques
* Deep learning model built using TensorFlow/Keras
* Visualization of insights using Seaborn and Matplotlib

---

## 🧠 Tech Stack

* **Python**
* **Pandas, NumPy** → Data processing
* **Seaborn, Matplotlib** → Data visualization
* **Scikit-learn** → Preprocessing & evaluation
* **TensorFlow / Keras** → Deep Learning model

---

## 📂 Dataset

* IPL match dataset (`ipl_data.csv`)
* Contains:

  * Batting team
  * Bowling team
  * Venue
  * Runs
  * Wickets
  * Overs
  * Batsman & Bowler details

---

## 🔄 Workflow

### 1. Data Preprocessing

* Handling missing values
* Encoding categorical features using Label Encoding
* Feature selection

### 2. Data Visualization

* Matches per venue
* Top batsmen by runs
* Top bowlers by wickets
* Correlation heatmap

### 3. Feature Engineering

Selected features:

* Batting team
* Bowling team
* Venue
* Runs
* Wickets
* Overs
* Striker
* Batsman
* Bowler

---

### 4. Model Building

* Neural Network using Keras:

  * Dense layers with ReLU activation
  * Output layer for regression
* Loss function: Mean Squared Error
* Optimizer: Adam

---

### 5. Model Training

* Train-test split applied
* Data scaling using MinMaxScaler
* Model trained for multiple epochs

---

### 6. Evaluation

* Metrics used:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)

---

## 📊 Results

* Model successfully learns match patterns
* Provides reasonably accurate score predictions
* Training vs validation loss plotted for performance analysis

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone <your-repo-link>
cd IPL-Score-Predictor
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

```bash
jupyter notebook IPL_score_Predictor.ipynb
```

---

## 💡 Future Improvements

* Use advanced models like LSTM for time-series prediction
* Hyperparameter tuning
* Deploy as a web app (Flask/Streamlit)
* Use larger and updated datasets

---

## 🎯 Use Cases

* Cricket analytics
* Live match prediction systems
* Sports data science projects
* Final year academic projects

---

## 📜 License

This project is for educational purposes.

---

## 🙌 Acknowledgements

* IPL Dataset sources
* TensorFlow & Scikit-learn documentation

---

