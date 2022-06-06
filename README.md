# EDA-Capstone-Project-
Telecom Churn Analysis capstone project 1 
# Problem Statement 
• Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation.The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription.

• Explore and analyze the data to discover key factors responsible for customer churn and come up with ways/recommendations to ensure customer retention.

• Churn is major problem in any industry such problem is also observed in telecom industry. In given data we are looking for churn analysis for given data we first perform EDA and then by comparing various elements such as rates, voice mail, voice messages, international calls etc. By means of doing this analysis we can go for conclusion where is churn rate is high why customers are leaving. For a telecom industry it is very hard to acquire new customers so they should focus on how to retain existing customers.If the churn rate of company is 50% then the company will be going to shut in two years. As company with churn rate 25% then it will shut in four years so Churn is the major factor to be taken in consideration.

• As we know creating new customer is not easy in telecom industry so we have to focus on existing customers.

• For Telecom churn analysis problem can be defined as:

• Customers Churn 

• In this we have to look into the problems why customers are leaving.

• For different states churn rate is different.
  
• Dependent variable is Churn in the data set.

• Finally we have to look for Customer satisfaction.

# Feature Engineering 
Applied feature engineering to all the variables to see the behaviour of the customer towards company. With the help of Heat map we reduced highly co-related features, with VIF.Digging into data we understand that 

• There is no null value in the data set. 

• In state column there are total 51 unique states. 

• Total 20 columns with values such as float, integer, Boolean and object data type.

• Dependent variable should be considered as Churn.

• Graphical representation according to various columns and with manipulation of columns.
# Relation between Churn and Others 
• From heat map we can conclude that Total day minutes directly co-related to Total day charge, Total evening minutes directly co-related to Total evening charge, Total night minutes directly co-related to Total night charge, Total international minutes directly co-related to Total international charge.

• There is not more but some what co-relation between Total day minutes and Churn, Total day charge and churn, Customer service calls and churn.

# Conculision 

• From the given data and after performing EAD and comparison with the all the elements we say that there are some factors which company should taken care in consideration.

• States with high percentage of Churn are not approaching towards costumer service center. Instead when port request is put by some customers customer service should approach them.

• There is mix match churn rate for voice mail plans and voice mail messages.

• People with international plan who use more international minutes are moving towards churn.
• Due to high day charges people who use day minutes more are moving towards churn. As of that we would like to suggest take fix price for all types of times or lower the charges for day and increase for evening and night.

• For a telecom company it is necessary to approach towards customers on ground level and within certain period of time launch new schemes.

• States where customers churn rate is high increase advertisement in that area and increase customer service centers.   

# References 
[1] “Heterogeneous ensemble stacking with minority upliftment (HESMU) for churn prediction on imbalanced telecom data” by K. Sivasaankar Karuppaiah, N.P. Gopalan Palanisamy Materials today : Proceedings xxx (xxxx) xxx.

[2] “Churn prediction on huge telecom data using hybrid firefly based classification” By Ammar A. Q. Ahmed ⇑ , Maheswari D. Egyptian Informatics Journal xxx (2017) xxx-xxx

[3] “Customer Churn Prediction in Telecommunication Sector using Rough Set Approach” By Adnan Amina , Sajid Anwara , Awais Adnana , Muhammad Nawaza , Khalid Alawfib , Amir Hussainc , Kaizhu Huangd Neurocomputing, http://dx.doi.org/10.1016/j.neucom.2016.12.009

[4] “Applying data mining to telecom churn management” By Shin-Yuan Hung a , David C. Yen b,  Hsiu-Yu Wang Expert Systems with Applications 31 (2006) 515–524


Any suggestions are welcomed...


