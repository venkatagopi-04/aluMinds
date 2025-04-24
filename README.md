# AluMinds 🔍⚙️  
**Prediction and Optimization of Aluminium Wire Rod Physical Properties using AI/ML**

## 💡 Project Overview
**AluMinds** is a smart web-based system designed to predict and optimize the physical properties of aluminum wire rods—**UTS (Ultimate Tensile Strength), Elongation, and Conductivity**—based on dynamic casting parameters. This project was developed for the **Smart India Hackathon 2024** and is backed by real-world industrial data from **National Aluminium Company Limited (NALCO)**.

The system empowers engineers and supervisors with:
- Accurate **predictions** of wire rod properties  
- Intelligent **reverse predictions** (input suggestion based on desired output)  
- A user-friendly **dashboard interface**  
- **Optimization insights** for improved productivity and quality

---

## 🚀 Features
- 🔮 **Machine Learning Predictions**: Trained using Random Forest for reliable and interpretable outputs  
- 🔁 **Reverse Prediction Engine**: Suggests casting parameters based on target physical properties  
- 📊 **Interactive Dashboard**: Built using the **MERN stack** (MongoDB, Express, React, Node.js)  
- 📈 **Historical Logs**: View and analyze past predictions and optimizations  
- 🛠️ **Form Optimization**: Dual-column, compact forms for efficient data input  
- 📌 **Industrial Integration Ready**: Can be adapted into real-time factory pipelines  

---

## 🧠 Tech Stack
- **Frontend**: React.js (with Tailwind CSS for styling)  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (with separation of prediction & optimization using a `type` field)  
- **Machine Learning**: Python (scikit-learn - RandomForestRegressor)  
- **Model Deployment**: Flask (serving `.pkl` model)  
- **Visualization**: Matplotlib, Custom Graph Components  

---

## 🧪 ML Model Details
**Input Features**:
- Al%, Cu%, Mg%, Ag%  
- Casting Temperature  
- Cooling Water Temperature  
- Casting Speed  
- Cast Bar Entry Temperature  
- Emulsion Temperature  
- Emulsion Pressure  
- Emulsion Concentration  
- Rod Quench Water Pressure  

**Target Variables**:
- UTS (MPa)  
- Elongation (%)  
- Conductivity (S/m)  

**Models Used**:
- Random Forest Regressor  
- Reverse model using MultiOutputRegressor  

---




## 🧑‍💼 Team AluMinds
Built by a passionate team of AI/ML enthusiasts and developers for Smart India Hackathon 2024.  


---
## 🏆 Recognition
- 🥇 **Shortlisted by NALCO** for innovative AI-based solution
- 🥈 **National Runner-up** at **Smart India Hackathon 2024**


---


