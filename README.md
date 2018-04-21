# Python-Project.py

## The Iris Data Set

### Evolution of Machine Learning

### The most famous set of data for data mining and machine learning is the infamous Iris data set. 

### The Iris Data Set is a specific set of information compiled by Ronald Fisher. Ronald Fisher as a biologist in the 1930’s.
![Picture of Ronald Fisher,](http://www.swlearning.com/quant/kohler/stat/biographical_sketches/Fisher_3.jpeg)

### But the original data as taken by a man named Edgar Anderson in 1935 who was an American botanist who studied the flowers in Quebec in Canada, he called the data “The irises of the Gaspe Peninsula, he did this to quantify the variation if iris flowers. Two of the the three species were collected in the Gaspe Peninsula and were picked on the same day from the same field and measured at the same time by the same time with the same aparatus.

![picture of Iris Setosa](https://en.wikipedia.org/wiki/Iris_(plant)#/media/File:Iris_germanica_(Purple_bearded_Iris),_Wakehurst_Place,_UK_-_Diliff.jpg)

### Ronald Fisher used the data as an example for multivariante discriminant analysis.
The Iris Data Set describes biological characteristics of various types of flowers, specifically length and width of both petals and sepals which are part of the flowers reproductive system.
The data set contains 3 classes of 50 instances each, where each class refers to a type pf Iris plant. One class is linearly separable from the other to and the latter are not linearly separable from each other.

## Attribute Information:
1.	Sepal Length in cm
2.	Sepal Width in cm
3.	Petal Length in cm
4.	Petal Width in cm

## Class:
1.	Iris Setosa
2.	Iris Versicolour
3.	Iris Virginica
 .
### It is used widely as a data set for testing purposes in computer science. Also, many academic researchers have used the Iris Data Set in the area of machine learning, as the dat is about pattern recognition, researchers believe that the computer has the capacity to learn without being programmed to perform specific tasks.

### There is a lot of research in the area of Artificial Intellignece and researchers are interested to see can computers learn form data. Machines can use previous computations to automate to repeat and automate future deciosn making.This has been aroung for quiet a while but now with the ever growing scale of data and its now affordable data storage, and the need for automatuion and efficiency and effectiveness in the workplace and beyond, we need to find a way to analyze large ammounts of more complex data and deliver faster results.
### Machine learning can range at present form online reccommendations on Amazon or Netflix to Googles self drive cars, to fraud detection.

### In this Project i will use the Python script to analyse various data to find out more about the infamous Iris Data Set and use charts and tables to show the results of my findings. I will also use various libraries and websites to to aid me in this project and further my knowledge and understanding of this particular data set.

## First we will look at what is the minimum and maximum of each of the four columns of the iris dat set.
















import pandas as pd
mydataset = pd.read_csv('iris.csv')
x = mydataset.iloc[:,1].values
print(min(x))
print(max(x))
















































References
https://www.techopedia.com/definition/32880/iris-flower-data-set
https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.names
https://analyticsindiamag.com/start-building-first-machine-learning-project-famous-dataset/
https://www.kaggle.com/uciml/iris
https://rstudio-pubs-static.s3.amazonaws.com/205883_b658730c12d14aa6996fe2f6c612c65f.html
http://www.codeastar.com/beginner-data-science-tutorial/
https://www.kaggle.com/uciml/irisIris_flower_data_set
https://en.wikipedia.org/wiki/Iris_flower_data_set
https://www.sas.com/en_ie/insights/analytics/machine-learning.html




	

	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	



 




