# 🧪 A/B Testing: Digital Marketing Campaign Optimization

## 📌 Project Overview
This project evaluates the effectiveness of a digital marketing campaign using A/B testing methodology by comparing two user groups:

- **Ad Group**: Users exposed to product advertisements  
- **PSA Group**: Users exposed to public service announcements (control group)  

The main objective is to determine whether the advertising campaign significantly increases conversion rates and to uncover user behavior patterns for optimizing future marketing strategies.

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy (Data Manipulation)  
- **Statistical Analysis**: SciPy, Statsmodels (Z-Test, Hypothesis Testing)  
- **Visualization**: Matplotlib, Seaborn  

---

## 🔍 Data Analysis Workflow
1. **Data Loading**  
   Import marketing campaign dataset  

2. **Data Cleaning**  
   Validate data integrity and handle missing/invalid values  

3. **Exploratory Data Analysis (EDA)**  
   - Ad exposure distribution is **right-skewed** (avg ~21 ads)  
   - Sample imbalance detected:  
     - Ad Group: ~554K users  
     - PSA Group: ~23K users  

4. **Z-Test Assumption Checking**  
   - Independence of samples  
   - No duplicate users
   - Expected Successes (n × p)
   - Expected Failures (n × (1 − p))

5. **A/B Testing (Z-Test)**  
   Perform statistical significance testing on conversion rates  

6. **Time-Based Analysis**  
   Identify optimal days and hours for campaign performance  

7. **Conclusion & Recommendations**  
   Translate findings into business strategy  

---

## 📊 Hypothesis & Results
- **H₀**: No difference in conversion rate between Ad and PSA groups  
- **H₁**: Ad group has a higher conversion rate than PSA group  

### Key Findings:
- Ad Group conversion rate: **2.32%**  
- PSA Group conversion rate: **1.55%**  
- Result: **Statistically significant improvement**  

- **Peak Performance Time**:  
  Monday, **13:00 – 17:00**

---

## 💡 Strategic Recommendations
- Focus advertising budget on **weekday performance (Monday–Wednesday)**  
- Reduce spending during **low-performing periods (weekends & late night)**  
- Improve future experiments by ensuring **more balanced sample sizes** for higher accuracy  

---

## 📂 Project Files
https://github.com/Happy-Code-byFarhah/A-B-Testing-Marketing-Project/blob/main/AB%20Testing%20Project.ipynb

## 📊 Dataset
https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing
