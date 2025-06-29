# 🌸 Flower Farming Recommendation System

This project is a machine learning-based recommendation system designed to help farmers choose the most suitable flowers for cultivation based on environmental and soil parameters. The system utilizes predictive analytics to recommend flowers that are optimal for specific farming conditions.

## 📁 Project Structure
Flower-Farming-Recommendation/
├── Dataset/
│ └── flower_data.csv
├── Flower Recommendation.ipynb
├── Model/
│ └── flower_model.pkl
├── static/
│ └── styles.css
├── templates/
│ └── index.html
├── app.py
└── README.md

## 🔍 Features

- User input form for soil and weather conditions
- Predicts the most suitable flower crop using a trained ML model
- Web-based interface using Flask
- Clean and responsive frontend

## ⚙️ Technologies Used

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **Flask (for the web application)**
- **HTML/CSS (for frontend)**
- **Jupyter Notebook (for model development)**

## 🚀 How to Run Locally

1. Clone this repo
   ```bash
   git clone https://github.com/yourusername/Flower-Farming-Recommendation.git
   cd Flower-Farming-Recommendation
   
2.Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install dependencies
pip install -r requirements.txt

4.Run the Flask app
python app.py

📊 Dataset
The dataset used includes:

Temperature

Humidity

Soil type

Rainfall

pH level

Suitable flower type (label)

(Make sure to cite your data source if it's from a public domain)

🤖 Model
Model Type: Random Forest Classifier (or mention whichever you used)

Accuracy: ~XX% (update with actual results)

Pickled for reuse via joblib or pickle

📌 Future Enhancements
Add multilingual support for regional farmers

Integrate with APIs to get real-time weather data

Deploy using Docker or cloud services

