# Data Mining Term Project

## 1.**Introduction** :
&ensp; Wine quality is widely used in machine learning and data mining, therefore, this are our study subject of data mining.  
&ensp; Wine quality frequently influenced by climate, weather, temperature and the winemaking process that are not the indicators we used in dataset, instead ,there are objectivie attributes, such as, volatile acidity, sulphate, sulfur dioxide.  
&ensp; After we learnt plenty of methods of data mining to find the rules of classification, we can now practice and compare it by Weka.

## 2.**Preprocess(Related Work)** :
因為是從網站上直接抓下來知名的dataset，檢查過後並沒有任何Data Missing的情況。

## 3.**Mine the Data** :
&ensp; After preprocessing, we tested the following methods to find the rule of data where we could calculate accuracy by classifying the test set.  
&ensp; There are two major way to find the rule. First, using the classifier functions or Decision trees .Secondly, clustering the data and we evaluation the clusters to their possible classes.  
&ensp; It is a simple strategy that we used is choosing the highest accuracy in these methods with non-preprocessed dataset. Processing to the next step, adjusting the arguments try to get the higher accuracy, therefore the final goal we want to achieve is to find the best accuracy as possible to classify the quality of wine by these attributes experimentally filtered or chosen by heuristic.


Methods we will try:
  * MultiLayerPerceptron *(Neural Network)*
  * IBK *(K-nearest)*
  * RandomForest
  * J48 *(Decision Trees)*
  * K-means with *Classes to clusters evaluation*  

## 4.**Experiments** :
&ensp; First, clustering the data by **Simple K Means**.Using the *Euclidean Distance* and number of clusters is *6*. As we can see, it is not the result we want to get and this method can't applied to classifying that the accuracy calculated by confusion matrix is ***26.8293%*** which is extremely low.
![](https://i.imgur.com/QLxUJzv.png)  
**Fig.1 Confusion Matrix of Simple K Means**

&ensp; Second

## 5.**Conclusion** :


### **Reference** :
Dataset contributed by *Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009*
