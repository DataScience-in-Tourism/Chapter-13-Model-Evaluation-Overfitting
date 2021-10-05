# Chapter 13: Model Evaluation

## How to Accurately Evaluate Predictive Models

***Ajda Pretnar*** & ***Janez Demšar***
* Ajda Pretnar - Faculty of Computer and Information Science, University of Ljubljana

### Abstract

The model evaluation assesses the performance of models on new data. The procedure helps to select the optimal predictive model based on appropriate evaluation scores that reflect the model's quality. Evaluation scores differ for classification and regression. The former commonly uses area under the ROC curve and F1 scores, while the latter uses the mean average error and the mean squared error. In both cases, evaluation requires the use of k-fold cross-validation, or a similar sampling technique, to ensure the model is tested on a different set of data than it was trained on.

-----------------------

Here you will find the Orange workflow and the data set to follow the research case.

**Orange**

Orange is an open-source data mining and machine learning software. You can download it from [orangedatamining.com](https://orangedatamining.com/download/). Use *File* - *Open* to open an existing workflow. You can learn the basics of Orange by following a few [short tutorials](https://www.youtube.com/c/OrangeDataMining).

**Hotel booking data set**

For the exercise, we will use the hotel bookings data set, which was originally published by ([Antonio, de Almeida and Nunes 2019](https://doi.org/10.1016/j.dib.2018.11.126)) and is available on [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand) and on [Github](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-02-11/readme.md).
