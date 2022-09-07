# Recovery-prediction-covid-19-vaccination
A competitive race can be seen in pharma industry which has yielded into a remarkable progress and growth in bio-science field. SARS-Covid-19 vaccine doses are mostly provided to high risk individuals and older generation first, subject to immunity system. However uncertainty still remains over how long does these vaccine shots provides you the protection from the virus. Many temporary and life threatening side effects can be seen in individuals after vaccination drives, which creates a doubt in individuals mind to choose what’s best for them along with minimal adverse effects of vaccines.
# Objective of research project
The main objective of this research is to predict the recovery of patients from adverse side effects of covid-19 vaccination on humans that can help people and virologist  to choose the best composition of vaccines by analysing the vaccination data and responses from individuals who reported various side effects after having their doses. 
Based on ongoing research over findings ,this analysis can be helpful to analyse side effects of vaccination which can help virologists and pharmaceutical companies to create a composition based on most occurred  side-effects through available vaccines.
# Data Source Information
Dependent Variable  : RECOVD (Whether the participant recovered from the side effects of covid-19 vaccination or not)


Independent Variables for Research Analysis :

1.	SYMPTOM 1 : Primary symptoms (first reported symptom after vaccination)
2.	SYMPTOM 2 : Secondary Symptom 1 reported if any
3.	SYMPTOM 3 : Secondary Symptom 2 reported if any
4.	SYMPTOM 4 : Secondary Symptom 3 reported if any
5.	SYMPTOM 5 : Secondary Symptom 4 reported if any
6.	VAX _MANU : Name of vaccine manufacturer (Brand Names) 
7.	VAX_DOSE_SERIES : No. of doses received by the recipients
8.	VAX_ROUTE : This tells about the vaccine route administration

Abbreviation	Route
ID	Intradermal
IM	Intramuscular
SC	Subcutaneous
IN	Intranasal
PO	Per Oral
SYR	Needle and Syringe (Not Specified further)
OT	Other

9.	VAX_SITE : Anatomic Site where vaccination was administrated
10.	RECV_DATE : It refers to the receiving date of VAERS form information at information centre.
11.	STATE : Two digit postcode of US State for vaccinated people
12.	AGE_YRS : Age of the recipients who received vaccination
13.	SEX : Sexual orientation of the recipients (Male – Female, Unknown)
14.	VAX_DATE : Data of vaccination received by recipients
15.	ONSET_DATE : Date of onset of adverse event symptoms associated with the vaccination
16.	NUMDAYS : no. of days between the vaccination date and first onset symptom
17.	V_ADMINBY: Facilities administrating the vaccine ( places where recipients received vaccinations)
18.	OTHER_MEDS: Any on-going medications reported during reporting of symptoms from vaccination
19.	HOSPDAYS:  No. of days recipient was hospitalised if condition was serious.
20.	CURE_ILL: Current illness reported at the time of vaccination if any
21.	TODAYS_DATE : Date of report entered into the VARES system
22.	ALLERGIES : Any pre-existing physician-diagnosed allergies that existed at the time of vaccination
23.	HOSPITAL : Recipient hospitalised or not
24.	HISTORY : Previous history of illness if any
25.	L_THREAT : Whether the side effects were life threatening to the participant or not

ML Techniques Used : Logistic Regression , Decision Tree ,Random Forest and KNN

Link to Dataset : https://vaers.hhs.gov/data/datasets.html
