# Predicting Heart Conditions with Classification Models - Cleveland UCI Data (Kaggle) ❤️‍🩹
In this project, we explore the application of various classification models to predict the presence or absence of heart disease based on a dataset acquired from Kaggle: [Cleveland UCI Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

### Features 

1. **age**: age in years
2. **sex**: sex (1 = male; 0 = female)
3. **cp**: chest pain type (0: typical angina; 1: atypical angina; 2: non-anginal pain; asymptomatic)
4. **trestbps**: resting blood pressure (in mm Hg on admission to the hospital)
5. **chol**: serum cholestoral in mg/dl
6. **fbs**: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. **restecg**: resting electrocardiographic results (0: normal; 1:having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV); 2: showing probable or definite left ventricular hypertrophy by Estes' criteria)
8. **thalach**: maximum heart rate achieved
9. **exang**: exercise induced angina (1 = yes; 0 = no)
10. **oldpeak** = ST depression induced by exercise relative to rest
11. **slope**: the slope of the peak exercise ST segment (0: upsloping; 1: flat; 2: downsloping)
12. **ca**: number of major vessels (0-3) colored by flourosopy
13. **thal**: 0 = normal; 1 = fixed defect; 2 = reversable defect

## Label
condition: 0 = no disease, 1 = disease

### Creators:
- Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbr
- Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
- Donor: David W. Aha (aha'@'ics.uci.edu) (714) 856-8779

# Utilizing K-Nearest Neighbors, Decision Trees and Random Forests
We aim to predict heart conditions using different classification models, including K-Nearest Neighbors (KNN), Decision Trees, and Random Forests. These models will help us understand the predictive power of different features and their impact on diagnosing heart disease.

## Example: (Unpruned) Decision Tree Model
Below is an example of an unpruned Decision Tree model visualized for this task:
![image](https://github.com/ghubnerr/heart-disease-cleveland-uci/assets/91924667/36d77382-d215-4621-92f1-f8679a4e92a7)
