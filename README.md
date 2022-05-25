# ScorePrediction
Prediction of Domain Reputation Score

This project was developed as a part of course work for Introduction to Data Science. The code was developed by a team of three members.

Problem Statement: 
There have been many prior works on assessing the University Reputation and its impact on the students. In this project, we attempt to design an algorithm that predicts reputation score of the university based on the domain (Engineering, Business, Law). This would help students to choose the best fit as per their competency. The scope of this project is limited to predicting the law reputation score. The similar idea can be extended to other domains as well.

Data set:
To predict the domain reputation score, we have used the "University Statistics" data-set that was sourced from "Kaggle" along with "Law School Data-set" sourced from "publiclegal". The University Statistics Data-set has 23 attributes out of which only 4 attributes were having an impact on the Engineering Reputation Score: Acceptance rate, Avg-sat score, Tuition fees and Avg GPA. "Law school data-set" consisted of 3 sub files consisting of - Law school ranking, Tuition and Salary. We have post-processed these files to generate a single data frame having only relevant values. The attributes includes Acceptance Rate, SAT Score, Avg-GPA and Tuition that had substantial amount of impact on the reputation score which is to be predicted.

Exploratory Data Analysis:

<img width="640" alt="acceptanceToSatScorePlot" src="https://user-images.githubusercontent.com/99711349/170152442-33bac744-ebb9-4edf-b8c2-3b36382ee94b.png">

 
<img width="666" alt="employerToSalaryPrivatePlot" src="https://user-images.githubusercontent.com/99711349/170152098-4173df43-83b8-48bf-9e1d-05d6134aff32.png">
  

<img width="666" alt="employerToSalaryPublicPlot" src="https://user-images.githubusercontent.com/99711349/170152248-5d87ce1b-480b-422b-af9b-34c6b5fbbbe0.png">


Installation:
The code was developed using Jupyter Notebook and hence requires Python, Jupyter Notebook and the required Python packages running this notebook. Most of the in-built Python packages were used for the development of this code.
Required Python Packages:
1. Sklearn
2. Keras
3. Matplotlib
4. Seaborn

Results:The results generated for the law prediction score were as expected, because the Recurrent Neural Network model gave us values of the test data set which predicted the reputation score of the Engineering schools. We have visualized the reputation score data points of both Engineering and Law data-sets in scatter plots that gives a clear idea of the projections done by the Recurrent Neural Network model.
<img width="504" alt="DS_Project_Result_projection" src="https://user-images.githubusercontent.com/99711349/170147513-82d31a47-a149-4c1c-ae22-474e6070bb8d.png">

Future Scope:
To progress with this model, if there is a relevant data-set that contains attributes dependent on the respective domains, we will be able to train the model and classify the Universities into 3 classes: Good, Average and Bad. Example: In University Statistics data-set, assuming the data has a unique attribute that defines the engineering attribute such as "engineering knowledge" and law data-set has an attribute like "court points”. Then it would possible for us to segregate/classify the Universities into different classes based on these attributes in a better way. 

Conclusion:
The Prediction of the Domain Score based on the available attributes generated expected results. The scope of the project was limited to generating the domain score for the law schools but the project can be extented to multiple domains if their is relevant dataset available for the classification.
