
# 🏡 California House Pricing Prediction

This project predicts housing prices in California using machine learning techniques. Built with Python, Flask, and scikit-learn, the model is trained on the California Housing dataset and deployed as a web application.

## 🚀 Features

- Regression model to predict house prices
- Preprocessing pipeline with feature scaling
- Web interface for user inputs
- Dockerized and Heroku-ready for deployment

## 📊 Technologies Used

- **Python 3.7**
- **Jupyter Notebook** for data exploration
- **scikit-learn** for model training
- **Flask** for backend web development
- **HTML (Jinja templates)** for frontend rendering
- **Pickle** for model serialization (`regmodel.pkl`, `scaling.pkl`)
- **Docker** for containerization
- **Heroku** for deployment
- **Pandas, NumPy, Matplotlib** for data manipulation and visualization

## 📁 Project Structure

```
calihousepricing/
│
├── California_HousePricing.ipynb   # Jupyter notebook with EDA and model training
├── app.py                          # Flask application
├── regmodel.pkl                    # Trained regression model
├── scaling.pkl                     # Fitted scaler
├── requirements.txt                # Python dependencies
├── Dockerfile                      # Docker configuration
├── Procfile                        # Heroku deployment instruction
└── templates/
    └── home.html                   # HTML template for the web app
```

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/slowloris-98/calihousepricing.git
cd calihousepricing
```

### 2. Create and activate virtual environment
```bash
conda create -p venv python=3.7 -y
conda activate venv/
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
python app.py
```

## 🌐 Deployment

You can deploy the app using Docker or Heroku. Make sure to include the `Dockerfile` and `Procfile` when pushing to cloud services.

## 📝 License

This project is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

## 🙏 Acknowledgments

Inspired by [Krish Naik](https://github.com/krishnaik06) and his machine learning deployment tutorials.
