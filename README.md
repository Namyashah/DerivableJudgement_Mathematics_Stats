## 📷 Screenshots
> ![ScreenShot](images/Screenshot%202025-08-11%20100228.png)  

# 📊 Derivable Judgement: A Statistical Decision-Making Model

## 📌 Overview
This project demonstrates a step-by-step, manual statistical decision-making process using real healthcare data.  
The main focus is to showcase how data cleaning, hypothesis testing, and relationship analysis can help in making better healthcare decisions.  

Unlike typical automated analysis, this project emphasizes:
- Manual computation of statistical formulas  
- Real-time healthcare-inspired problem statements  
- Interpretation of results based on Null (H₀) and Alternate (H₁) hypotheses

---

## 🩺 Dataset Description
- Domain: Healthcare  
- File: `healthcare_dataset_2000.csv`  
- Size: ~2000 rows × multiple health indicators  
- Example Attributes:
  - Age, Gender
  - Diesease type
  - Recovery time
  - Medical test scores  
- Data Cleaning Steps:
  - Removed missing or duplicate entries  
  - Converted data types for consistency  
  - Standardized measurement units (if applicable)  
  - Checked and fixed outliers where necessary  

---

## 🧮 Statistical Methods Applied

### 1️⃣ Descriptive Statistics
- Mean,Variance, Standard Deviation  
- Helps understand central tendency and spread of healthcare metrics.

### 2️⃣ Hypothesis Testing
Performed manually, then verified with Python libraries:
- T-test: Compare two groups (e.g., Treatment A vs. Treatment B recovery times)  
- Z-test: Used for large sample size comparisons (e.g., average cholesterol level before & after a diet plan)  
- Chi-Square Test: Check association between categorical variables (e.g., Smoking habits vs. Disease occurrence)  
- ANOVA: Compare more than two group means (e.g., Recovery time across three different drugs)  

### 3️⃣ Relationship Analysis
- Correlation: Measures how strongly two variables move together  
- Covariance: Directional relationship between variables  

---

## 🎯 Real-Time Healthcare Problem Examples
For each statistical method, a Null Hypothesis (H₀) and Alternate Hypothesis (H₁) are stated.

Example:
- Scenario: Does a new treatment significantly reduce patient recovery time compared to the current treatment?
  - H₀: The new treatment does not significantly change recovery time.  
  - H₁: The new treatment significantly reduces recovery time.  
- Applied Test: Independent T-test  
- Outcome: Decision to accept or reject H₀ based on calculated p-value.

---

## 🛠️ Tools & Libraries Used
- Python 🐍 — Main programming language  
- NumPy — Numerical operations & manual statistical calculations  
- Pandas — Data manipulation, cleaning, and preparation  
- SciPy — Hypothesis testing and statistical methods  
- (and other libraries as needed for additional analysis)  

---

## 📜 Methodology Flow
1. Data Cleaning → Prepare the healthcare dataset for analysis  
2. Formulate Hypotheses → Define H₀ & H₁ for each test  
3. Perform Manual Calculations → Step-by-step derivations using statistical formulas  
4. Verify Using Python → Confirm results with `scipy.stats` and other libraries  
5. Interpret Results → Explain the meaning of the results in real-world healthcare terms  

---

## 📊 Results Summary (Placeholder)
> (You can fill this after running all tests — include p-values, confidence intervals, and key decisions)  
- Example: "The Chi-Square test revealed a statistically significant relationship between smoking habits and heart disease occurrence (p < 0.05)."  
- Example: "ANOVA indicated no significant difference in recovery times between the three tested drugs (p > 0.05)."

---

## 📂 Project Structure
```
├── healthcare_dataset_2000.csv      # Cleaned healthcare dataset
├── Theoretical Founddation.pdf      # Question And Answer Written In Notes
├── Statistical_DecisionModel.ipynb  # Jupyter Notebook with code & analysis
├── README.md                        # Project Documentation
```

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Namyashah/DerivableJudgement_Mathematics_Stats.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas scipy
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Statistical_DecisionModel.ipynb
   ```
---

## 💡 Future Improvements
- Add regression analysis (Linear & Logistic) for predictive modeling  
- Create an interactive dashboard (using Plotly or Dash)  
- Automate report generation from statistical results  

---

## ❤️ Acknowledgements
- Python Open Source Community  
- Healthcare researchers whose real-world problems inspired test scenarios  
- Statistical pioneers for hypothesis testing methods

---
