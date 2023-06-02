# Glioma-Grade-Classification
XGBoost Binary Classification for Glioma Grading

# Glioma Grade Classification
### Approach
- Data cleaning and transformation
- XGBoost model
- 10-Fold cross validation while training 
### Description (from the website):

- Dataset link: https://archive-beta.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset

Gliomas are the most common primary tumors of the brain. They can be graded as LGG (Lower-Grade Glioma) or GBM (Glioblastoma Multiforme) depending on the histological/imaging criteria. Clinical and molecular/mutation factors are also very crucial for the grading process. Molecular tests are expensive to help accurately diagnose glioma patients.  

In this dataset, the most frequently mutated 20 genes and 3 clinical features are considered from TCGA-LGG and TCGA-GBM brain glioma projects.

The prediction task is to determine whether a patient is LGG or GBM with a given clinical and molecular/mutation features. The main objective is to find the optimal subset of mutation genes and clinical features for the glioma grading process to improve performance and reduce costs.

### Reference
Tasci,Erdal, Camphausen,Kevin, Krauze,Andra Valentina & Zhuge,Ying. (2022). Glioma Grading Clinical and Mutation Features Dataset. UCI Machine Learning Repository. https://doi.org/10.24432/C5R62J.
