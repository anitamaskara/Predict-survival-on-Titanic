# Predict-survival-on-Titanic-using-Python

# Introduction
Titanic: Machine Learning from Disaster dataset is used to predict survival on the Titanic and get familiar with ML basics. The data is available at <a href="https://www.kaggle.com/c/titanic/data"> https://www.kaggle.com/c/titanic/data</a>

# Competition Description
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

# Data
The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set is used to build the machine learning model. For the training set, the outcome is provided (also known as the “ground truth”) for each passenger.

The test set is used to see how well the model performs on unseen data. For the test set, the ground truth for each passenger is not provided.
I predict these outcomes. For each passenger in the test set, the model I trained is used to predict whether or not they survived the sinking of the Titanic.

# Data Dictionary

survival:	     0 = No, 1 = Yes <br>
pclass:	  Ticket class	1 = 1st , 2 = 2nd, 3 = 3rd <br>
sex <br>
Age:	Age in years; Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
<br>
sibsp:	# of siblings / spouses aboard the Titanic; Sibling = brother, sister, stepbrother, stepsister;Spouse = husband, wife (mistresses and fiancés were ignored)
<br>
parch:	# of parents / children aboard the Titanic	<br>
ticket:	Ticket number	<br>
fare: Passenger fare	<br>
cabin	: Cabin number	<br>
embarked:	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton <br>

The dataset defines family relations in this way...<br>
Parent = mother, father <br>
Child = daughter, son, stepdaughter, stepson<br>
Some children travelled only with a nanny, therefore parch=0 for them.
