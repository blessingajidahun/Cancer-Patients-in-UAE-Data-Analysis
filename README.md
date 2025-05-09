# Cancer Patients in UAE Data Analysis

I carried out analysis on  the sales dataset of the XYZ company, discovering trends and patterns and recommending steps that can be taken to increase sales.
## Project Objectives
To develop a machine learning model that classifies cancer patient data from the UAE into meaningful categories and clusters. The goal is to
gain deeper insights into patient profiles, improve diagnosis support, and uncover hidden patterns within the healthcare data.

## Dataset Used
<a href=https://github.com/blessingajidahun/Cancer-Patients-in-UAE-Data-Analysis/blob/main/_cancer_dataset_uae%20(1).csv>Dataset</a>
## Tools
- Python
- Matplotlib
- Seaborn
- Numpy
- Pandas
- Scikit-learn
- Jupyter noteboo

### In the data preparation phase, the following activities were performed;
- Data loading
- Data Validation
- Data cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)

EDA was performed in order to identify trends, patterns, and relationships. The following EDA were performed:
- Analysis of recovery rates over the years
- Analysis of recovery rate per cancer type
- Analysis of the impact of smoking status on patient outcomes
- Identification of top 5 most common cancer types and their respective recovery rates
### Supervised Machine Learning for Predictive Modeling
Machine learning models were built to predict the cancer stage (I, II, III, IV) based on the demographic features (i.e., age, gender, nationality and ethnicity), lifestyle features (i.e., smoking status) and medical history (i.e., comorbidities, cancer type, weight and height). To achieve this, different machine learning models such as Logistic Regression (Multinomial and Ordinal), Random Forest Classifier, KNeighborsClassifier, Support Vector Machine and XGBClassifier were employed. The final decisions were taken based on XGBClassifier, Ordinal Logistic Regression and Random Forest Classifier as they appeared to be more potent compared to other models.

### Unsupervised Machine Learning for Clustering
To identify hidden patterns and subgroups, support personalized treatment strategies and reveal patterns in patients' demographics and health factors, unsupervised machine learning algorithms were employed. This algorithm helped in clustering patients into similar groups. To achieve this, KMeans clsutering and Principal Component Analysis (PCA) were employed.

### Insights
- Age, Weight and Height appeared as the most important features for predicting cancer stage for Random Forest Classifier.
- Cancer type, Ethinicity and Comorbidities are the most important features for predicting cancer stage for Ordinal Logistic Regression and XGBClassifier
- Three clusters were uncovered. Cluster 0 consists mostly of middle-aged (averagely 45 years), East Asian, patients with lower body weight and predominantly non-smokers, treated mainly with surgery.Cluster 1 is younger (averagely 36 years), South Asian, heavier patients, non-smokers, undergoing immunotherapy. Cluster 2 is the oldest group (averagely 74 years) with lower weight and more likely to be former smokers.
### Recommendations
Based on the results, the following were recommended:
- Specific interventions for diverse cancer types should be developed
- Seeing that ethnicity is an important factor in cancer stages, culturally-sensitive interventions should be developed.
- Personalized care plans and resource allocation should be done in consideration of the clusters uncovered. for instance targeted interventions for older, underweight, former smokers should be developed in order to cater for the different patient-groups.
- Targeted cancer screening programs for high-risk populations (e.g., adults 65+, with low BMI, and smoking history) should be launched
