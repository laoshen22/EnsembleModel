# EnsembleModel

我之前做的机器学习模型，一共 9 个，包括


* [1] "Stochastic Gradient Boosting"                             
* [2] "Multi-Layer Perceptron"                                   
* [3] "Multivariate Adaptive Regression Spline"                  
* [4] "Generalized Linear Model"                                 
* [5] "Support Vector Machines with Radial Basis Function Kernel"
* [6] "k-Nearest Neighbors"                                      
* [7] "Generalized Additive Model using Splines"                 
* [8] "glmnet"                                                   
* [9] "Boosted Tree"

coding 包括划分数据为training 和 testing 到parallel computing 到模型训练 到ensemble。


# 有关the parallel computing

在caret中用以下code
```
set.seed(800)
detectCores()
registerDoParallel(48,cores=48)
getDoParWorkers()
```

* <https://topepo.github.io/caret/parallel-processing.html>

* <https://rpubs.com/msundar/large_data_analysis>
