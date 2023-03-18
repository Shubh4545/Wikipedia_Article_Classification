# Wikipedia Article Classification

## Problem Statement
Probleme statement given [here](https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/3dd2706404ac7bf2ddc5fa1ac579bba2ce627baa/Wikipedia_Article_Classification.ipynb) 

## Goal 
The end goal of this project is to develop a binary classification model that can classify Wikipedia articles as either featured or non-featured. 

##Installation
We are using Google Colab as IDE beacuse it is very powerfull tool.

we have used libraries like pandas,numpy,seaborn,matplotlib,sklearn,imblearn etc

And For Dataset creation we are using Wikipidia API also.

## Usage
First you have to [run](https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/3dd2706404ac7bf2ddc5fa1ac579bba2ce627baa/WIkipedia_dataset_Create.ipynb) to create dataset file.

As we are saving data from API it will take time or get timeout due to responce of server so run it continously until all data gets saved

## Clean Data
Dataset looks like before

![dataset}(https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/200ccdb7ded80c7473382571f2fb634be7a18eca/Resource/dataset%20before%20cleaning.png)

we performed  operations like remove duplicates,removing nan ,checking missing values and changing data type

## EDA
This is most important part

We checked Dependent Feature we got to know Data is highly imbalenced ratio is 98:2

![dependent](https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/a25696176ca83b41cee5b63c480b0a2bbb2a682d/Resource/y.png)

## Model

we used Linear regression , Random forst and SVM 

Results of three modes are

![Result](https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/1b46c07f1af845e0d02cae40cbe58e5f6dc9d5de/Resource/result.png)

## Post Evluation

Feature imporatnce of feature is 

![imp](https://github.com/Shubh4545/Wikipedia_Article_Classification/blob/ffd4a0903f7974294aa75823898576c35aafe766/Resource/feature%20imp.png)

# Conclusion
Based on the results, we can draw the following conclusions:

The Linear Regression model has the highest accuracy on the test set (98.48%), followed closely by the Random Forest model (94.67%). The SVM model has the lowest accuracy on the test set (94%).

The Linear Regression model has a slightly higher accuracy on the training set than the Random Forest model (97.97% vs. 94.52%). The SVM model has the highest accuracy on the training set (97%).

The AUROC score is a metric that indicates the quality of the model's ranking rather than the absolute accuracy. Both the Linear Regression and Random Forest models have high AUROC scores of 0.97, indicating that they can effectively separate the two classes. The SVM model has a slightly lower AUROC score of 0.94, indicating that it may not be as effective in ranking the samples.

Overall, the Linear Regression and Random Forest models seem to perform well on this dataset, while the SVM model has room for improvement. However, it's important to note that the choice of model depends on the specific requirements of the problem at hand, and other factors such as interpretability, computational complexity, and scalability should also be considered.









