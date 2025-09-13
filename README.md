# 🚔 Crime Pattern Analysis and Prediction – Using Machine Learning and Data Mining Techniques

## 📌 Overview  
This project applies **Machine Learning (ML)** and **Data Mining** to analyze crime records and predict future crime trends.  
It helps identify **crime hotspots**, classify crime types, and generate insights that can assist law enforcement in **predictive policing** and **resource allocation**.

## 🎯 Objectives  
- Classify crime types using ML models.  
- Detect crime hotspots with clustering techniques.  
- Visualize patterns with heatmaps and charts.  
- Provide predictive insights for better decision-making.  

## 🗂️ Dataset  
- **Source**: Kaggle Crime Dataset (2020–present)  
- **Size**: 10K+ records  
- **Features**: Crime type, location, date/time, community area, arrest status, etc.  
- **Preprocessing**: Missing value handling, label encoding, scaling, feature extraction  

## ⚙️ Methodology  
1. **Data Preprocessing** – Cleaning, encoding, scaling.  
2. **Exploratory Data Analysis (EDA)** – Heatmaps, victim age/gender, crime by area.  
3. **Clustering (Unsupervised ML)** – K-Means to detect hotspots.  
4. **Classification (Supervised ML)** –  
   - Random Forest (93.75% accuracy)  
   - Support Vector Machine (92.25% accuracy)  
   - Logistic Regression  
   - Naive Bayes  
   - AdaBoost, XGBoost, KNN  
5. **Association Rule Mining** – Apriori algorithm for discovering hidden relationships.  

## 📊 Results  
- ✅ **Random Forest** achieved **93.75% accuracy**  
- ✅ **SVM** achieved **92.25% accuracy**  
- ✅ Hotspots visualized with **Seaborn heatmaps**  
- ✅ K-Means revealed spatial and temporal clusters of crimes  
- ✅ Apriori uncovered associations between crime type, time, and location  

## 🛠️ Tech Stack  
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Plotly, XGBoost, mlxtend  
- **Tools**: Jupyter Notebook, Streamlit (prototype)
  
## 🧾 CitationS 
Dhanya Ratna Madhuri, Kommineni Chandhana, Dr. Sheela Jayachandhran
Crime Pattern Analysis and Prediction Using Machine Learning and Data Mining Techniques
VIT-AP University, 2025
## 🚀 How to Run  
Clone this repo and install dependencies:  
```bash
git clone https://github.com/your-username/Crime-Pattern-Analysis-and-Prediction.git
cd Crime-Pattern-Analysis-and-Prediction
pip install -r requirements.txt
