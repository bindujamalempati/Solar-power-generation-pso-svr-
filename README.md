# PSO-SVR Forecasting 🌞📈

A smart solar power generation forecasting app that uses a hybrid machine learning model combining **Particle Swarm Optimization (PSO)** and **Support Vector Regression (SVR)** to make accurate predictions. The app includes a user-friendly web interface built using Flask and integrates model visualization and result display capabilities.

---

## 📌 Project Overview

The goal of this project is to build a web-based forecasting system that:
- Predicts solar power generation using advanced ML models.
- Provides a clean and interactive user interface.
- Visualizes predictions and supports user interaction.

The project includes:
- **Machine Learning Model (PSO-SVR)** for forecasting.
- **Flask Web App** for user interaction and display.
- **HTML/CSS Templates** for frontend rendering.
- **Database** for user signup/signin (`signup.db`).

---

## ⚙️ How It Works

1. **Data Input**: Takes solar power generation data (`spg.csv`).
2. **Model Training**:
   - **SVR** is used for regression modeling.
   - **PSO** is used to optimize SVR parameters.
3. **Prediction**: Forecasts power output for given input.
4. **Web Display**: Flask serves a user interface to visualize results.

---

## 🧪 Tech Stack

| Area              | Technology Used              |
|-------------------|------------------------------|
| Backend           | Python, Flask                |
| Machine Learning  | Scikit-learn, PSO, SVR       |
| Model Storage     | `.pkl` for SVR, `.h5` for LSTM |
| Frontend          | HTML5, CSS3, JS, Bootstrap   |
| Visualization     | Matplotlib, custom PNG charts|
| Database          | SQLite (`signup.db`)         |

---

Sure! Here's the **correctly formatted Markdown code** (just the code, no extra text) for the sections you asked — clean and ready to paste into your `README.md` file:

---

### 📁 **Folder Structure**

```markdown
## 📁 Folder Structure

project/
│
├── app.py                      # Flask main application
├── spg.csv                     # Input data
├── Notebook.ipynb              # Model development notebook
├── model.pkl                   # Trained PSO-SVR model
├── my_h5_model_lstm_h1.h5      # LSTM model (optional feature)
├── requirements.txt            # Python dependencies
│
├── templates/                  # HTML frontend pages
│   ├── index.html
│   ├── result.html
│   └── ...
│
├── static/                     # Static resources
│   ├── img/                    # Banner and UI images
│   ├── js/                     # JavaScript files
│   └── forecast.png            # Output chart
│
└── signup.db                   # SQLite DB for user login
```

---

### ▶️ **How to Run the App Locally**

```markdown
## ▶️ How to Run the App Locally

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/solar-forecast-pso-svr.git
cd solar-forecast-pso-svr
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask App

```bash
python app.py
```

Then go to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser 🚀
```

