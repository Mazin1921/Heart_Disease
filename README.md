## 👍 Theory --> From Resorces 
1. problem statement
2. data
3. evaluation 
4. featuress

## 👩‍💗⚕ Predicting heart disease using machine learning

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.


We're going to take the following approach:


1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

 ## 1. Problem Definition
 Statement : Given clinical parameters about a patient, can we predict whether or not they have heart disease?

 ## 2. Data
The original data came from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease

There is also a version of it available on Kaggle. https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

## 3. Evaluation

If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.
## 4. Features
This is where you'll get different information about each of the features in your data. You can do this via doing your own research (such as looking at the links above) or by talking to a subject matter expert (someone who knows about the dataset).

## Create data dictionary

1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
    0: Typical angina: chest pain related decrease blood supply to the heart
    1: Atypical angina: chest pain not related to heart
    2: Non-anginal pain: typically esophageal spasms (non heart related)
    3: Asymptomatic: chest pain not showing signs of disease
4.   trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for    
5. chol - serum cholestoral in mg/dl
6. serum = LDL + HDL + .2 * triglycerides
   above 200 is cause for concern
7. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
    '  >126' mg/dL signals diabetes
8. restecg - resting electrocardiographic results
     0: Nothing to note
      1: ST-T Wave abnormality
        can range from mild symptoms to severe problems
        signals non-normal heart beat
    2: Possible or definite left ventricular hypertrophy
        Enlarged heart's main pumping chamber
9. thalach - maximum heart rate achieved
10. exang - exercise induced angina (1 = yes; 0 = no)



