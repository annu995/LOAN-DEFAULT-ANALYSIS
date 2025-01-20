                                           LOAN DEFAULT ANALYSIS SUMMARY																					
																					
INTRODUCTION																					
PROBLEM STATEMENT-																					
 To predict loan defaulters based on various factors to overcome the issue of loan default and  to classify if any new borrower is likely to default or not.																					
																					
DATA OVERVIEW																					
WE HAVE TOTAL rows and columns=148670, 34																					
WE HAVE FILLED NULL VALUES																					
mention= null columns and avg values																					
DATA VISUALIZATION																					
                                                                                                      STATUS ON THE BASIS OF Credit_Score																					
	credit score	Status	status %																		
	(499.6, 540.0]	3741	10.21															credit_score category	count	status	rate
	(540.0, 580.0]	3689	10.07														0	Excellent	37469	9431	0.251701406
	(580.0, 620.0]	3691	10.07														1	fair	33548	8214	0.24484321
	(620.0, 660.0]	3597	9.82														2	poor	29737	6228	0.209436056
	(660.0, 700.0]	3651	9.96														3	good	25773	7334	0.284561363
	(700.0, 740.0]	3506	9.57														4	very good	22143	5432	0.245314546
	(740.0, 780.0]	3618	9.87																		
	(780.0, 820.0]	3626	9.90																		
	(820.0, 860.0]	3750	10.23																		
	(860.0, 900.0]	3770	10.29																		
	total	36639	100.00																		
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT WITH CREDIT SCORE (860.0, 900.0] IS MAXIMUM i.e.10.29% AND MINUMUM FOR CREDIT SCORE (700.0, 740.0] i.e. 9.57%																					
																					
                                                                                                    STATUS ON THE BASIS OF dtir1(debt to income ratio)																					
	dtir1	Status	Status %																		
	(4.944, 10.6]	670	1.8																		
	(10.6, 16.2]	638	1.7																		
	(16.2, 21.8]	863	2.4																		
	(21.8, 27.4]	1264	3.4																		
	(27.4, 33.0]	2034	5.6																		
	(33.0, 38.6]	19120	52.2																		
	(38.6, 44.2]	4171	11.4																		
	(44.2, 49.8]	3832	10.5																		
	(49.8, 55.4]	2094	5.7																		
	(55.4, 61.0]	1953	5.3																		
	total	36639	100.0																		
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT WITH dtir1 (33.0, 38.6] IS MAXIMUM i.e.52.1% AND MINUMUM FOR dtir (10.6, 16.2] i.e. 1.7%																					
																					
																					
                                                                         STATUS ON THE BASIS OF GENDER																					
																					
		Gender	Status	Status %																	
		Female	6848	18.7																	
		Joint	7933	21.7																	
		Sex Not Available	10767	29.4																	
		Male	11091	30.3																	
		total	36639	100.0																	
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT DONE BY MALE IS MAXIMUM i.e 30.27% AND MINUMUM FOR JOINT  i.e. 21.6%																					
																					
																					
                                                                                                      STATUS ON THE BASIS OF TERM																					
Term	Status	Status %																			
96	40	0.11																			
108	5	0.01																			
120	93	0.25																			
132	26	0.07																			
144	46	0.13																			
156	33	0.09																			
165	1	0.00																			
168	18	0.05																			
180	3154	8.61																			
192	2	0.01																			
204	16	0.04																			
216	26	0.07																			
228	18	0.05																			
240	1220	3.33																			
252	0	0.00																			
264	7	0.02																			
276	27	0.07																			
280	1	0.00																			
288	13	0.04																			
300	1596	4.36																			
312	30	0.08																			
322	0	0.00																			
324	703	1.92																			
336	39	0.11																			
348	53	0.14																			
360	29472	80.44																			
total	36639	100																			
																					
CONCLUSION= LOAN DEFAULT DONE WITH TERM 360 IS MAXIMUM i.e 80.4% AND MINUMUM FOR TERM 322 AND 252  i.e. 0%																					
																					
                                                                                                      STATUS ON THE BASIS OF REGION																					
	REGION	STATUS	STATUS %																		
	North-East	376	1.03																		
	central	2395	6.54																		
	North	16821	45.91																		
	south	17047	46.53																		
	TOTAL	36639	100.00																		
																					
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT DONE BY SOUTH IS MAXIMUM i.e 46.5% AND MINIMUM DONE BY NORTH-EAST i.e. 1%																					
																					
                                                                                                      STATUS  ON THE BASIS OF approv_in_adv																					
	approv_in	Status	Status %																		
	pre	4835	13.2																		
	nopre	31804	86.8																		
	total	36639	100																		
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION= DEFAULT DONE BY NOT PRE-APPROVED LOAN IS GREATER THAN PRE-APPROVED LOAN																					
																					
                                                                                                      STATUS  ON THE BASIS OF LOAN LIMIT																					
	loan limit	status	Status %																		
	cf	33325	91.0																		
	ncf	3314	9.0																		
	total	36639	100																		
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION- LOAN  DEFAULT IS GREATER IN CF THAN NCF i.e. 91%																					
																					
																					
                                                                                                      STATUS  ON THE BASIS OF business_or_commercial																					
bus or com	status	status %																			
b/c	7172	19.57																			
nob/c	29467	80.43																			
total	36639	100																			
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT IS GREATER IN nob/c than b/c i.e. 80%																					
																					
                                                                                                      STATUS  ON THE BASIS OF co-applicant_credit_type																					
																					
	co-applicant_credit_type		Status	status %																	
	CIB		13713	37.43																	
	EXP		22926	62.57																	
	total		36639	100																	
																					
																					
																					
																					
																					
																					
																					
CONCLUSION=LOAN DEFAULT IS GREATER FOR EXP i.e. 62.5%					than CIB																
																					
                                                                                                      STATUS  ON THE BASIS OF AGE																					
																					
			AGE	STATUS	STATUS %																
			<25	387	1.06																
			>74	2153	5.88																
			25-34	4248	11.59																
			65-74	5571	15.21																
			35-44	7309	19.95																
			55-64	8422	22.99																
			45-54	8549	23.33																
			TOTAL	36639	100																
																					
																					
																					
CONCLUSION=LOAN DEFAULT DONE BY AGE GROUP 45-54 IS MAXIMUM AND MINIMUM FOR <25																					
																					
                                                                                                      STATUS  ON THE BASIS OF submission_of_application																					
																					
	submission_of_application		status	status %																	
	not_inst		9226	25.181																	
	to_inst		27413	74.819																	
	total		36639	100.000																	
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION=LOAN DEFAULT IS GREATER FOR loan applications submitted directly THAN not_inst																					
																					
                                                                                                      STATUS  ON THE BASIS OF LTV																					
		LTV	Status	Status %																	
		(783.996, 1567.024]	0	0																	
		(1567.024, 2350.052]	0	0																	
		(3133.08, 3916.109]	0	0																	
		(3916.109, 4699.137]	0	0																	
		(4699.137, 5482.165]	0	0																	
		(5482.165, 6265.193]	0	0																	
		(6265.193, 7048.222]	0	0																	
		(7048.222, 7831.25]	0	0.000																	
		(2350.052, 3133.08]	1	0.003																	
		(-6.863, 783.996]	36638	99.997																	
		total	36639	100.000																	
																					
																					
																					
CONCLUSION= LOAN DEFAULT IS MAXIMUM FOR LTV (-6.863, 783.996] i.e. 99.9%																					
																					
                                                                                                      STATUS  ON THE BASIS OF rate_of_interest																					
		rate_of_interest		Status	status %																
		(-0.008, 0.8]		0	0																
		(0.8, 1.6]		0	0																
		(1.6, 2.4]		0	0																
		(2.4, 3.2]		1	0.00																
		(3.2, 4.0]		36510	99.65																
		(4.0, 4.8]		80	0.22																
		(4.8, 5.6]		48	0.13																
		(5.6, 6.4]		0	0																
		(6.4, 7.2]		0	0																
		(7.2, 8.0]		0	0																
		total		36639	100																
																					
																					
																					
CONCLUSION=DEFAULT IS MAXIMUM FOR RATE_OF _INTEREST (3.2, 4.0]  																					
																					
                                                                                                      STATUS  ON THE BASIS INCOME																					
																					
	INCOME	STATUS	STATUS %																		
	(231432.0, 289290.0]	0	0																		
	(347148.0, 405006.0]	0	0																		
	(405006.0, 462864.0]	0	0																		
	(462864.0, 520722.0]	0	0																		
	(289290.0, 347148.0]	1	0.0																		
	(520722.0, 578580.0]	1	0.0																		
	(173574.0, 231432.0]	3	0.0																		
	(115716.0, 173574.0]	11	0.0																		
	(57858.0, 115716.0]	50	0.1																		
	(-578.58, 57858.0]	36573	99.8																		
	TOTAL	36639	100.0																		
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT IS MAXIMUM FOR INCOME 				(-578.58, 57858.0]		i.e. 99%															
																					
                                                                                                      STATUS  ON THE BASIS OF OPEN CREDIT																					
																					
open_credit	STATUS	STATUS %																			
nopc    	36541	99.7																			
opc        	98	0.3																			
TOTAL	36639	100																			
																					
																					
																					
																					
																					
																					
																					
																					
																					
																					
CONCLUSION= LOAN DEFAULT IS GREATER FOR NO OPEN CREDIT i.e 99.7%																					
                                                                                       CONCLUSIONS
Credit Score and Loan Default:
Loan defaults are highest for credit scores in the range (860.0, 900.0] (10.29%) and lowest for scores in (700.0, 740.0] (9.57%).

Demographics and Loan Defaults:

Defaults are highest for males (30.27%) and lowest for joint accounts (21.6%).
Age group 45–54 shows the highest default rate, while the <25 age group has the lowest.

Loan Terms and Conditions:

Loan defaults are maximum for a term of 360 months (80.4%), and no defaults are observed for terms 322 and 252 months.
Non-pre-approved loans have a higher default rate compared to pre-approved ones.

Regional and Loan Type Analysis:

Defaults are highest in the South (46.5%) and lowest in the North-East (1%).
Loan defaults are higher for loan applications submitted directly than through other sources.

Other Key Factors:

Defaults are maximum for:
Income range (-578.58, 57858.0] (99%).
Loan-to-value ratio (LTV) range (-6.863, 783.996] (99.9%).
Rate of interest range (3.2, 4.0].
Borrowers with no open credit (99.7%) and CF over NCF loans (91%).
![image](https://github.com/user-attachments/assets/40d4ee9d-8f7d-41c6-a526-8189630f9706)
                                            FINAL CONCLUSIONS
Demographics and Loan Conditions:
Loan defaults are highest for males (30.27%), the age group 45–54, and loans with a term of 360 months (80.4%). Defaults are also significantly higher for non-pre-approved loans, directly submitted applications, and borrowers with no open credit (99.7%).

Financial and Regional Insights:

Defaults peak for income range (-578.58, 57858.0] (99%), LTV range (-6.863, 783.996] (99.9%), and rate of interest (3.2, 4.0]. Regionally, defaults are highest in the South (46.5%) and lowest in the North-East (1%).
![image](https://github.com/user-attachments/assets/11705120-8a96-449f-8acd-6e3e329f5dab)

