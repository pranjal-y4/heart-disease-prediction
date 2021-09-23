# Heart-Disease-Prediction

Overview

Machine Learning is used across many spheres around the world. The healthcare industry is no exception. Machine Learning can play an essential role in predicting presence/absence of Locomotor disorders, Heart diseases and more. Such information, if predicted well in advance, can provide important insights to doctors who can then adapt their diagnosis and treatment per patient basis.
An estimate by the World Health Organization, that over 17.9 million deaths occur every year worldwide because of cardiovascular disease, and of these deaths, 80% are because of coronary artery disease and cerebral stroke. The vast number of deaths is common amongst low and middle-income countries. Many predisposing factors such as personal and professional habits and genetic predisposition accounts for heart disease. Various habitual risk factors such as smoking, overuse of alcohol and caffeine, stress, and physical inactivity along with other physiological factors like obesity, hypertension, high blood cholesterol, and pre-existing heart conditions are predisposing factors for heart disease. The efficient and accurate and early medical diagnosis of heart disease plays a crucial role in taking preventive measures to prevent death.
Using machine learning, it detects hidden patterns in the input dataset to build models. It makes accurate predictions for new datasets. The dataset is cleaned and missing values are filled. The model uses the new input data to predict heart disease and is then tested for accuracy. In its most basic sense, machine learning uses programmed algorithms that learn and optimize their operations by analyzing input data to make predictions within an acceptable range. With the feeding of new data, these algorithms tend to make more accurate predictions.

Proposed Methodology


Dataset: 
We have used a dataset from the Machine learning repository. It comprises a real dataset of 300 examples of data with 14 various attributes (13 predictors; 1 class) like blood pressure, type of chest pain, electrocardiogram result, etc. 
<img width="604" alt="Screenshot 2021-09-23 at 8 38 32 PM" src="https://user-images.githubusercontent.com/85802579/134533554-42208a52-749c-4cb8-944b-5b798f522aca.png">


Data Pre-Processing: 
A real-world data generally contains noises, missing values, and maybe in an unusable format which cannot be directly used for machine learning models. Data preprocessing is required tasks for cleaning the data and making it suitable for a machine learning model which also increases the accuracy and efficiency of a machine learning model.
<img width="459" alt="Screenshot 2021-09-23 at 8 38 53 PM" src="https://user-images.githubusercontent.com/85802579/134533636-40064bdf-9f46-40e1-9715-f61e27e68724.png">


Algorithm used:  
Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes.
In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).

Model Building: 
The model building by dividing the dataset into training set and test set.We have logistic Regression model to achieve high accuracy.

Model Evaluation: 
Our model gives accuracy of 91%.

	<img width="586" alt="Screenshot 2021-09-23 at 8 39 14 PM" src="https://user-images.githubusercontent.com/85802579/134533701-6ca70b6b-a140-4315-abe0-6a79358e7f19.png"

Visualization

Comparing the risk of heart disease on different parameters. 


<img width="595" alt="Screenshot 2021-09-23 at 8 40 10 PM" src="https://user-images.githubusercontent.com/85802579/134533897-f2dbb37f-41e7-4944-8137-676970b9c3ae.png">

<img width="615" alt="Screenshot 2021-09-23 at 8 40 25 PM" src="https://user-images.githubusercontent.com/85802579/134533940-59f8b646-3f06-4fff-b346-a9e6e19cd00d.png">

<img width="595" alt="Screenshot 2021-09-23 at 8 40 40 PM" src="https://user-images.githubusercontent.com/85802579/134533999-5e6be7b9-bb8a-4bdd-81a0-34cd7b3383ae.png">
<img width="595" alt="Screenshot 2021-09-23 at 8 40 51 PM" src="https://user-images.githubusercontent.com/85802579/134534030-37d78ced-d6a2-4f26-aed6-5fa1c3ba3f39.png">

Heatmap-To find all features all positively correlated or negatively correlated.
<img width="682" alt="Screenshot 2021-09-23 at 12 46 25 AM" src="https://user-images.githubusercontent.com/85802579/134534097-fad0cb0b-008d-4ed8-acbd-35e52b5b5262.png">

Histogram- 
<img width="619" alt="Screenshot 2021-09-23 at 8 41 30 PM" src="https://user-images.githubusercontent.com/85802579/134534173-f782e8b9-c4e9-4cd5-a9cb-065194a0d6e3.png">


Implementation

1.<img width="563" alt="Screenshot 2021-09-23 at 8 42 25 PM" src="https://user-images.githubusercontent.com/85802579/134534319-8f7fa337-af0a-4204-863f-19aadac03509.png">


2.
<img width="559" alt="Screenshot 2021-09-23 at 8 42 37 PM" src="https://user-images.githubusercontent.com/85802579/134534362-91e39d7d-89d8-4406-a336-a85af9eab81b.png">

3.<img width="559" alt="Screenshot 2021-09-23 at 8 42 48 PM" src="https://user-images.githubusercontent.com/85802579/134534398-aaef7767-96e7-4bf3-861f-a77beca977bb.png">


4.<img width="559" alt="Screenshot 2021-09-23 at 8 43 11 PM" src="https://user-images.githubusercontent.com/85802579/134534473-cf8fd3dc-b00f-4763-8bd9-386ccbc1a97c.png">


5.<img width="559" alt="Screenshot 2021-09-23 at 8 43 34 PM" src="https://user-images.githubusercontent.com/85802579/134534551-2b7cf25b-b23a-4541-97c3-e840d4e72504.png">


6.<img width="559" alt="Screenshot 2021-09-23 at 8 43 45 PM" src="https://user-images.githubusercontent.com/85802579/134534575-68deb77b-62c6-4404-8d8a-ec5ac779c551.png">


7.<img width="534" alt="Screenshot 2021-09-23 at 8 43 55 PM" src="https://user-images.githubusercontent.com/85802579/134534603-0a924d5c-49af-4e3a-b056-5534164ddb96.png">



Conclusion

Men seem to be more susceptible to heart disease than women. Increase in Age, number of cigarettes smoked per day and systolic Blood Pressure also show increasing odds of having heart disease.
The model predicted with 91% accuracy. The model is more specific than sensitive.


