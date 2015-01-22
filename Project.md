---
title: "Practical Machine Learning Prediction Assigment"
author: "Edana Merchan"
date: "January 22, 2015"
output: html_document
---

The assigment for this class uses data collected by devices such as Jawbone Up, Nike FuelBand, and Fitbit about personal activity. This measurements are used to improve users health, to find patterns in their behavior. In this project, we are going to use the data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. 

Data 


The training data for this project are available here: 

<https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv>

The test data are available here: 

<https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv>

The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment. 


```r
#training <- read.csv("/Users/edana/Data_Fitbit/pml-training.csv", na.strings=c("NA",""))
#testing <- read.csv("/Users/edana/Data_Fitbit/pml-testing.csv", na.strings=c("NA",""))

#Clean data
#data <- nearZeroVar(training, saveMetrics=TRUE)
```

##References

Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.
