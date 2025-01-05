# Hearty by NutriComm

Empowering heart health through technology, **Hearty** is an innovative application that integrates machine learning and comprehensive health data to provide personalized cardiovascular disease (CVD) risk assessments and tailored dietary recommendations. Developed during a Data Science Bootcamp, this project combines advanced data science techniques with a user-centric approach to promote heart health.

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Project Files](#project-files)
- [Setup and Usage](#setup-and-usage)
- [Future Enhancements](#future-enhancements)
- [Acknowledgments](#acknowledgments)

---

## Overview

Cardiovascular disease is the leading cause of death globally, with modern lifestyles contributing to its prevalence. The Hearty app leverages machine learning models trained on NHANES (National Health and Nutrition Examination Survey) data to:

- **Identify CVD risk factors**.
- Provide **personalized nutrition advice**.
- Encourage actionable, heart-healthy lifestyle changes.

This project aims to bridge the gap in accessible, data-driven solutions for heart health management.

---

## Key Features

1. **CVD Risk Assessment**: Utilizes logistic regression and neural networks to predict individual cardiovascular disease risk based on health metrics and dietary habits.
2. **Personalized Nutrition**: Provides tailored dietary recommendations aligned with individual preferences and health needs.
3. **Adaptive Learning**: Models refine recommendations over time as more user data becomes available.
4. **Comprehensive Insights**: Combines demographic, dietary, clinical, and laboratory data for holistic health guidance.

---

## Technologies Used

- **Machine Learning**: Logistic Regression, Neural Networks (Keras with TensorFlow backend)
- **Data Analysis**: Python (Jupyter Notebook), Pandas, Scikit-learn, Matplotlib
- **Visualization**: Figma
- **App Prototyping**: Streamlabs OBS, QuickTime, iMovie
- **Development Tools**: Visual Studio Code, Excel

---

## Data Sources

This project uses data from:

- **NHANES**: Publicly available U.S. health and nutrition data combining interviews, physical exams, and laboratory results.

Data includes:

- Dietary intake (e.g., fruits, vegetables, processed meats).
- Demographics (e.g., age, gender, income).
- Health metrics (e.g., BMI, blood pressure, cholesterol levels).

---

## Project Files

- **Jupyter Notebook**: Core machine learning model code.
- **Video Presentation**: Demonstration of the front-end and back-end functionalities.
- **Neural Network Weights**: Pre-trained models for CVD risk and dietary recommendations.
- **Datasets**: NHANES-derived data used for model training and testing.
- **Excel Sheets**: Variable selection and extreme case studies.

---

## Setup and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/Hearty-NutriComm.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook 01_Jupyter_Notebook_NutriComm.ipynb
   ```
4. **Load Pre-Trained Models**:
   - `Neural_Network_Model_CVD_Weights_NutriComm.h5`
   - `Neural_Network_Model_Food_Weights_NutriComm.h5`
5. **Explore Front-End Prototypes**: Open Figma links or run the presentation video.

---

## Future Enhancements

- **Expand Dataset**: Integrate additional health datasets for broader demographic representation.
- **Enhance Models**: Incorporate emerging biomarkers and improve data quality.
- **Mobile App Development**: Build a full-fledged application for wider accessibility.
- **Interactive Features**: Include gamification for user engagement.

---

## Acknowledgments

This project was developed by **Mariane de Almeida Alves, Ryan Covill, Dongsuk Kim, and Christopher H. Kroll** as part of the Remote Bootcamp Data Science Track. We thank **NHANES**, **TechLabs**, and the open-source community for their invaluable resources and tools.

---

For further information, please contact the project team.
