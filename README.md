# KNN in Iris dataset

### Dependency  

* numpy  
* pandas  
* operator

### Brief 
* Using different distances methods , compare the accuracy
* With PCA and Cross-Validation  
* Dataset : Iris.csv  

### K-fold issue in small-dataset
* When dataset is small and the MSE/Missclassification is pretty low, random permutation dataset then using K-fold will make it obvious different .
* 当数据集很小而且分类误差很小的时候，每次K-fold产生的平均误差的分布区间很小，在k-fold之前随机打乱数据，会令每次打乱数据之后进行的实验产生的结果都不一样。数据集小，区间小波动大

### Any question  
Email:allanxu@life.hkbu.edu.hk
