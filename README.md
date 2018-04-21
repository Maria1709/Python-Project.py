# Python-Project.py

## The Iris Data Set

### Evolution of Machine Learning

### The most famous set of data for data mining and machine learning is the infamous Iris data set. 
### The Iris Data Set is a specific set of information compiled by Ronald Fisher. Ronald Fisher as a biologist in the 1930’s.
![Picture of Ronald Fisher,](http://www.swlearning.com/quant/kohler/stat/biographical_sketches/Fisher_3.jpeg)

### But the original data as taken by a man named Edgar Anderson in 1935 who was an American botanist who studied the flowers in Quebec in Canada, he called the data “The irises of the Gaspe Peninsula, he did this to quantify the variation if iris flowers. Two of the the three species were collected in the Gaspe Peninsula and were picked on the same day from the same field and measured at the same time by the same time with the same aparatus.
 

### Ronald Fisher used the data as an example for multivariante discriminant analysis.
The Iris Data Set describes biological characteristics of various types of flowers, specifically length and width of both petals and sepals which are part of the flowers reproductive system.
The data set contains 3 classes of 50 instances each, where each class refers to a type pf Iris plant. One class is linearly separable from the other to and the latter are not linearly separable from each other.

## Attribute Information:
1.	Sepal Length in cm
2.	Sepal Width in cm
3.	Petal Length in cm
4.	Petal Width in cm

# Picture of Iris Versicolor
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Blue_Flag_%28Iris_versicolor%29_-_United_States_National_Arboretum_-_%281%29.jpg" width="200" Height="200">

# Picture of Setosa
<img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg" width="200" Height="200">

# Picture of Iris Virginica
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Iris_virginica.jpg" width="200" height="200">

## Class:
1.	Iris Versicolor
2.	Iris Setosa
3.	Iris Virginica
 .
### It is used widely as a data set for testing purposes in computer science. Also, many academic researchers have used the Iris Data Set in the area of machine learning, as the dat is about pattern recognition, researchers believe that the computer has the capacity to learn without being programmed to perform specific tasks.

### There is a lot of research in the area of Artificial Intellignece and researchers are interested to see can computers learn form data. Machines can use previous computations to automate to repeat and automate future deciosn making.This has been aroung for quiet a while but now with the ever growing scale of data and its now affordable data storage, and the need for automatuion and efficiency and effectiveness in the workplace and beyond, we need to find a way to analyze large ammounts of more complex data and deliver faster results.
### Machine learning can range at present form online reccommendations on Amazon or Netflix to Googles self drive cars, to fraud detection.

### In this Project i will use the Python script to analyse various data to find out more about the infamous Iris Data Set and use charts and tables to show the results of my findings. I will also use various libraries and websites to to aid me in this project and further my knowledge and understanding of this particular data set.

### First we will look at what is the minimum and maximum of each of the four columns of the iris data set.


![PIC4](images/snip4.PNG)


### We can see from the above data results taken of the first column of the Iris Data set that the minimum is 4.29 and the maximum is 7.9. 
### Result output for column 2: Minimum was 2.0 and the maximum was 4.4.
### Result output for column 3: 1.0, 6.9
### Result output for column 4: 0.1, 2.5

### To get a better more accurate picture of this data set we will calculate the average of the Iris Data set.


![PIC2](images/snip2.PNG)
					
					
	
	
										

![PIC1](images/snip1.PNG)
					
					
### We can see from the array of data above that the average of the first column is 5.84
					
![PIC6](images/snip6.PNG)

![PIC7](images/snip7.PNG)





![PIC1](images/snip8.PNG)




















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




	

	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	



 




