# PromoHub-Machine-Learning-Models
📌 Project Overview

PromoHub is a centralized platform for verified promotions, roadshows, and business listings, designed to reduce fraud and improve trust in digital promotions.
This repository contains the machine learning models developed to support intelligent decision-making, fraud detection, and analytics within the PromoHub ecosystem.

All models are developed locally using Jupyter Notebooks and later integrated into the PromoHub backend as AI microservices.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Objectives of the ML Module

The machine learning component of PromoHub aims to:

Detect fraudulent or misleading promotions

Identify spam or phishing-like promotional content

Score promotions and businesses based on risk

Provide data-driven insights for platform analytics

Support admin verification workflows with AI assistance

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧠 Models Being Developed
1️⃣ Promotion Fraud Detection Model

Purpose:
Identify potentially fraudulent or deceptive promotions before or after publication.

Key Features:

Promotion description text

Offer validity period

Business verification status

Historical reports on the promotion

Click-to-view anomalies

Techniques:

Classification (Random Forest / Logistic Regression)

Feature engineering on structured promotion data

Class balancing (e.g. SMOTE)

Output:

Fraud probability score

Binary classification (Fraud / Legitimate)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2️⃣ Spam & Phishing Content Detection (Text-Based)

Purpose:
Detect spam-like or phishing promotional messages submitted by businesses.

Key Features:

Promotion title

Description text

URLs embedded in promotions

Techniques:

NLP preprocessing (tokenization, stopword removal, TF-IDF)

Supervised learning (Naive Bayes / Random Forest)

Trained on public spam/phishing datasets and adapted to PromoHub context

Output:

Spam probability score

Risk label (Low / Medium / High)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4️⃣ Promotion Performance Analytics Model

Purpose:
Provide insights into how promotions perform over time.

Metrics Analyzed:

Views

Click-through rate (CTR)

Conversion estimates

Reporting frequency

Use Cases:

Business analytics dashboards

Platform-wide statistics

Trend analysis for admins

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Tools & Technologies

Python

Jupyter Notebook

pandas, numpy

scikit-learn

imbalanced-learn (SMOTE)

matplotlib / seaborn

joblib / pickle (model persistence)



























