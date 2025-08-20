# Exploratory Data Analysis (EDA) Notes 
# Eye Cancer Patients Record Project
August 15, 2025

## 1. Dataset Overview / Size
**Questions:** 
- How many patients are in the dataset?
- How many patients have each cancer type?
**Purpose:** Understand the dataset size, which is fundamental for context.

**Total Patients Recorded in This Dataset: 5000**

<p float="left">
<img src="Cancer_Type_Counts_Table.png" width="400"/>
<img src="cancer_type_percent.png" width="400">
---

## 2. Demographic Distribution
**Questions:**  
- What is the distribution of age, gender, and other demographics?  
- How many female, male, and other in the dataset?
- 

**Purpose:** Describe the population. Helps detect imbalances (like more males than females) which could affect analysis.

<p float="left">
<img src="age_distribution_patients.png" width="400"/>
<img src="age_distribution_patients_part2.png" width="400"/>
</p>

<p float="left">
<img src="age_group_patients.png" width="400"/>
<img src="distribution_cancertype_and_agegroups_patients.png" width="400"/>
</p>
---

## 3. Cancer Stage-Specific Counts
**Question:** 
- For each cancer type, how many patients are diagnosed at Stage IV?
- 

**Purpose:** To identify which cancer types are most frequently diagnosed at Stage IV. This helps focus the analysis on advanced-stage cases, informs prevalence, and guides sampling or treatment considerations.

<p float="left">
<img src="Cancer_Type_by_Stage_IV_table.png" width="400"/>
<img src="number_stage_by_cancer_type.png" width="400"/>
</p>

<img src="Stage_IV_by_Age_Group.png" width="400">
---

## 4. Survival Analysis / Outcome Exploration
**Questions:**  
- What is the average survival time for patients?  
- Which cancer type has the highest or lowest average survival time?  
- Does age affect survival time?  

**Purpose:** Explore relationships between patient features (age, cancer type) and outcomes (survival time).

<img src="averagesurvivaltime.png" width="600">
---

## 5. Cross-Tab / Group Comparisons
**Questions:**  
- How does gender distribution vary across cancer types?  
- How many patients at terminal stage for each cancer type?  

**Purpose:** Examine differences across groups (cancer type, gender, stage). Helps identify patterns or disparities.
