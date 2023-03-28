# Data-Analytics-for-Python
A completed data analysis of lego sets as part of a university assignment
The business situation is entirely fictional and uses real world data.

# Purpose
To demonstrate data analytical skills in python, namely:
 - Loading data
 - Data inspection
 - Model selection
 - Data manipulation
 - Data analysis
 - Statistical analysis
 - Data modelling
 - Data visualisation
 
 Additionally the use of business problem statement understanding and transformation into a data-driven report.

# Introduction
The data analytics procedure is completed in python using the Jupyter Notebook platform. The goal is to produce a linear model that assists with predicting the price of a lego set.

The data set used was retrieved from Kaggle.com and uses approximately 12000 sets with accompanying data such as user and age rating, piece count and price.

# Method
The data's source location, the Kaggle.com set was investigated for any specific documentation as well as any initally gleanable information.

The data is then loaded into a simple text editor to check for any specific errors prior to loading into a python pandas DataFrame object.

Upon loading, a quick overview of the dataset is performed to check details such as size, shape, description, null values and so on.

It is worth noting, the original dataset in Kaggle contains minimal pre-cleaning, where as the university assignment provided version of the dataset has had most of the pre-cleaning process completed.

The target and dependent variable investigation is then performed. Investigation into a suitable model format, as well as the constraints and conditions of the modelling choice are explored in detail.

Once the target and dependent variables are identified and the model is selected, the data cleaning and modification process begins.

The data in question required normalisation to fit the constraints of the chosen model, so additional columns of the adjusted data are created.
The original data is left in the dataset to improve analysis between original and adjusted/normalised formats.

Statistical analysis is performed on the original and adjusted data to ensure chosen model constraints are maintained.

The data is then modelled against the test set. Two runs are performed, one of the original set and one of the adjusted/normalised set.
These two model outputs are then tested against the model's constraints as well as expected accuracy and against each other.
