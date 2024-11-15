# Multivariate Predictive Maintenance  
**Leveraging Multivariate Data for Enhanced Operational Efficiency**

## Project Overview  
This project, developed as part of an internship with Sand Technologies, focuses on creating a predictive maintenance system using multivariate data to enhance operational efficiency. The goal was to anticipate failures, improve safety, and reduce costs by leveraging machine learning and explainability techniques. The project culminated in the deployment of interactive dashboards for real-time monitoring.

---

## Problem Statement  
Modern industrial systems face significant challenges with unexpected equipment failures, leading to downtime and resource inefficiency. This project aimed to:  
- Proactively predict equipment failures using multivariate data.  
- Optimize maintenance schedules, balancing **proactive** and **reactive** strategies.  
- Integrate explainable AI for actionable insights and trust in model predictions.

---

## Data Summary  
The data used in this project consisted of:  
- **Errors:** Hourly logs of machine errors.  
- **Maintenance Events:** Records of component replacements categorized into proactive or reactive maintenance.  
- **Failures:** Events indicating failed components requiring replacement.  
- **Telemetry:** Hourly averages of key machine metrics like voltage, rotation, pressure, and vibration.  
- **Metadata:** Information about machine model types and ages.  

---

## Key Steps in the Project  

### 1. Data Preprocessing and Feature Engineering  
- **Errors Dataset:** One-hot encoding and error counts.  
- **Maintenance Dataset:** Time since last maintenance, cumulative counts, and maintenance intervals by machine age.  
- **Telemetry Dataset:** Ratio features, interaction features, and hourly statistics.  
- **Failures Dataset:** Binary failure indicators and time since last component failure.  

### 2. Modeling Approach  
A range of machine learning algorithms was implemented, including:  
- **LightGBM**  
- **XGBoost**  
- **Random Forest**  
- **Support Vector Machine (SVM)**  

### 3. Model Explainability  
To ensure transparency and trust, explainability tools were integrated:  
- **Feature Importance**  
- **SHapley Additive exPlanations (SHAP)**  
- **Local Interpretable Model-agnostic Explanations (LIME)**  

### 4. Model Performance  
The models achieved:  
- **Accuracy:** > 90%  
- **Precision:** > 97%  
- **Recall and F1-Score:** > 90%

---

## Deployment  
Interactive dashboards were developed for real-time monitoring and decision-making:  
- **Power BI Dashboard:** Visual insights into machine performance and failure predictions.  
- **Streamlit Application:** Web-based interface for exploring predictions and explainability outputs.

---

## Recommendations  
To ensure the long-term success of this system, the following recommendations were provided:  
- Implement a **feedback loop** for continuous improvement of models.  
- Explore **advanced model architectures** and dynamic updates.  
- Address **ethical considerations** to ensure compliance with regulations.  
- Conduct **training sessions** for stakeholders to maximize the value of the deployed system.

---

## Conclusion  
The Multivariate Predictive Maintenance project represents a significant step forward in leveraging data science for operational efficiency. By seamlessly combining human expertise with machine intelligence, the solution minimizes downtime, optimizes resource allocation, and lays the groundwork for sustainable industrial operations.

---

## Team
- **Sinothabo Zwane**
- **Ntebatse Rachidi** 
- **Kedijang Setsome** 
- **Hlawulekani Rikhotso**  
- **Albinah Hlongo** 
- **Kaya Dumasi** 
- **Kanyisa Nake** 

---

## Acknowledgments  
Special thanks to the Sand Technologies team for providing support and resources throughout this project.

