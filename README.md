# Harinderjeet Singh
## Machine Learning & Data Science Portfolio

📍 Edmonton, AB | 🎓 NorQuest College - CMPT  
🔗 [Live ML Demo](https://banffgroup6app.streamlit.app) | 💼 [LinkedIn](#) | 📧 [Email](#)

---

## 👋 About Me

Machine Learning practitioner specializing in **applied AI solutions**, **computer vision**, and **predictive analytics**. I build end-to-end ML pipelines from data preprocessing through production deployment, with expertise in cloud platforms, advanced ML frameworks, and MLOps practices.

**Currently:** Developing production-ready ML systems at NorQuest College CMPT program  
**Focus Areas:** Supervised Learning, Deep Learning, Computer Vision, Explainable AI

---

## 🚀 Featured Projects

### 🎯 1. Intelligent Traffic & Parking System for Banff National Park
**Production ML System | Streamlit Deployment | Random Forest**

[🔗 Live Demo](https://banffgroup6app.streamlit.app) | [📊 View Code](#)

<img src="assets/img/banff-dashboard.png" alt="Banff Dashboard" width="600"/>

**The Challenge:** Predict parking demand and optimize traffic flow for 144K+ traffic records and 795K+ parking transactions across 7 routes and 20+ facilities in Banff National Park.

**My Solution:**
- Built production-grade Random Forest model achieving **R² = 0.76**
- Deployed interactive Streamlit app with 5 features: real-time predictions, XAI analysis, RAG chatbot
- Discovered counterintuitive insight: parking demand peaks at 11 AM during *optimal* traffic flow

**Impact:**
- Enables dynamic pricing strategies (95% digital transactions)
- Provides actionable insights for park administrators
- Identified Route 7&8 as major bottleneck (12.3 mph vs Route 10 at 24 mph)

**Tech Stack:** Python, scikit-learn, SHAP, Streamlit, pandas, matplotlib

**Key Features:**
- ✅ Real-time predictions with confidence intervals
- ✅ SHAP-based explainable AI analysis
- ✅ Interactive dashboard with temporal pattern analysis
- ✅ Natural language query chatbot (RAG)

**Lessons Learned:**
- Resolved data leakage issue (R² = 1.0 → 0.76) through rigorous feature validation
- Temporal features account for 56% of predictive power
- Hour-of-day is dominant predictor (25% importance)

---

### 🌍 2. NPRI Industrial Emissions Forecasting
**Environmental Data Science | 522K Records | Random Forest MAE = 75.27**

[📊 View Analysis](#) | [📈 Presentation](https://github.com/yourusername/npri-emissions)

<img src="assets/img/npri-trends.png" alt="Emissions Trends" width="600"/>

**The Challenge:** Predict emissions and waste from key Canadian industries (oil sands, mining, manufacturing, electricity, sewage) over 5-year horizon.

**My Approach:**
- Processed 522,908 industrial records with 24 features (2005-2022 data)
- Applied advanced outlier handling using **winsorization** (reduced max from 235,991 to 1,487 tonnes)
- Engineered aggregate features: Total_Releases, Total_Treatment
- Used PCA for dimensionality reduction and feature selection

**Results:**
- **Random Forest selected:** MAE = 75.27 (vs Decision Tree 77.42, Linear Regression 161.47)
- Identified Manufacturing as dominant sector (45.7% of records)
- Discovered 50.9% reliance on Published Emission Factors

**Tech Stack:** Python, scikit-learn, pandas, PCA, matplotlib, seaborn

**Key Insights:**
- Releases declining 2005-2015, spike 2018-2020
- Treatment volumes surged 2018-2022 (potential policy impact)
- Engineering estimates account for 20.1% of reporting

---

### 🎮 3. Hydrogen Vehicle Challenge - Educational Game
**Game Development | Python Pygame | Western Canada Infrastructure**

[🎮 Play Demo](#) | [💻 Source Code](#)

<img src="assets/img/hydrogen-game.png" alt="Game Screenshot" width="600"/>

**The Concept:** Interactive educational game teaching hydrogen infrastructure deployment through gameplay. Players build charging stations, manage fuel resources, and deploy 5,000 hydrogen vehicles across Western Canada.

**Game Features:**
- 3 vehicle types (Car, Truck, Taxi) with unique fuel dynamics
- 4 real regions: Edmonton, Calgary, Vancouver, Prince Rupert
- Real infrastructure: NorQuest College, MacEwan, U of A, Rogers Place
- Strategic fuel management (collect cells, build Level 1-3 stations)
- Obstacles: blocked roads, detours, environmental hazards

**Educational Value:**
- Teaches resource management and strategic planning
- Based on real "5000 Hydrogen Vehicle Challenge" by Edmonton Global
- Demonstrates clean energy adoption challenges
- Tracks CO₂ emissions prevented in real-time

**Tech Stack:** Python, Pygame, Sprite Animation, Event Handling

**Impact:**
- Gamifies learning about hydrogen infrastructure
- Connects gameplay to actual policy goals (net-zero emissions)
- Encourages problem-solving for clean energy deployment

---

### 🧱 4. LEGO Detection & Counting System
**Computer Vision | Deep Learning | Faster R-CNN mAP@0.5 = 0.78**

[📷 View Results](#) | [🤖 Model Weights](#)

<img src="assets/img/lego-detection.png" alt="LEGO Detection" width="600"/>

**The Challenge:** Automated detection, counting, and classification of LEGO pieces using both classical computer vision and deep learning approaches.

**Two-Phase Approach:**

**Phase 1: Classical Computer Vision (OpenCV)**
- Thresholding segmentation (90% piece separation)
- Canny edge detection for boundary identification
- HSV color-based segmentation (85% color classification)

**Phase 2: Deep Learning (Faster R-CNN)**
- Transfer learning with ResNet50 backbone
- Trained on 33 annotated images (5 classes: red, blue, yellow, green, white)
- Achieved **mAP@0.5 = 0.78** (industry standard metric)
- Handles overlapping pieces with NMS (Non-Maximum Suppression)

**Tech Stack:** Python, PyTorch, torchvision, OpenCV, NumPy

**Performance:**
- Detection accuracy: 92%
- Color classification: 95%
- Inference time: ~200ms per image
- Handles 30+ pieces per image

**Key Innovations:**
- FPN (Feature Pyramid Network) for small object detection
- HSV color space + deep features for color ambiguity resolution
- Production inference pipeline with visualization

---

## 🛠️ Technical Skills

### Machine Learning & AI
![Python](https://img.shields.io/badge/Python-Expert-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Advanced-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Intermediate-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-Intermediate-red)

- **Supervised Learning:** Regression, Classification, Ensemble Methods (Random Forest, XGBoost)
- **Deep Learning:** CNNs, Transfer Learning, Object Detection (Faster R-CNN, YOLO)
- **Computer Vision:** OpenCV, Image Segmentation, Feature Extraction
- **Explainable AI:** SHAP, Permutation Importance, Partial Dependence Plots

### Data Science & Analytics
- **Data Processing:** pandas, NumPy, data cleaning, feature engineering
- **Visualization:** matplotlib, seaborn, Plotly
- **Statistical Analysis:** Hypothesis testing, correlation analysis, time series
- **Big Data:** Handling 500K+ record datasets

### MLOps & Deployment
- **Cloud Platforms:** Streamlit Cloud, Google Colab
- **Version Control:** Git, GitHub
- **Model Serving:** REST APIs, Streamlit apps
- **Containers:** Docker (basic)

### Programming
- **Python** (Advanced): 3 years experience
- **SQL** (Intermediate): Complex queries, window functions
- **R** (Basic): Statistical analysis

---

## 📊 Project Metrics

| Project | Dataset Size | Model | Key Metric | Status |
|---------|-------------|-------|------------|--------|
| **Banff Parking** | 939K records | Random Forest | R² = 0.76 | ✅ Deployed |
| **NPRI Emissions** | 522K records | Random Forest | MAE = 75.27 | ✅ Complete |
| **Hydrogen Game** | 4 regions | Python/Pygame | 5000 vehicles | ✅ Playable |
| **LEGO Detection** | 33 images | Faster R-CNN | mAP = 0.78 | ✅ Complete |

---

## 🎓 Education

**NorQuest College** - Edmonton, AB  
*Computer Modeling and Simulation Technology (CMPT)*  
Expected Graduation: 2025

**Relevant Coursework:**
- CMPT 3835: Work Integrated Learning II (ML Production Systems)
- CMPT 3520: Machine Learning II (Deep Learning, Computer Vision)
- CMPT 2400: Data Analytics (Statistical ML, Feature Engineering)
- CMPT 2021: Game Development (Python, Pygame)

**Academic Achievements:**
- 24-page Goal Setting & Performance Tracking document
- AutoML comparative analysis (H2O AutoML, TPOT)
- Production deployment of ML applications

---

## 💡 What I Bring

### Technical Excellence
✅ Production-ready ML pipelines from data to deployment  
✅ Advanced feature engineering (27+ variables in Banff project)  
✅ Rigorous model validation (resolved R²=1.0 data leakage)  
✅ Industry-standard evaluation metrics (mAP, IoU, SHAP)

### Problem-Solving
✅ Counterintuitive insights (parking demand during low-traffic periods)  
✅ Multi-phase strategies (classical CV → deep learning)  
✅ Real-world applications (environmental policy, traffic optimization)

### Communication
✅ Technical documentation for both developers and stakeholders  
✅ Interactive dashboards and visualizations  
✅ Professional presentations with speaking notes

---

## 🎯 Career Goals

Seeking opportunities in:
- **Machine Learning Engineer:** Production ML pipelines, MLOps, model deployment
- **Data Scientist:** Predictive analytics, statistical modeling, business insights
- **Computer Vision Engineer:** Object detection, image processing, deep learning
- **Applied AI Researcher:** Explainable AI, model interpretation

**Interested Industries:**  
Transportation & Logistics | Environmental Science | Manufacturing | Clean Energy

---

## 📫 Get In Touch

- 💼 **LinkedIn:** [linkedin.com/in/yourprofile](#)
- 📧 **Email:** your.email@example.com
- 🐙 **GitHub:** [github.com/yourusername](https://github.com/yourusername)
- 🌐 **Live Demo:** [Banff ML App](https://banffgroup6app.streamlit.app)

---

## 📝 Recent Blog Posts

*Coming soon: Technical deep-dives into my projects*

- 📊 "Resolving Data Leakage in Production ML Models"
- 🚗 "Predicting Parking Demand: A Case Study from Banff"
- 🤖 "Building Production-Ready Object Detection Systems"
- 🎮 "Gamifying Clean Energy Education"

---

## 🏆 Certifications & Training

- AutoML Frameworks (H2O AutoML, TPOT, AutoGluon)
- Explainable AI (SHAP, LIME, Interpretable ML)
- Agile Project Management
- Technical Writing for Data Science

---

*Portfolio last updated: December 2024*  
*Made with ❤️ using GitHub Pages*

---

## 🔍 Keywords

Machine Learning, Data Science, Computer Vision, Deep Learning, Python, scikit-learn, PyTorch, TensorFlow, OpenCV, Streamlit, Random Forest, XGBoost, Faster R-CNN, YOLO, SHAP, Explainable AI, MLOps, Predictive Analytics, Object Detection, Feature Engineering, Model Deployment, Production ML, Edmonton, Alberta, Canada
