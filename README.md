# IBM AutoAI Customer Churn Prediction System (watsonx.ai)

## 🚀 Project Overview
This project demonstrates an end-to-end machine learning pipeline built using IBM watsonx AutoAI to predict customer churn for a telecom dataset. The system automatically builds, evaluates, and deploys machine learning models as a production-ready REST API.

---

## 🎯 Business Problem
Telecom companies need to predict which customers are likely to churn in order to reduce customer loss and improve retention strategies.

---

## 🏗️ Solution Architecture

Data → IBM Watson Studio (AutoAI)
     → Automated Feature Engineering
     → Model Training & Selection
     → Model Registry (Watson Machine Learning)
     → Deployment Space
     → REST API Endpoint

---

## 🧠 Tools & Technologies
- IBM watsonx.ai AutoAI
- IBM Watson Machine Learning
- IBM Cloud Deployment Spaces
- Python (Scikit-learn, Pandas)
- REST API
- Cloud Object Storage

---

## ⚙️ Key Features
- Automated ML pipeline generation using AutoAI
- Multiple model comparison (9 pipelines generated)
- Best model selection (Logistic Regression / Ensemble)
- Model versioning in IBM Model Registry
- Real-time REST API deployment
- Scalable cloud inference endpoint

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Features: contract type, tenure, monthly charges, services, etc.
- Target: Churn Value (0 = stay, 1 = churn)

---

## 🚀 Deployment
Model deployed using IBM Watson Machine Learning:

- Deployment Type: Online
- API Type: REST
- Status: Active

![ALT TEXT](assets/Screenshot(210).png)

![ALT TEXT](assets/Screenshot(211).png)

![ALT TEXT](assets/Screenshot(212).png)

![ALT TEXT](assets/Screenshot(213).png)

📈 Model Performance
9 AutoAI pipelines generated
Best model selected automatically
Optimized for accuracy
👨‍💻 Author

Fezekile Xalaba
AI Engineer | Machine Learning | IBM watsonx | Multi-Cloud (AWS, GCP, IBM)

📌 Key Learning Outcome

Built a production-ready AI system using IBM AutoAI with automated model selection and REST API deployment.
---

## 📡 API Usage Example

```json
{
  "input_data": [
    {
      "fields": ["tenure", "monthly_charges", "contract", "internet_service"],
      "values": [[12, 70.5, 1, 2]]
    }
  ]
}


