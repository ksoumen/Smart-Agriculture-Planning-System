🌾 Precision Farming System for Resource and Profit Optimization
🎓 Final Year B.Tech Project | Computer Science and Business System

Academy of Technology, Hooghly
Under the guidance of: Dr. Dilip Kumar Maity
Team Members:

Sourish Saha

Soumen Karmakar

Niladri Biswas

Ujjal Samanta

Sakshi Kahar

📘 Project Overview

Farming is a delicate balance of resources, environment, and market conditions.
This project introduces a Machine Learning–powered Precision Farming System that helps farmers make data-driven decisions for fertilizer and pesticide use, crop recommendation, and profit prediction.

The system uses supervised learning models and an interactive Streamlit web app to provide instant insights for better resource and profit optimization.

🔗 Live Demo: farm-prediction-model.streamlit.app

📂 Source Code: GitHub Repository

🚀 Features

🌱 Fertilizer & Pesticide Prediction — Predicts required quantities using regression models.

🌾 Crop Recommendation — Suggests the most suitable crop based on soil and climate.

💰 Profit Estimation — Calculates expected yield, cost, and net profit.

🧠 Multi-Model ML Approach — Uses Random Forest, Gradient Boosting, KNN, and SVM.

🧮 Financial Calculator — Converts predictions into real-world financial insights.

💻 User-Friendly Interface — Built with Streamlit for simplicity and accessibility.

🧬 Machine Learning Models Used
Task	Algorithm	Metric	Performance
Fertilizer Prediction	Random Forest Regressor	RMSE	~8.25
Pesticide Prediction	Gradient Boosting	RMSE	~8.50
Yield Prediction	Random Forest	RMSE	~8.25
Crop Recommendation	SVM / KNN Classifier	Accuracy	97.6%
📊 System Architecture
+---------------------------+
|   User Input (Streamlit)  |
+---------------------------+
           |
           v
+---------------------------+
|  Preprocessing & Encoding |
+---------------------------+
           |
           v
+---------------------------+
|  ML Models (Regression &  |
|   Classification)         |
+---------------------------+
           |
           v
+---------------------------+
|   Profit & Yield Outputs  |
+---------------------------+

🧠 Datasets Used
Dataset 1 – Agriculture Resource Optimization

Records: 1,450

Features: Soil nutrients (N, P, K), pH, temperature, humidity, rainfall, etc.

Targets: Fertilizer_Used, Pesticide_Used, Yield

Dataset 2 – Crop Recommendation Dataset

Records: 2,550

Features: N, P, K, Temperature, Humidity, pH, Rainfall

Target: Crop Type (29 classes)

Both datasets were cleaned, encoded, and scaled for model training using Scikit-learn.

🧰 Technologies Used
Category	Tools / Libraries
Programming Language	Python 3.8+
Frontend / UI	Streamlit
ML Libraries	Pandas, NumPy, Scikit-Learn
Visualization	Matplotlib, Seaborn
Hosting	Streamlit Cloud
Version Control	Git & GitHub
⚙️ Installation & Setup
# Clone the repository
git clone https://github.com/sahaSourish/Prediction_model.git

# Navigate to project directory
cd Prediction_model

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py


Then open the local URL displayed in your terminal (usually http://localhost:8501/).

💻 Example Prediction

Input Example:

Crop: Tomato

Soil: Loamy

N=45, P=38, K=42

Temp=27°C, Humidity=70%, Rainfall=110mm

Prices: Fertilizer ₹25/kg, Pesticide ₹40/kg, Crop ₹20/kg

Output Example:

Fertilizer Needed: 5.38 tons

Pesticide Needed: 2.71 kg

Predicted Yield: 40.39 tons

Estimated Profit: ₹6,73,000

📈 Results Summary

Random Forest achieved an RMSE of 8.25 for yield prediction.

Crop recommendation model achieved 97%+ accuracy.

Demonstrated significant potential for input cost reduction and profit increase.

🔮 Future Enhancements

Real-time integration with weather APIs and IoT sensors.

Add LSTM-based time-series forecasting for seasonal yield trends.

Mobile app version for Android/iOS.

Incorporate geospatial & satellite data for land mapping.

Support regional languages for broader adoption.

🏁 Conclusion

This project demonstrates how machine learning and data-driven intelligence can revolutionize agriculture.
By predicting inputs, yield, and profitability, the system bridges the gap between traditional farming and smart precision agriculture — making farming more sustainable and profitable.

📜 References

Afzal H. et al., Incorporating Soil Information with Machine Learning for Crop Recommendation, Scientific Reports, 2025.

Jabed M.A. et al., Crop Yield Prediction in Agriculture: A Review of ML & DL Approaches, Heliyon, 2024.

Iniyan S., Jebakumar R., Smart Mobile Application for Crop Yield Prediction, JMM, 2022.

Gosai D. et al., Crop Recommendation System using ML, 2021.

Streamlit Documentation – docs.streamlit.io

Scikit-Learn Documentation – scikit-learn.org
