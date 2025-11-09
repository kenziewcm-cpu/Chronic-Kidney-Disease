Research Questions/Study Objectives:

This project aims to explore clinical and laboratory features associated with chronic kidney disease (CKD) and to identify key predictors that distinguish CKD from non-CKD individuals.
Specifically, we will address the following research questions:
1.Which clinical and biochemical indicators are significantly associated with CKD status?
2.How do comorbid conditions such as diabetes mellitus and hypertension influence the likelihood of CKD?
3.How does CKD risk differ across subgroups such as diabetic vs. non-diabetic individuals?
This analysis will use inferential statistics including hypothesis testing, contingency tables, Chi-square test, Fisher’s exact test, relative risk (RR), and odds ratio (OR).
4.Can we develop an interpretable statistical model to predict CKD status based on patient-level biomarkers?

Background and Rationale
Chronic Kidney Disease (CKD) is a progressive, irreversible condition affecting roughly 10% of the global population, often leading to end-stage renal disease and cardiovascular complications. Early detection relies on biochemical markers such as serum creatinine, blood urea, and urine albumin, which indicate renal filtration efficiency, yet their interpretation can be influenced by comorbidities like hypertension, diabetes, and anemia. This study employs a clinical dataset of CKD and non-CKD patients to statistically compare renal, hematologic, and comorbidity-related variables using t-tests, Wilcoxon tests, and chi-square analyses, aiming to identify markers most strongly associated with CKD. 
Recent research supports this multifactorial approach: Perkovic et al. (2024) and Kolligundla et al. (2025) emphasized urinary proteins and oxidative-stress biomarkers, Kume et al. (2024) highlighted metabolic dysregulation, Li et al. (2025) demonstrated the diabetes–CKD interplay, Zhang et al. (2025) linked gut virome shifts to renal inflammation, and Coleman et al. (2025) stressed evidence-based clinical management. Together, these findings justify integrating biochemical and comorbidity indicators to enhance diagnostic precision and risk stratification in CKD. 


Dataset description
The dataset used in this study is mainly about Chronic Kidney Disease (CKD) , including clinical records from patients evaluated for kidney function. 
The dataset contains approximately 400 patient observations and 24 variables (with NAs), including demographic information, clinical laboratory measurements, and diagnostic indicators.
The variables consist of both continuous laboratory values (e.g., blood urea) and categorical clinical conditions (e.g., hypertension). The outcome variable (classification) categorizes individuals as either CKD or not CKD. 
Data quality considerations include the presence of missing values and occasional non-standard or text-based entries (such as “ ”, and categorical labels).

This dataset is considered suitable for examining relationships between kidney disease diagnosis and selected biomarkers because it includes key physiological indicators known to be clinically linked to kidney function and the sample size (>400) and group size in the outcome variable (250, 150 respectively) is adequate for group comparison and regression modeling.
The variable names are clearly interpretable in a medical context, and is logically correlated (most are blood test results) allowing meaningful conclusions on risk factors and disease patterns drawn from the analysis.
