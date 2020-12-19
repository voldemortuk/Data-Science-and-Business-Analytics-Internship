# Task 2
### Iris Flower Species Dataset

In this tutorial we will use the Iris Flower Species Dataset.

The Iris Flower Dataset involves predicting the flower species given measurements of iris flowers.

It is a multiclass classification problem. The number of observations for each class is balanced. There are 150 observations with 4 input variables and 1 output variable. The variable names are as follows  :

        Sepal length in cm.
        Sepal width in cm.
        Petal length in cm.
        Petal width in cm.
        Class

## Prediction using Using Unsupervised Learning
	•In this task we will use K nearest algorithm to make prediction and understand its working.!
![decisiontree](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK6/Task6.png)
# K nearest neighbour algorithm
The k-Nearest Neighbors algorithm or KNN for short is a very simple technique.
The entire training dataset is stored. When a prediction is required, the k-most similar records to a new record from the training dataset are then located. From these neighbors, a summarized prediction is made.



![decisiontree](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK6/Decision-Trees-2.png)


The dataset here has 6 different parameters , so we can use K nearest algorithm to feed any new/test data to this classifer and it would be able to predict the right class accordingly.

• In this task we will use K means Clustering to make prediction and understand its working.!
![decisiontree](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK6/Task6.png)
# K means Clustering 

K-Means Clustering is an unsupervised machine learning algorithm. We graph the relationship between the number of clusters and Within Cluster Sum of Squares (WCSS) then we select the number of clusters where the change in WCSS begins to level off (elbow method).
It is  one of  the simplest unsupervised  learning  algorithms  that  solve  the well  known clustering problem. The procedure follows a simple and  easy  way  to classify a given data set  through a certain number of  clusters (assume k clusters) fixed apriori. The  main  idea  is to define k centers, one for each cluster. These centers  should  be placed in a cunning  way  because of  different  location  causes different  result. So, the better  choice  is  to place them  as  much as possible  far away from each other. The  next  step is to take each point belonging  to a  given data set and associate it to the nearest center. When no point  is  pending,  the first step is completed and an early group age  is done. At this point we need to re-calculate k new centroids as barycenter of  theclusters resulting from the previous step. After we have these k new centroids, a new binding has to be done  between  the same data set points  and  the nearest new center. A loop has been generated.

![decisiontree](https://github.com/voldemortuk/Data-Science-and-Business-Analytics-Internship/blob/main/TASK6/Decision-Trees-2.png)




### STEPS INVOLVED IN TRAINING THE MODEL :
    Step 1 : import all the required libraries required .

    Step 2 : Read the dataset.

    Step 3 : Randomly select ‘c’ cluster centers.
   
     Steo 4 : Assign the data point to the cluster center whose distance from the cluster center is minimum of all the cluster centers.
    
    Step 5 :  Lets train our model and fit the dataset.
    
    Step 6 : Recalculate the new cluster center using: 
                where, ‘ci’ represents the number of data points in ith cluster.

    Step 7 :  Recalculate the distance between each data point and new obtained cluster centers.
                    If no data point was reassigned then stop, otherwise repeat from step 4).

    Step 8 : Now check the accuracy of the model and evaluate it

    Step 9 : Now lets you test how well your model fits the data set.
