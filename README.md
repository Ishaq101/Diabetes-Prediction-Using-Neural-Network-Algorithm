# Diabetes-Prediction-Using-Neural-Network-Algorithm
Build diabetes detection model using Neural Network Algorithm


Background:<br>
As a AI Engineer in a consultant company, one of our client need a help to predict which patient is potential got diabetes or not. The client propose to build this smart detection using Deep Learning Algorithm.

Objectives:
1. Build smart detection for diabetes from given dataset (`dataset.csv`)
2. Do experimentation with Deep Learning Algorithm especially Neural Network Architect
    - narrow and shallow
    - narrow and wide 
    - deep and shallow
    - deep and wide
3. Do hyperparameter including Epoch, Batch Size, Learning Rate, and others then evaluate each experimentation using confusion matrix

<br><br>
About Dataset:<br>
This dataset comes from the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK). It focuses on diagnosing diabetes in Pima Indian women aged 21 and over. The data was carefully chosen from a larger collection, specifically including only female patients of Pima Indian heritage who were at least 21 years old.
<br><br>
<table>
    <thead>
      <tr>
        <th>Feature</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Pregnancies</td>
        <td>Number of times pregnant</td>
      </tr>
      <tr>
        <td>Glucose</td>
        <td>Plasma glucose concentration at 2 hours in an oral glucose tolerance test</td>
      </tr>
      <tr>
        <td>BloodPressure</td>
        <td>Diastolic blood pressure (mm Hg)</td>
      </tr>
      <tr>
        <td>SkinThickness</td>
        <td>Triceps skin fold thickness (mm)</td>
      </tr>
      <tr>
        <td>Insulin</td>
        <td>2-Hour serum insulin (mu U/ml)</td>
      </tr>
      <tr>
        <td>BMI</td>
        <td>Body mass index (weight in kg / (height in m)^2)</td>
      </tr>
      <tr>
        <td>DiabetesPedigreeFunction</td>
        <td>Diabetes pedigree function</td>
      </tr>
      <tr>
        <td>Age</td>
        <td>Age (years)</td>
      </tr>
      <tr>
        <td>Outcome</td>
        <td>Class variable (0 or 1) - 268 of 768 are 1, the others are 0</td>
      </tr>
    </tbody>
  </table>