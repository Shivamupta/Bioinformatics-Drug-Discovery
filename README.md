# Computational Drug Discovery for Alzheimer's Disease 💊

This project is an end-to-end Machine Learning pipeline designed to predict potent inhibitors for the **Acetylcholinesterase (AChE)** enzyme, which is a key target for Alzheimer's disease treatment.

## 🚀 Project Overview
- **Goal:** To identify potential drug candidates using Quantitative Structure-Activity Relationship (QSAR) modeling.
- **Target:** Human Acetylcholinesterase (ChEMBL220).
- **Model:** Random Forest Regressor.
- **Tech Stack:** Python, ChEMBL API, PaDEL-Descriptor, Scikit-Learn, LazyPredict.

## 📂 Project Structure
The project is divided into 5 parts:
1. **Data Collection:** Retrieving bioactivity data from ChEMBL.
2. **Data Preprocessing:** Cleaning, labeling, and calculating pIC50.
3. **Descriptor Calculation:** Generating PubChem Fingerprints using PaDEL.
4. **Model Building:** Training a Random Forest model.
5. **Model Comparison:** Benchmarking against 30+ ML algorithms.

## 📊 Key Results
- **Model Accuracy ($R^2$):** ~0.60
- **Top Algorithm:** Random Forest Regressor proved to be robust for high-dimensional chemical data.

## 🛠️ How to Run
These notebooks are designed to run on **Google Colab**.
1. Open the `.ipynb` files in Colab.
2. Run the cells sequentially.
3. Ensure `padel.zip` and `padel.sh` are downloaded in Part 3.

---
**Authors:** Shivam Gupta & Yash Yadav
**Institute:** J.C. Bose University of Science & Technology, YMCA
