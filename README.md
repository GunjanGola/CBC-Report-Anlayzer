# CBC-Report-Anlayzer
CBC Report Analyzer is a machine learning-based system that analyzes Complete Blood Count parameters and predicts health severity while providing model explanations using SHAP. The goal is to make ML predictions more interpretable for healthcare-related decision support.
Problem Statement:
Medical reports contain multiple parameters that are difficult for non-experts to interpret. This project aims to analyze CBC parameters and identify important factors contributing to severity predictions using explainable machine learning.
Technologies Used :
Python
Pandas
NumPy
Scikit-learn
SHAP
Matplotlib
Seaborn
Jupyter Notebook
Results :
Model used : XGBoost
Accuracy : 95.16%
FEATURE IMPORTANCE
=========================
           Feature  Importance
9   PLATELET COUNT    0.256019
1      HAEMOGLOBIN    0.254651
2              TLC    0.119376
10           H.C.T    0.085444
0           GENDER    0.061868
13         M.C.H.C    0.042019
3        POLYMORPH    0.029669
8              RBC    0.028028
12           M.C.H    0.027393
4      LYMPHOCYTES    0.025963
11           M.C.V    0.024513
5      EOSINOPHILS    0.024464
6        MONOCYTES    0.020593
7        BASOPHILS    0.000000
