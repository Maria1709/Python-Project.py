# Python-Project.py

## The Iris Data Set

### The Iris Data Set is a specific set of information compiled by Ronald Fisher. Ronald Fisher as a biologist in the 1930’s.
![Picture of Ronald Fisher] (Fisher_3.jpeg)

### But the original data as taken by a man named Edgar Anderson in 1935 who was an American botanist who studied the flowers in Quebec in Canada, he called the data “The irises of the Gaspe Peninsula, he did this to quantify the variation if iris flowers.

![picture of Iris Setosa](iris setosa.jpg)

### Ronald Fisher used the data as an example for multivariate discriminant analysis.
The Iris Data Set describes biological characteristics of various types of flowers, specifically length and width of both petals and sepals which are part of the flowers reproductive system.
The data set contains 3 classes of 50 instances each, where each class refers to a type pf Iris plant. One class is linearly separable from the other to and the latter are not linearly separable from each other.
Attribute Information:
1.	Sepal Length in cm
2.	Sepal Width in cm
3.	Petal Length in cm
4.	Petal Width in cm

Class:
1.	Iris Setosa
2.	Iris Versicolour
3.	Iris Virginica
 
It is used widely as a data set for testing purposes in computer science. Also, many academic research papers have used the Iris Data Set 




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
https://www.kaggle.com/uciml/iris


	

	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	



 




