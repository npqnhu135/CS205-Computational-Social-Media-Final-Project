# 📱 Impact of TikTok on ADHD Symptoms
*Computational Social Media Final Project - Fulbright University Vietnam*

## 📌 Project Overview
This project is the final assignment for the **Computational Social Media** course at Fulbright University Vietnam, under the guidance of **Professor Dr. Phan Thanh Trung**. 

The research focuses on evaluating the impact of TikTok usage on the symptoms of Attention Deficit Hyperactivity Disorder (ADHD), particularly the **attention span** of adolescents and young adults.

## 🎯 Research Objectives
As TikTok becomes increasingly prevalent and addictive among regular users, understanding its impact on mental health is necessary to cultivate healthy and responsible user practices. While there are many studies on social media in general, there is limited statistical research focusing on the correlations between ADHD symptoms and TikTok usage. 

This project aims to fill this gap by collecting and analyzing real-world data regarding users' **time spent**, **usage behaviors**, and **self-reported ADHD symptoms**.

---

## 🛠 Methodology
- **Data Collection:** An online survey yielding **201 valid responses** from TikTok users.
- **Data Preprocessing & Visualization:** - Removed invalid observations (e.g., non-TikTok users).
  - Mapped categorical time spent and symptom frequencies to numerical variables (e.g., converting "Under 30 mins" to 0.5 hours).
  - Calculated composite metrics: `ADHD_score`, `attention_score`, `impulsivity_score`, and `impact_score`.
- **Statistical Analysis:** Utilized descriptive statistics, Analysis of Variance (ANOVA), and correlation tests to identify patterns in user behavior.

---

## 📊 Key Findings
- Daily TikTok usage is significantly linked to increased attention difficulties and diminished focus.
- The specific period of the day users choose to scroll TikTok also has a measurable effect on their attention span.
- **Future Implications:** There is a crucial need to promote media literacy education, raise screen-time awareness, and introduce design nudges that encourage mindful app usage.

---

## 📁 Repository Structure
- 📄 `CSM - GROUP 1 - FINAL PROJECT.ipynb`: Jupyter Notebook containing the Python source code for data preprocessing, statistical analysis, and data visualization.
- 📄 `Computational_Social_Media_Final_Report_Group 1.pdf`: The detailed final research paper.
- 📄 `CSM - GROUP 1 - FINAL PROJECT.pdf`: The project presentation slide deck.
- 📄 `ksatfile.xlsx` *(Dataset - Hidden for privacy reasons)*: Raw data extracted from Google Forms.

---

## 💻 Technologies Used
- **Programming Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Statistics & Machine Learning:** `scipy`, `statsmodels`, `scikit-learn`
- **Environment:** Google Colab / Jupyter Notebook
