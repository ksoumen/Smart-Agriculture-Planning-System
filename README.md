# 🌾 Precision Farming System for Resource and Profit Optimization

### 🎓 Final Year B.Tech Project | Computer Science and Business System  
**Academy of Technology, Hooghly**  
**Under the guidance of:** Dr. Dilip Kumar Maity  

---

## 👨‍💻 Developed By
- **Soumen Karmakar** — *Data Collection, Dataset Analysis & Preprocessing*  
- **Sourish Saha** — *Model Development & Streamlit App*  
- **Niladri Biswas** — *Testing & Integration*  
- **Ujjal Samanta** — *Documentation & Research*  
- **Sakshi Kahar** — *Report Compilation*  

---

## 📖 Project Overview

Farming today faces the challenge of balancing **resource efficiency** and **profitability** amidst changing environmental conditions.  
Our project, **“Precision Farming System for Resource and Profit Optimization”**, uses **Machine Learning** to help farmers make **data-driven decisions** on:

- How much **fertilizer and pesticide** to use  
- Which **crop** to plant based on soil and climate  
- What **yield and profit** to expect  

The system integrates trained ML models into an easy-to-use **Streamlit web interface**, offering personalized recommendations and profit projections.

🔗 **Live Demo:** [farm-prediction-model.streamlit.app](https://farm-prediction-model.streamlit.app/)  
📂 **Source Code:** [GitHub Repository](https://github.com/ksoumen/Precision-Farming-System)

---

## 🚀 Key Features

- 🌱 Predicts **fertilizer and pesticide requirements**  
- 🌾 Suggests **optimal crops** for given soil and weather  
- 💰 Estimates **yield, cost, and profit** in real-time  
- 📊 Provides **data-driven insights** for resource management  
- 💻 Offers a **Streamlit-based user interface** accessible to all farmers  
- ⚡ Uses **ensemble ML models** (Random Forest, Gradient Boosting, KNN, SVM) for accuracy  

---

## 🧠 Machine Learning Models Used

| Task | Algorithm | Metric | Performance |
|------|------------|---------|--------------|
| Fertilizer Prediction | Random Forest Regressor | RMSE | ~8.25 |
| Pesticide Prediction | Gradient Boosting Regressor | RMSE | ~8.50 |
| Yield Prediction | Random Forest | RMSE | ~8.25 |
| Crop Recommendation | SVM / KNN Classifier | Accuracy | 97.6% |

---

## 🧬 Datasets Used

### **Dataset 1 – Agriculture Resource Optimization**
- **Records:** 1,450  
- **Features:** Crop Type, Season, Soil Type, N, P, K, pH, Temperature, Humidity, Rainfall  
- **Targets:** Fertilizer Used (tons), Pesticide Used (kg), Yield (tons)  
- **Source:** Aggregated from agricultural data repositories and government datasets  

### **Dataset 2 – Crop Recommendation Dataset**
- **Records:** 2,550  
- **Features:** N, P, K, Temperature, Humidity, pH, Rainfall  
- **Target:** Crop Type (29 classes — cereals, pulses, fruits, cash crops)

🧩 **Your Role:**  
You handled **data collection, preprocessing, and analysis**, ensuring:  
- Removal of inconsistencies and missing values  
- Label encoding of categorical variables  
- Feature engineering (NPK ratio, temperature-humidity index)  
- Exploratory Data Analysis (EDA) and correlation study  

---

## ⚙️ System Workflow

Data Collection → Preprocessing → Model Training → Evaluation → Streamlit Integration → Prediction & Profit Analysis

### 🧩 Architecture Diagram
+---------------------------+
| User Input (Streamlit) |
+---------------------------+
|
v
+---------------------------+
| Data Preprocessing Layer |
+---------------------------+
|
v
+---------------------------+
| ML Models (Regression & |
| Classification) |
+---------------------------+
|
v
+---------------------------+
| Yield & Profit Output |
+---------------------------+


---

## 🧰 Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python 3.8+ |
| **Frontend / UI** | Streamlit |
| **ML Libraries** | Pandas, NumPy, Scikit-Learn |
| **Visualization** | Matplotlib, Seaborn |
| **Deployment** | Streamlit Cloud |
| **Version Control** | Git & GitHub |

---

## 💻 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/ksoumen/Precision-Farming-System.git

# Navigate into the project directory
cd Precision-Farming-System

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

Then open the local server (usually http://localhost:8501
) in your browser.

---
```

## 🧮 Example Prediction

**Input Example:**
- Crop: Tomato
- Soil Type: Loamy
- Season: Zaid
- N = 45, P = 38, K = 42
- Temperature = 27°C, Humidity = 70%, Rainfall = 110mm
- Prices: Fertilizer ₹25/kg, Pesticide ₹40/kg, Crop ₹20/kg

**Predicted Output:**
- Fertilizer Required: 5.38 tons
- Pesticide Required: 2.71 kg
- Predicted Yield: 40.39 tons
- Estimated Profit: ₹6,73,000

## 📈 Results Summary

- Random Forest Regressor: RMSE ≈ 8.25
- Gradient Boosting: Accuracy up to 99%
- SVM Classifier: Accuracy 97.6%
- Demonstrated potential for input cost savings and yield optimization

## 🖼️ Project Preview
- Input Page	Results Page

	(Add screenshots from your Streamlit app in the assets/ folder)

## 🔮 Future Enhancements

- 🌦️ Integrate real-time weather and soil sensor APIs
- 🛰️ Add satellite & geospatial data for land analysis
- 📱 Develop mobile version (Android/iOS)
- 🧩 Introduce LSTM-based seasonal forecasting
- 🗣️ Support for regional languages for local farmers

## 🏁 Conclusion
This project demonstrates how machine learning and agricultural data analytics can revolutionize modern farming.
By combining historical data, environmental parameters, and real-time predictions, the system enables precision farming that improves yield, reduces costs, and promotes sustainable agriculture.

## 👥 Project Team

**Name**	**Role**
- **Soumen Karmakar**	Data Collection, Dataset Analysis & Preprocessing
- **Sourish Saha**	Model Development & Streamlit UI
- **Niladri Biswas**	Testing & Integration
- **Ujjal Samanta**	Documentation & Evaluation
- **Sakshi Kahar**	Research & Reporting
- **Guide:** Dr. Dilip Kumar Maity	Academy of Technology, CSBS Department

## 📚 References

- H. Afzal et al., “Incorporating Soil Information with Machine Learning for Crop Recommendation,” Scientific Reports, 2025.
- Md. A. Jabed, M. A. A. Murad, “Crop Yield Prediction in Agriculture,” Heliyon, 2024.
- S. Iniyan, R. Jebakumar, “Smart Mobile App for Crop Yield Prediction,” JMM, 2022.
- D. Gosai et al., “Crop Recommendation System using Machine Learning,” Academia.edu, 2021.
- Streamlit Documentation
- Scikit-Learn Documentation

