# 💧 Water Quality Prediction - RMS

**This project focuses on predicting multiple water quality parameters using machine learning techniques, specifically a MultiOutputRegressor wrapped around a RandomForestRegressor.**

Developed as part of a **one-month AICTE Virtual Internship sponsored by Shell in June 2025**, this project was a valuable learning experience in applying machine learning to real-world environmental challenges.

---

## 🌍 Overview

As a student passionate about data science and environmental issues, I undertook this project to explore how machine learning can contribute to water quality monitoring and pollution control.

Clean water is a vital global resource, and predicting water quality indicators can help detect contamination early and support timely interventions.

In this project, I:

- Collected and cleaned real-world water quality datasets  
- Applied supervised machine learning for **multi-target regression**  
- Built a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`  
- Evaluated model performance using key regression metrics  
- Explored different feature correlations and visualized data trends  
- Learned to fine-tune models for better generalization  

---

## 🔧 Technologies Used

- **Python 3.12**
- **Pandas, NumPy** – for data handling and preprocessing  
- **Scikit-learn** – for modeling and evaluation  
- **Matplotlib, Seaborn** – for data visualization  
- **Jupyter Notebook** – for experimentation and iterative development  

---

## 💡 What I Learned

- Building models for **multi-output regression**
- Handling missing values, normalization, and encoding techniques  
- Understanding the significance of **environmental datasets**  
- Evaluating models using **R² Score** and **Mean Squared Error (MSE)**  
- Communicating findings with clean, insightful visualizations  

---

## 🔬 Predicted Water Quality Parameters

The model was trained to predict multiple parameters that are commonly used to assess water quality, including:

- **NH4**
- **BOD5 (BSK5)**
- **Colloids**
- **O2**
- **NO3**
- **NO2**
- **SO4**
- **PO4**
- **CL**

---

## 📊 Model Performance

The model was evaluated using:

- **R² Score**  
- **Mean Squared Error (MSE)**  

🚀 The results were promising and showed good accuracy across most predicted parameters.

---

## 📎 Project Link

You can explore the full project notebook and model here:  
👉 [Click to view the model](https://drive.google.com/file/d/18RJzu35vyuMgpcAE590u1IaDvHY3-SWq/view?usp=sharing)

---

## 📚 Internship Details

- **Internship Type:** AICTE Virtual Internship  
- **Organization:** Edunet Foundation  
- **Sponsor:** Shell  
- **Duration:** June 2025 (1 month)  
- **Domain:** Machine Learning in Environmental Monitoring  

---

## 🙌 Acknowledgments

Grateful to **AICTE**, **Edunet Foundation**, and **Shell** for organizing this internship and giving students like me the opportunity to explore impactful real-world problems using technology.

---

## 🚀 Future Improvements

As I continue learning, I hope to:

- Try out other regressors (e.g., XGBoost, SVR)  
- Add automated hyperparameter tuning (GridSearchCV/RandomizedSearchCV)  
- Explore deep learning approaches for regression  
- Deploy the model as a web app using Streamlit or Flask  

---

_This project reflects my continuous learning journey in machine learning and environmental analytics._  
_I'm excited to keep improving and contributing to meaningful solutions!_
