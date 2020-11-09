Return [Home](index.md)

# Blog 3: Sprint 1


This week we are finishing up tasks for Sprint 1. We have decided that most, if not all, of the sprints will be bi-weekly sprints.
This will allow us to the on bigger tasks within a single sprint and not worry too much about getting deliverables done within a single week.

For the tasks that we completed this week, we have completed the list of classifier algorithms that we will potentially be using in the final deliverable, completed the refactoring of our SRS document, and analyzed and prepared datasets for both images and sounds.

Classification is a task that requires the use of machine learning algorithms that learn how to assign a class label to a given input or an example from a problem domain.
An easy to understand example is classifying emails as “spam” or “not spam.” In machine learning, there are many different types of classification task that you may encounter and a specialized approach to modeling the various classification may be used.
There are four main types of classification algorithms; Binary Classification, Multi-Class Classification, Multi-Label Classification, and Imbalanced Classification

Binary classification refers to those classification tasks that have two class labels. Typically, binary classification tasks involve one class that is the normal state and another class that is the abnormal state.
Multi-class classification refers to those classification tasks that have more than two class labels. Unlike binary classification, multi-class classification does not have the notion of normal and abnormal outcomes. Instead, examples are classified as belonging to one among a range of known classes.
Multi-label classification refers to those classification tasks that have two or more class labels, where one or more class labels may be predicted for each example. Consider the example of photo classification, where a given photo may have multiple objects in the scene and a model may predict the presence of multiple known objects in the photo, such as “bicycle,” “apple,” “person,” etc.
Imbalanced classification refers to classification tasks where the number of examples in each class is unequally distributed. Typically, imbalanced classification tasks are binary classification tasks where the majority of examples in the training dataset belong to the normal class and a minority of examples belong to the abnormal class.

We have also completed going over our SRS documents and refactoring them to make sure that they reflect our new project deliverable.

We have also found public datasets online that we will be using to train and test the AI algorithms with, for both sound and images. Below is an image of the of a stop sign and a traffic light that are highlighted to visually demonstrate what the algorithms will be identifying when completed.

![Image of stop sign and traffic light](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog3/imageDataSetEx.png)

We have begun to also identify and create spectrograms from the audio files we are running in this AI. These spectorgrams output an image that looks like the ones below. The AI reads these and handles regression testing accordingly. These were generated with the library "librosa."

![Spectogram 1](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog3/spectogram_1.png)
![Spectogram 2](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog3/spectorgram_2.png)

Lastly, we are in the process of creating a project schedule for next semester so that the team, our professor, our client, and our technical advisor can keep track of what we will be doing over the upcoming weeks.

#### Updated by Timothy Roe, Jr. on 11/8/2020 and Submitted by Cameron Ho on 11/8/2020
#### Return [Home](index.md)
