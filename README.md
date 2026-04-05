# 5.5 Project – Prescriptive Analytics and Final Project Submission

**Student Name:** Morgan Moore
**Student ID:** mormoo5363
**Course:** Data Analytics / Software Development
**Date:** 03/28/2026

---

## 📌 Project Overview

This final project builds on previous phases of data analysis by moving from descriptive and predictive analytics into **prescriptive analytics**. The goal is to simulate real-world interventions and evaluate how changes in key health factors impact the likelihood of stroke.

Using a machine learning model (Logistic Regression), this project analyzes how modifying actionable features such as Body Mass Index (BMI) and Stress Levels can influence predicted stroke outcomes.

---

## 📊 Objectives

* Identify actionable features from the predictive model
* Simulate intervention scenarios on high-risk patients
* Measure changes in predicted stroke probability
* Visualize before-and-after outcomes
* Provide data-driven recommendations for reducing stroke risk

---

## 🛠️ Technologies Used

* Python 3
* Jupyter Notebook
* Pandas
* Scikit-learn
* Matplotlib

---

## 📁 Files Included

* `Stroke_Prediction_Dataset.xlsx` – Dataset used for analysis
* `5.5_Project.ipynb` – Jupyter Notebook with simulation and results
* `README.md` – Project documentation

---

## ⚙️ Methodology

### Actionable Features

The analysis focused on two key actionable variables:

* **Body Mass Index (BMI)**
* **Stress Levels**

These features were selected because they can be modified through lifestyle changes, medical intervention, and behavioral adjustments.

---

### Intervention Simulation

A subset of high-risk patients (above median predicted stroke probability) was selected. The following interventions were applied:

* **BMI reduced by 10%**
* **Stress levels reduced by 5%**

The trained logistic regression model was then used to predict stroke probability before and after these interventions.

---

### Visualization

A scatter plot was created to compare:

* Predicted stroke risk before intervention
* Predicted stroke risk after intervention

This allowed for visual analysis of how effective the simulated changes were.

---

## 📈 Results & Insights

* Patients with higher initial stroke risk showed noticeable reductions after intervention.
* BMI reduction had a significant impact on lowering predicted stroke probability.
* Stress level adjustments also contributed to improved outcomes, though to a lesser extent.
* The greatest improvements were observed in patients with the highest baseline risk.

---

## 🔍 Key Findings

* Lifestyle-related factors such as BMI and stress play a critical role in stroke risk.
* Targeted interventions are most effective when applied to high-risk populations.
* Even small percentage changes in health metrics can lead to measurable improvements in predicted outcomes.

---

## 📌 Recommendations

### Individual-Level Interventions

* Promote weight management through diet and exercise programs
* Encourage stress reduction techniques such as therapy, meditation, or lifestyle adjustments

### Policy-Level Recommendations

* Implement public health programs focused on obesity prevention
* Expand access to mental health services
* Encourage workplace wellness initiatives
* Integrate preventative screening for BMI and stress in healthcare systems

---

## ⚠️ Limitations

* The model is based on logistic regression and may not capture complex relationships
* Simulated interventions assume linear impact, which may differ in real-world scenarios
* Additional variables could improve prediction accuracy

---

## ▶️ How to Run the Project

1. Open the Jupyter Notebook (`.ipynb`)
2. Install required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib openpyxl
   ```
3. Update dataset path if needed:

   ```python
   df = pd.read_excel("your_file_path_here.xlsx")
   ```
4. Run all cells to reproduce analysis and visualizations

---

## 📌 Conclusion

This project demonstrates how prescriptive analytics can be used to simulate real-world interventions and guide decision-making. By focusing on actionable features like BMI and stress levels, it is possible to reduce predicted stroke risk and inform both individual and public health strategies.

---

## 📎 Author

Morgan Moore
GitHub: https://github.com/AbsurdGem 

