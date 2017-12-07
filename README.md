The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this Kaggle challenge, the ask is to complete the analysis of what sorts of people were likely to survive. In particular, apply the tools of machine learning to predict which passengers survived the tragedy.

The data has been split into two groups:
•	Training set (train.csv)
•	Test set (test.csv)

Training set is used to build the model and Test set for evaluation.

Data Dictionary
----------------
Variable	  Definition	                                        Key
--------    ----------                                          ---
survival	  Survival	                                          0 = No, 1 = Yes
pclass	    Ticket class	                                      1 = 1st, 2 = 2nd, 3 = 3rd
sex	        Sex	
Age	        Age in years	
sibsp	      # of siblings / spouses aboard the Titanic	
parch	      # of parents / children aboard the Titanic	
ticket	    Ticket number	
fare	      Passenger fare	
cabin	      Cabin number	
embarked	  Port of Embarkation	                                C = Cherbourg, Q = Queenstown, S = Southampton
