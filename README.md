# 📊 Product Placement and Impulse Buying Behaviour

## A Study on the Influence of Product Placement on Impulse Buying Behaviour Among College Students in Retail Stores

![SPSS](https://img.shields.io/badge/Analysis-IBM%20SPSS-blue)
![Excel](https://img.shields.io/badge/Data-Microsoft%20Excel-green)
![Research](https://img.shields.io/badge/Project-Research%20Methodology-orange)

---

## 📌 Project Overview

This project examines the influence of product placement on impulse buying behaviour among college students in retail stores.

Primary data was collected through a structured questionnaire and analysed using **IBM SPSS Statistics**. The study uses statistical techniques to examine relationships, predictive effects, and differences between selected variables.

A total of **50 responses** were collected for the study.

---

## 🎯 Research Objectives

- To study the influence of product placement on impulse buying behaviour.
- To examine the relationship between product placement and impulse buying behaviour.
- To analyse selected factors associated with impulse buying behaviour.
- To apply statistical techniques to test the research hypotheses.
- To interpret the statistical results in the context of the research problem.

---

## 📋 Data Collection

The data was collected using a structured questionnaire.

### Sample Information

| Particular | Details |
|---|---|
| Sample Size | 50 respondents |
| Data Collection Method | Structured Questionnaire |
| Study Population | College Students |
| Analysis Software | IBM SPSS Statistics |
| Significance Level | 5% |
| Questionnaire Variables | 30 study variables |

The questionnaire also included demographic information such as **Age, Gender and Year of Study**.

---

## 📊 Statistical Analysis

The following statistical techniques were used:

| No. | Statistical Technique | Variables |
|---|---|---|
| 1 | Pearson Correlation | Q7 & Q19 |
| 2 | Spearman Rank Correlation | Q13 & Q20 |
| 3 | Linear Regression | Q11 → Q19 |
| 4 | Multiple Regression | Q7, Q11 & Q17 → Q19 |
| 5 | One-Sample T-Test | Q30 |
| 6 | Paired-Samples T-Test | Product Placement Score & Impulse Buying Score |

---

## 🔍 Variable Description

| Variable | Description |
|---|---|
| Q7 | Frequency of attractive product displays catching attention |
| Q11 | Frequency of purchasing a product after noticing prominent placement |
| Q13 | Frequency of exceeding planned shopping budget |
| Q17 | Frequency of promotional displays making respondents examine a product |
| Q19 | Number of impulse purchases in a typical month |
| Q20 | Frequency of regretting an impulse purchase |
| Q30 | Overall influence of product placement on impulse buying behaviour |

### Likert Scale

The opinion-based questions use the following scale:

| Value | Response |
|---:|---|
| 1 | Strongly Disagree |
| 2 | Disagree |
| 3 | Neutral |
| 4 | Agree |
| 5 | Strongly Agree |

---

## 📈 Analysis Results

### 1. Pearson Correlation

**Variables:** Q7 and Q19

- Pearson Correlation (r): **-0.014**
- Significance (p): **0.925**
- Sample Size (N): **50**

The result indicates a very weak negative relationship between the two variables. The relationship was not statistically significant at the 5% significance level.

---

### 2. Spearman Rank Correlation

**Variables:** Q13 and Q20

- Spearman Correlation (ρ): **-0.101**
- Significance (p): **0.486**
- Sample Size (N): **50**

The result indicates a very weak negative relationship between the variables. The relationship was not statistically significant.

---

### 3. Linear Regression

**Dependent Variable:** Q19  
**Independent Variable:** Q11

- R: **0.268**
- R²: **0.072**
- Adjusted R²: **0.052**
- F: **3.699**
- p: **0.060**

Regression equation:

**Q19 = 1.808 + 0.236(Q11)**

The model was not statistically significant at the 5% level.

---

### 4. Multiple Regression

**Dependent Variable:** Q19  
**Independent Variables:** Q7, Q11 and Q17

- R: **0.281**
- R²: **0.079**
- Adjusted R²: **0.019**
- F: **1.313**
- p: **0.282**

Regression equation:

**Q19 = 1.968 − 0.003(Q7) + 0.262(Q11) − 0.089(Q17)**

The overall regression model was not statistically significant at the 5% level.

---

### 5. One-Sample T-Test

**Variable:** Q30  
**Test Value:** 3

- Mean: **3.06**
- Standard Deviation: **0.956**
- t: **0.444**
- df: **49**
- p: **0.659**

The result did not show a statistically significant difference from the neutral value of 3.

---

### 6. Paired-Samples T-Test

The test compared:

- Product Placement Score
- Impulse Buying Score

| Measure | Product Placement | Impulse Buying |
|---|---:|---:|
| Mean | 2.94 | 2.92 |
| Standard Deviation | 0.45 | 0.50 |

Paired-samples t-test:

- Mean Difference: **0.02**
- t: **0.29**
- df: **49**
- p: **0.776**

The difference between the two scores was not statistically significant.

---

## 📌 Key Findings

Based on the statistical analyses conducted at the 5% significance level:

- The Pearson correlation between Q7 and Q19 was not statistically significant.
- The Spearman correlation between Q13 and Q20 was not statistically significant.
- The linear regression model using Q11 to predict Q19 was not statistically significant.
- The multiple regression model using Q7, Q11 and Q17 to predict Q19 was not statistically significant.
- Q30 did not show a statistically significant difference from the neutral value of 3.
- The paired-samples t-test did not show a statistically significant difference between the Product Placement Score and Impulse Buying Score.

---

## 🛠️ Tools & Technologies

- **IBM SPSS Statistics** – Statistical analysis
- **Microsoft Excel** – Data preparation and dashboard
- **Google Forms** – Questionnaire and data collection
- **Microsoft Word** – Project documentation

---

## 📁 Repository Structure

```text
spss-product-placement-impulse-buying/
│
├── README.md
│
├── questionnaire/
│   └── Questionnaire.pdf
│
├── data/
│   └── SPSS_Project_Responses.xlsx
│
├── spss-analysis/
│   └── SPSS_Project_Analysis.sav
│
├── report/
│   └── SPSS_Project_Report.pdf
│
├── outputs/
│   ├── Pearson_Correlation.png
│   ├── Spearman_Correlation.png
│   ├── Linear_Regression.png
│   ├── Multiple_Regression.png
│   ├── One_Sample_T_Test.png
│   └── Paired_Samples_T_Test.png
│
└── dashboard/
    └── SPSS_Project_Dashboard.xlsx
