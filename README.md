# ML-PROJECT-2

## Title:

PREDICTING THE LIKELIHOOD OF CANDIDATE JOINING THE COMPANY OR NOT

## About the dataset which i've used for this project:

This dataset was part of the recruitment process of a particular client of ScaleneWorks. ScaleneWorks supports several information technology (IT) companies in India with talent acquisition. One of the challenges they face is about 30% of the candidate who accepts the job offer, do not join the company, this leads to a huge loss of revenue and time as the companies initiate the recruitment process again to fill the workforce demand.

## Feature description:

* Candidate - Unique reference number to identify candidate
* DOJ Extended - Date of joining asked by candidate or not
* Duration to accept the offer - Number of days taken by the candidate to accept the offer
* Notice period - Notice period served before candidate can join the company
* Offered band - Band offered to candidate based on experience, performance
* Percent hike expected in CTC - Percentage hike expected by the candidate
* Percent hike offered in CTC - Percentage hike offered by the company
* Percent difference CTC - Difference between expected and offered hike
* Joining Bonus - Joining bonus is given or not
* Candidate relocate actual - Candidates have to relocate or not
* Gender - Gender of the candidate
* Candidate Source - Source from which resume of the candidate was obtained
* Rex in Yrs - Relevant years of experience
* LOB - Line of business for which offer was rolled out
* Location - Company location for which offer was rolled out
* Age - Age of the candidate
* Status - Target varible wh whether the candidate joined or not

## Scope	&	Objective:
 
* To	find	out	if	a	model	can	be	built	to	predict	the	likelihood	of	a	candidate	along	with	a	column	that	indicates	if	the	candidate	finally	joined	the	company	or	not	

## Business	Problem	Statement:
 
* The goal is to predict if the candidate will join or not in the company.
* The challenges they face is about 30% of the candidate who accepts the job offer, do not join the company, this leads to a huge loss of revenue and time as the companies initiate the recruitment process again to fill the workforce demand.
 
## Analytics	Tools: 
 
Python	&	Machine	language	libraries.	

## Analytics	Approach:	
 
Machine	Learning	(Logistic	Regression,	KNN	,	SVC,	Decision	Tree,	Random	Forest	)	

## KPIs:	

Accuracy,	Precision	and	Recall,	F1-Score,	ROC-AUC,	Model	Training	time	Deployment	Efficiency,	Cross	validation.	
	
## Conclusion: 

### The best model is RandomForest with an Presicion score of  0.8584720861900098
### Notice period affects the most whether or not candidate will join the company.
### If offered hike is lower than expected than candidate is more likely to withdraw from the application
### LOB and joning bonus affect the likelihood of the candidates. so keep this in mind.


