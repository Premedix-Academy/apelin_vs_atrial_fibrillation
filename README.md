# Apelin vs atrial fibrillation
*Accompanying code for the Bohm et al. "Association between apelin and atrial fibrillation in patients with high risk of ischemic stroke" (submitted to Frontiers in Cardiovascular Medicine)*

## Abstract
### Background
Atrial fibrillation (AF) is associated with high risk of stroke preventable by timely initiation of anticoagulation. Currently available screening tools based on ECG are not optimal due to inconvenience and high costs. Aim of this study was to study the diagnostic value of apelin for AF in patients with high risk of stroke.
### Methods
We designed a multicenter, matched-cohort study. The population consisted of three study groups: a healthy control group (34 patients) and two matched groups of 60 patients with high risk of stroke (AF and non-AF group). Apelin levels were examined from peripheral blood.
### Results
Apelin was significantly lower in AF group compared to non-AF group (0.694±0.148 ng/ml vs. 0.975±0.458 ng/ml, p = 0.001) and control group (0.982 ± 0.060 ng/ml, p<0.001), respectively. Receiver operating characteristic (ROC) analysis of apelin as a predictor of AF scored area under the curve (AUC) of 0.658. Apelin’s concentration of 0.969 [ng/ml] had sensitivity = 0.966 and specificity = 0.467.
Logistic regression based on manual feature selection showed that only apelin and NT-proBNP were independent predictors of AF. Logistic regression based on selection from bivariate analysis showed that only apelin was an independent predictor of AF. A logistic regression model using repeated stratified K-Fold cross-validation strategy scored an AUC of 0.725 ± 0.131.
### Conclusions
Our results suggest that apelin might be used to rule out AF in patients with high risk of stroke.

## Keywords
Atrial fibrillation; Apelin; Biomarker; Electrical atrial remodeling; Ischemic stroke


## How to run
### Locally
(Requires python et al. already set up; tested with python3.7)
```bash
git clone https://github.com/jajcayn/apelin_vs_atrial_fibrillation.git
cd apelin_vs_atrial_fibrillation
pip install --upgrade -r requirements.txt
jupyter lab
```
