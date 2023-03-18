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



