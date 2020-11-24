Return [Home](index.md)

# Blog 5: Sprint 2 Week 2


This week was the second week for Sprint 2.
During this second week of this Sprint we completed the basic elements of the UI, worked on dataset manipulation, completed the model serializer and reserializer, and started working on our final presentation package.
We are in the process of the implementation of the AI algorithm, Support Vector Machine or SVM.

## User Interface

Currently the UI is incomplete as of the final deliverable, but the basics are completed.
In the current version of the user interface, it has two drop down menus that will allow the user to choose the dataset and the algorithm. There are also boxes that can be checked to manipulate the dataset such as turning the images to greyscale.
Currently we are in the process of creating the SVM which will be added to the UI as an option for possible algorithms to be ran.

![Image of Current Version of UI Part 1](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog5/UIPt1.png)

![Image of Current Version of UI Part 2](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog5/UIPt2.png)

## Dataset manipulation

As discussed in the last blog, making sure that the dataset is as unbias as possible is extremely important when training any AI algorithm. Taking note of this, making sure that when data is fed into the AI algorithm, it as clean as possible.
Doing this was one of the tasks that we completed this week. The specific manipulations that we did to images were make them greyscale, crop the image, and resizing. Turning the image greyscale is important to getting the most uniform colors through the algorithm.
Cropping the images is important too, it limits the amount of unnecessary background "noise" that could mess up the training of the AI.
The resizing of the images is less for the AI, and more for the users and developers. This makes it that everyone who is looking at the dataset, can clearly see what the image is capturing, instead of having a small image that is hard to see.
We have been able to mass update datasets by converting them to greyscale and resizing using Python.

![Image of Mass Dataset Manipulation](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog5/dataManip.png)

## Model Serializer and Reserializer

The team worked to begin serializing the data that is brought in from the resulting spectogram. The spectogram is brought in througha stream of bytes. The goal of serialization is to convert these bytes to a readable OOP object that can be used when developing in our Python package. Serialization will convert these objects, which we will use accordingly in our dataset assessment.

![Model of Data Serialization & Deserialization](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog5/serializationModel.png)


## Presentation Package

This week is the last week of finals and for this class, we have to do another presentation. This presentation will include what we have accomplished and what we have coming up for next semester.

## Support Vector Machine

The team has been researching the Support Vector Machine (SVM), a learning model that is used to analyze data for classification and regression analysis. The Support Vector Machine works to accomplish the training of a dataset. Given a point n, we treat each data point as if it were a vector and place it on a graph. We take a set w, considered to be the hyperplane of the graph,  multiplied by our set of x points, minus b, our offset. Whatever points fall within this decision boundary are support vectors and are considered the same classified element. Other data elements that are clumped together or within their own dataset boundary are considered data of another class or type. The purpose of the SVM is to determine the different types of objects present within a given dataset and separate and combine them into sets to make datasets more robust and takes a load off of the works that would have to be done for an set of datapoints that were to be serialized without first implementing SVM.

![Image of Mass Dataset Manipulation](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog5/svm.png)


#### Submitted by Timothy Roe, Jr. on 11/23/2020 & Updated by Cameron Ho 11/23/2020
#### Return [Home](index.md)
