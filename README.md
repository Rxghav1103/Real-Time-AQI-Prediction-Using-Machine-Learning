# 🌍 Real-Time AQI Prediction Using Machine Learning & OpenWeather API  

## 📌 Overview  
This project predicts the **Air Quality Index (AQI)** based on real-time air pollution data. It utilizes machine learning regression models trained on historical data to provide accurate AQI predictions. Users can enter a **city name or latitude & longitude** via an interactive **Streamlit web app**, which fetches the latest air pollution data from OpenWeather API and predicts AQI instantly.

---

## 🚀 Features  
✅ **Real-Time AQI Prediction** using trained ML models  
✅ **Interactive Streamlit UI** for seamless user experience  
✅ **Search by City Name or Coordinates** for flexibility  
✅ **Optimized ML Model** with hyperparameter tuning  
✅ **Live Air Pollution Data** from OpenWeather API  
✅ **Exported Model for Fast Inference**  

---

## 📂 Project Structure  
```
📁 AQI_Prediction
│── 📜 app.py                 # Streamlit UI & API integration
│── 📜 finalfile.ipynb         # Data processing & model training
│── 📜 requirements.txt        # Dependencies
│── 📜 gradient_boosting_model.joblib  # Trained ML model
```

---

## 🛠 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/AQI_Prediction.git
cd AQI_Prediction
```
### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit App  
```bash
streamlit run app.py
```

---

## 🔗 APIs Used  
- **[OpenWeather API](https://openweathermap.org/api/air-pollution)** – Fetches real-time air pollution data  
- **[OpenCage Geocoder](https://opencagedata.com/api)** – Converts city names to coordinates  

---

## 📊 How It Works  

### 🔹 **Step 1: Input Data**  
- Enter **City Name** (e.g., *New Delhi*)  
- Or input **Latitude & Longitude**  

### 🔹 **Step 2: Fetch Real-Time Data**  
- The app fetches live **air pollution data** from OpenWeather API  

### 🔹 **Step 3: Predict AQI**  
- The **Gradient Boosting Regressor model** predicts AQI based on pollutant levels  

### 🔹 **Step 4: Display Results**  
- The AQI score is displayed in the **Streamlit UI**  

---

## 🎯 Model Selection & Training  
- Multiple **regression models** were trained and evaluated  
- **Performance Metrics Used:**  
  - **Mean Squared Error (MSE)**  
  - **Mean Absolute Error (MAE)**  
  - **R² Score**  
- **Best Model:** **Gradient Boosting Regressor**  
- **Model Tuning:** Hyperparameters optimized for best performance  

---

## 🏆 Results  
- **Gradient Boosting Regressor** outperformed other models  
- It achieved the best results in terms of **MSE, MAE, and R² Score**  
- Model exported as `gradient_boosting_model.joblib` for fast inference  

---

## ⚡ Example Usage  
- **Search by City Name**  
  - Input: *New Delhi*  
  - Output: *Predicted AQI: 158.3*  

- **Search by Latitude & Longitude**  
  - Input: `Lat: 28.61, Lon: 77.23`  
  - Output: *Predicted AQI: 172.5*  

---

## 🔧 Future Enhancements  
- 🌟 Improve model accuracy with **larger datasets**  
- 📊 Add **AQI visualization graphs** for better insights  
- 🌎 Deploy using **Docker** & **FastAPI**  
- 📍 Include **historical AQI trends** for better analysis  

---

## 👨‍💻 Author  
Developed by **Raghavendra Bhargava** 🚀  

---

## ⭐ Like This Project?  
Give it a ⭐ on GitHub and contribute! 😊  
```

Now you can **copy-paste** this directly into your **README.md** file. 🚀 Let me know if you need modifications!
