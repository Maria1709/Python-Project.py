# Python-Project.py

The Iris Data Set
The Iris Data Set is a specific set of information compiled by Ronald Fisher. Ronald Fisher as a biologist in the 1930’s. But the original data as taken by a man named Edgar Anderson in 1935 who was an American botanist who studied the flowers in Quebec in Canada, he called the data “The irises of the Gaspe Peninsula, he did this to quantify the variation if iris flowers. 
Ronald Fisher used the data as an example for multivariate discriminant analysis.
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
































##   Sepal. Length    Sepal. Width     Petal. Length    Petal. Width   
## Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100  
## 1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300  
## Median :5.800   Median :3.000   Median :4.350   Median :1.300  
## Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199  
## 3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800  
## Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500  
##        Species  
## setose    :50  
## versicolor:50  
## virginica :50  
##                 
##                 
## 









1.0	
Summary












References
https://www.techopedia.com/definition/32880/iris-flower-data-set
https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.names
https://analyticsindiamag.com/start-building-first-machine-learning-project-famous-dataset/
https://www.kaggle.com/uciml/iris
https://rstudio-pubs-static.s3.amazonaws.com/205883_b658730c12d14aa6996fe2f6c612c65f.html

Summary Statistics:
	         Min Max   Mean    SD   Class Correlation
   sepal length: 4.3 7.9   5.84 0.83    0.7826   
    sepal width: 2.0 4.4   3.05 0.43   -0.4194
   petal length: 1.0 6.9   3.76 1.76    0.9490 (high!)
    petal width: 0.1 2.5   1.20 0.76    0.9565 (high!)
	
	  Summary Statistics:
	         Min Max   Mean    SD   Class Correlation
   sepal length: 4.3 7.9   5.84 0.83    0.7826   
    sepal width: 2.0 4.4   3.05 0.43   -0.4194
   petal length: 1.0 6.9   3.76 1.76    0.9490 (high!)
    petal width: 0.1 2.5   1.20 0.76    0.9565 (high!)

9. Class Distribution: 33.3% for each of 3 classes.
	
	
	https://www.kaggle.com/uciml/iris
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	



 




