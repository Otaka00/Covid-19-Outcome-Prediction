# Covid-19-Outcome-Prediction
This is a team project completed by 2 contributors: Maryam Mohamed and myself.
The jupyter notebook is considered to be an application on supervised learning models using libraries as Numpy, Matplotlib and Scikit-Learn. The data used in this project will help to identify whether a person is going to recover from coronavirus symptoms or not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO).

The data.csv dataset has daily level information on the number of affected cases, deaths and recovery from 2019 coronavirus. The data is already cleaned and preprocessed.

The dataset contains 14 major variables that will be having an impact on whether someone has recovered or not, the description of each variable are as follows:
1. Country: where the person resides
2. Location: which part in the Country
3. Age: Classification of the age group for each person, based on WHO Age Group Standard
4. Gender: Male or Female
5. Visited_Wuhan: whether the person has visited Wuhan, China or not
6. From_Wuhan: whether the person is from Wuhan, China or not
7. Symptoms: there are six families of symptoms that are coded in six fields.
13. Time_before_symptoms_appear:
14. Result: death (1) or recovered (0)

The objective is to design different classifiers to the predict the outcome (death/recovered) when a new person is admitted to the hospital. 
We achieved to design the following classifiers:
1. K-Nearest Neighbors
2. Logistic Regression
3. Naïve Bayes (due end of week 11)
4. Decision Trees
5. Support Vector Machines (due end of week 14)

We also compared the performance of all classifiers using different metrics such as the precision, recall, F1-score, and ROC/AUC curves.
