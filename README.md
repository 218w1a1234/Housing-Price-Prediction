# 🏡 House Price Prediction API

## 📌 Project Overview
This project predicts house prices using **Machine Learning (Random Forest)** and serves predictions via a **FastAPI-based REST API**.

---

## 📂 Repository Structure
```
📂 House-Price-Prediction
 ├── 📄 train.py           # Python script for Model Training
 ├── 📄 app.py             # FastAPI Deployment Script
 ├── 📄 requirements.txt   # Required Libraries
 ├── 📄 README.md          # Documentation & Instructions
 ├── 📄 house_price_model.pkl  # Trained Model
 ├── 📄 preprocessor.pkl   # Feature Transformer (Scaler + OneHotEncoder)
 ├── 📄 housing.csv        # Sample Dataset (if permitted)
```

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Train the Model (If Not Already Trained)
```bash
python train.py
```

### 3️⃣ Run the API Locally
```bash
uvicorn app:app --host 0.0.0.0 --port 8000 --reload
```

---

## 🎯 API Endpoints

### **📍 `POST /predict`**
- **Request Format**
```json
{
  "features": [-119.57, 35.63, 28, 2636, 538, 1425, 500, 3.87, "INLAND"]
}
```
- **Response**
```json
{
  "Predicted House Price": 215000.75
}
```

---

## 🌐 Hosted API Link (If Deployed)
🔗 **[Your API Link Here]**  
(Use Render/AWS/GCP if deployed)

---

## 📌 Model Performance
| Metric  | Score |
|---------|------:|
| RMSE    | 48,500 |
| MAE     | 35,200 |
| R² Score| 85% |

---

### 📩 **Submission**
Once uploaded, **submit the GitHub link** to your assessment portal.

