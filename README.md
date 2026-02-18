# 🏡 Real Estate Intelligence Platform  
## End-to-End Machine Learning, Analytics & Recommendation System

A production-ready real estate intelligence platform that integrates **predictive modeling, geospatial analytics, and recommendation systems** into a unified, interactive web application.

🔗 **Live Application:**  
https://real-estates-g2f9.onrender.com  

---

## 📌 Executive Summary

This capstone project demonstrates the complete lifecycle of a real-world data science system:

- Data acquisition & preprocessing  
- Advanced feature engineering  
- Multi-model benchmarking  
- Explainable model selection  
- Hybrid recommendation engine  
- Geospatial visualization  
- Cloud deployment  

The platform enables users to:

- 📈 Predict property prices  
- 🗺️ Analyze market trends  
- 🏠 Discover similar properties  
- 📍 Identify optimal sectors based on landmark proximity  

---

# 🚀 Core Modules

---

## 1️⃣ Price Prediction Engine

An interactive prediction module where users input:

- Property Type  
- Sector  
- Bedrooms & Bathrooms  
- Balconies  
- Property Age  
- Built-up Area  
- Additional Features  

The system returns an estimated market price using a production-grade ML pipeline.

### 🔬 Model Benchmarking

The following models were evaluated:

- Linear Regression  
- Ridge Regression  
- LASSO  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost  
- Multi-layer Perceptron (MLP)  
- ElasticNet  
- K-Nearest Neighbors  
- Support Vector Regression (SVR)  

The final model was selected based on performance, generalization ability, and robustness.

### ⚙️ Pipeline Architecture

- Feature scaling  
- Ordinal Encoding  
- One-Hot Encoding  
- Target Encoding  
- Feature selection  
- Model inference layer  

---

## 2️⃣ Real Estate Analytics Dashboard

A data-driven visualization suite providing market intelligence.

### 📍 Sector Price per Sqft Geomap  
Interactive geospatial pricing analysis.

### ☁️ Features Wordcloud  
NLP-based amenity frequency visualization.

### 📈 Area vs Price  
Identifies pricing patterns and non-linear trends.

### 🛏️ BHK Distribution  
Bedroom configuration market share.

### 💰 BHK Price Comparison  
Comparative pricing insights across categories.

### 📊 Property Type Distribution  
Density comparison between flats and houses.

This module transforms raw property data into actionable insights.

---

## 3️⃣ Intelligent Recommendation System

A hybrid recommendation engine built using similarity modeling.

### 🏠 Similar Property Recommendations

- Cosine similarity-based matching  
- Feature-level comparison  
- Price proximity analysis  
- Amenity alignment  

### 📍 Landmark-Based Sector Recommendation

Users can:

- Select a preferred landmark  
- Receive nearby sector suggestions  
- View properties optimized by location  

This module integrates feature similarity with geographic intelligence to enhance decision-making.

---

# 🧠 Technical Architecture

## 📊 Data Acquisition
- Self-scraped dataset from real estate platforms  
- Unified houses and flats dataset  

## 🧹 Data Processing & Feature Engineering
- Missing value imputation  
- Outlier detection & removal  
- Feature normalization  
- Luxury score creation  
- Amenity aggregation  

## 🔎 Feature Selection Techniques
- Correlation Analysis  
- Random Forest Importance  
- Gradient Boosting Importance  
- Permutation Importance  
- LASSO Regularization  
- Recursive Feature Elimination  
- SHAP (Explainable AI)  

## 🤖 ML Pipeline Design
- Scikit-learn Pipeline  
- StandardScaler  
- OrdinalEncoder  
- OneHotEncoder  
- Target Encoding  
- Model abstraction layer  

---

# 🛠 Technology Stack

### Programming & ML
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  

### Visualization
- Plotly  
- Seaborn  
- Matplotlib  
- WordCloud  

### Application Layer
- Streamlit  

### Deployment
- Render (Cloud Hosting)  
- External model hosting  
- Cached model loading for performance optimization  

---

# 📦 Production Considerations

- Large model externalized to comply with GitHub size limits  
- Cached model loading to reduce cold start latency  
- Optimized for free-tier cloud memory constraints  
- Modular and scalable architecture  


---

# 📈 Key Highlights

- End-to-end ML system development  
- Real-world data scraping and cleaning  
- Multi-model benchmarking & explainability  
- Hybrid recommendation engine  
- Geospatial analytics integration  
- NLP-based amenity visualization  
- Cloud deployment  
