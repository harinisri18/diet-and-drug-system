# diet-and-drug-system

What we eat and drink is important at every stage of life, and it is never too early or too late to eat healthfully .Food is always central to the human life. Besides the air we breathe, food is the only 
physical matter, which humans take into the body. A growing proportion of the global population is becoming overweight or obese, leading to various diseases (e.g., diabetes, ischemic heart 
disease and even cancer) due to unhealthy eating patterns, such as increased intake of food with high energy and high fat.Everyone wants to keep them healthy and also fit and look good .Henceforth 
the diet and drug recommendation is of paramount importance to alleviate this problem.

There is a tamil saying which says "unave maranthu,marunthe unavu " that means ” food as a medicine , medicine as a food “and 
“Leave your drugs in the chemist's pot if you can heal the patient with food " but drugs have become part of our life too.

Being healthy means putting the right fuel into your body and having your internal engine run smoothly. Every meal that you consume influences the way that you feel one way or another so the 
more nutritious foods you choose, the healthier you will be.Nowadays, a vast amount of clinical data scattered across different sites on the Internet hinders users from finding helpful information 
for their well-being improvement. Besides, the overload of medical information (e.g., on drugs, medical tests, and treatment 
suggestions) have brought many difficulties to medical professionals in making patient-oriented decisions. These issues raise the need to 
apply recommender systems in the healthcare domain to help both, end-users and medical professionals, make more efficient and accurate health-related decisions.

On the Internet, where the number of choices is overwhelming, there is need to filter, prioritize and efficiently deliver relevant information in order to alleviate the problem of information overload, which has 
created a potential problem to many Internet users. Recommender systems solve this problem by searching through large volume of dynamically generated information to provide users with 
personalized content and services. 


Being healthy and eating better is something the vast majority of the population wants and doing so usually requires great effort. The working prototype accomplishes a Personalized Diet 
Recommendation System with the integration of Machine Learning Algorithms to recommend the right food at right time and with the 
right nutrition, calories, fat, etc. 

The goal of application is to provide a platform where users find their Nutritious food according to their personal health preferences according to their BMI and recommend food separately for weight 
loss and gain categories and build a behavior of living healthy life and I have also build the recommendation system wherein it helps to identify the suitable drug names that can be recommended for the diseases respectively.
A wide variety of ingredients, cultures and personal tastes makes decisions about what to eat a great problem. Many diseases that were previously thought of as hereditary are now seen to be 
connected to biological dysfunction related to nutrition.

Building a model to find out which drug might be appropriate for a future patient with the same illness for drug recommendation system. The features of this dataset are Age, Sex, Blood Pressure, 
and the Cholesterol of the patients, and the target is the drug that each patient responded to.
Polycystic Ovary Syndrome, or PCOS, is a health condition that affects about 10 million people in the world. The exact cause is unknown, but it is considered a hormonal problem. In order to solve 
this problem of PCOD and support the woman community, I have developed PCOD recommendation system and a predictive system by comparing 5 different Machine Learning models accuracy and 
finding the most efficient model and using it for a more precise diagnosis and partially developed an website with integrating these ideas together for girls and woman to get their inputs and be aware 
of their conditions along with diet and drug to be taken .

FLOW FOR PROJECT FOR MEAL AND DIET SYSTEM :

Data collection - data is collected by web scraping                  
Data processing - data is processed and required attributes are added to make demo datasets.            
User's profile generation by taking input from them .           
Initial recommendation on the basis of user's profile (Content  based,implemented by k-nearest neighbors).    
Recommendation based on similar profiles to users.   
Recommendation on the basis of users past/recent activity   
(Collaborative Memory based approach,implemented by K-nearest 
neighbors).  
The project aims at creating a personalized diet recommendation system based on the input of the user.The project uses custom created dataset containing values for nutrients and calories.User can input values named height,weight and age using a customized GUI built using python's Tkinter Library.Machine learning model was implemented using k-means clustering and random-forest classifer for clustering and classification of the food items.

FLOW FOR PROJECT FOR DRUG SYSTEM:
First Step: I've imported the patient's data set that has attributes about the patient and the most appropriate drug for them.     
Second Step: I've analyzed the data by checking its data quality: missing values, outliers, data format, etc. After this, I've visualized  the dataset to extract insights about the data.  
Third Step: After checking the data quality and visualizing the data set, I've have pre-processed the data set: converted categorical values to numerical values.  
Fourth Step: I've have then created two subsets from the orginal data set called: 
X_train: Used to train the Machine Learning Models  
X_test: Used to test the performance of the trained models     
Fifth Step: Trained 3 Classifier Models: Bagging Classifier and Decision Tree Classifier model. Checked the trained model's performance using the X_test 
set.  
Sixth Step: Since all the models performed really well and achieved an accuracy score of 100%, I chose decision tree classifier model and saved it in the pickle format using joblib.  
Seventh Step: Created a front-end app using HTML and CSS and integrated the pickle file with the app using the flask framework.I have 
stopped with building of front end .   

Thank you !
