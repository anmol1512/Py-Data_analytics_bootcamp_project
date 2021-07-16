
# Data visualization and Analysis of "Titanic" Dataset

A mini project to analyze and Visualize the large Dataset of Titanic Ship passengers by using Numpy,Pandas (Series+DataFrames) and Data visualization packages eg. Seaborn,Matplotlib.


## OBJECTIVE
The Object of this project is to use pandas dataframes and some data visualization packages in python  to analyze what could be the  certain conclusion that can be made out about the passengers travelling in Titanic ship.

Hence analysis of the given data set is there to find conclusion and relation among the passengers in Titanic 
Also,data visualization packages helps in visualizing a large dataset to make it a lot easier.

## DATASET DESCRIPTION

The Dataset of the Titanic passengers contains the following columns/Attributes.


| PassengerId | Survived | Pclass |  Name| Sex| 	Age |	SibSp |	Parch |	Ticket |	Fare |	Cabin |	Embarked  |           
| :-------- | :------- | :--- | :---- | :------ | :---------- | :----- | :-------- | :------- |:------- | :-------- |:------- |
| `unique int` | `binary no.(0 or 1)` | `int(1,2,3)` | `string` |`sstring(male or female)` |`int` |`int` |`int` |`string` |`int/float`|`string`|`string`|

#### Description of the attributes of the dataset
- PassengerId -> Unique passenger id
- Survived -> Survival(0=NO;1=YES)
- Pclass -> Passenger Class(1=1st class;2=2nd class;3=3rd class)
- Name -> name of the passenger
- Sex -> Male or Female
- Age -> age of passenger
- SibSp -> number of passenger's sibling/spouse Aboard
- Parch -> number of passenger's parents/children Aboard
- Ticket -> passenger's ticket no.
- Fare -> Passenger's fare(British pound)
- Cabin -> Passenger's cabin no.
- Embarked -> port of embarkation(C=Cherbourg; Q=Queenstown; S=Southampton)
 
 This Data set was provide by SHAPEAI https://www.shapeai.tech/ as a project.
 

  
## PACKAGE
#### numpy:
NumPy stands for Numerical Python and it's a fundamental package for scientific computing in Python. NumPy provides Python with an extensive math library capable of performing numerical computations effectively and efficiently.NumPy is the ndarray, where nd stands for n-dimensional. An ndarray is a multidimensional array of elements all of the same type. In other words, an ndarray is a grid that can take on many shapes and can hold either numbers or strings.

There are several ways to create ndarrays in NumPy. In the following lessons we will see two ways to create ndarrays: 
- Using regular Python lists
- Using built-in NumPy functions

In many Machine Learning problems we will often find ourself using ndarrays in many different ways. For instance, we could use an ndarray to hold the pixel values of an image that will be fed into a Neural Network for image classification.

#### pandas:
Pandas is a package for data manipulation and analysis in Python.Pandas incorporates two additional data structures into Python, namely **Pandas Series** and **Pandas DataFrame**.These data structures allow us to work with labeled and relational data in an easy and intuitive manner.
Below are just a few features that makes Pandas an excellent package for data analysis:
- Allows the use of labels for rows and columns
- Can calculate rolling statistics on time series data
- Easy handling of NaN values
- Is able to load data of different formats into DataFrames
- Can join and merge different datasets together
- It integrates with NumPy and Matplotlib

#### seaborn and matplotlib.pyplot:
If we do any work with data, whether that be through business, machine learning, or artificial intelligence, we're going to want to know about how to put together visualizations. Visualizations serve two major purposes in the data analysis process.

First of all, visualizations can be used during our initial data exploration to help us make insights into our data. Visualizations can reveal patterns in the data that statistics alone might not provide. They can also provide an intuition about the structure of our data. visualizations might promote new questions for further investigation.

Secondly, visualizations can help us convey our insights to others through explanatory plots. By generating new visualizations or polishing and refining the plots created during exploration, we can more easily show others what we found in your analysis. A good visualization can communicate the findings quickly and succinctly.

  
## CONCLUSIONS

- The number of people who died and belong to 3rd class is very more as compared to other classes i.e the died people percentage is greater in 3rd class.

- The number of male who died was more than the number of female who died with a huge difference.

- People who were travelling alone and died are more than the people who were travelling with someone and died.

- The average fare of 1st class passengers is very expensive as compared to 2ndclass and 3rd class.whereas,2nd class average fare and 3rd class average fare was very close to each other and also very cheap.

- Mature passengers(Age>=18 and Age<60) died more than other age group passengers.


  