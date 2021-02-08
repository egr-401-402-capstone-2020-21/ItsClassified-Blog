Return [Home](index.md)

# Blog 7: AI Implementation and Modifying the UI


This week was mostly the team getting AI implementation completed and updating the UI.
The biggest decision that we made this week is that we decided to rescope our project.

According to our schedule that we created before the break, we are a little ahead of schedule. To be exact we are 2 tasks ahead of schedule the schedule that we have implemented.
Here is an image of a Gant chart that we have for the entire project. According to this, we have completed 66% of the number of tasks.
This number is relative to how many tasks we have completed and how many there are total and does not pertain to how difficult each task will be. But nonetheless we have made good progress on the project and are a little ahead of our intended schedule. 

## Rescoping the Project

As a team we decided to change the focus of the project. Originally we wanted to have our AI models be trained in identifying both street signs and traffic noises, but we felt that we were spread a little thin.
All 7 members of the team decided that it would be best to change the scope of our project to just street signs.
By doing this we are able to focus more on our tasks and not have to worry about doing double the work.
Yes we do have almost double the man power, but we believe that with double the man power focusing on one type of data we can get ahead and even improve on certain attributes of the project.

## AI Models

This sprint we were scheduled to finish implementing, train, and test SVM and K Nearest Neighbors. In addition we were scheduled to start the implementation of Convolutional Neural Network, CNN, and Random Forests RF.
During this second week of this sprint, we were very productive in getting models finished and ended up completing SVM, K Nearest Neighbor, RF, and MLP.
Although we did get to do finishing a few extra algorithms, we did not end up completing the unit testing for the models.
We were also not able to complete the CNN model, but we were able to get started on that model; The schedule that we have planned out does not contain completing the CNN, but only possibly starting it if we are able to.
Along with completing the models, we were also able to implement a timing function that shows how fast the AI model recognizes and classifies the images.
Below are the current output, results, and heatmap for each of the completed algorithms.

Here are the results of the completed algorithms:

Colored Images:
![Image of Colored Results](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/coloredImage.png)

Grayscale Images:
![Image of Colored Results](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/grayscaleImage.png)

The output has 3 lines for each of the trained models. The first line shows how accurate the model is, the second line is the cross validation, and the third line shows where the heatmap image is saved to.
Cross validation is a resampling procedure used to evaluate machine learning models' results.
A heatmap is a graphical image that makes sense of the data produced by the AI model. The ideal perfect model has a strong diagonal line from the top left point to the bottom right point.
Having a strong diagonal line shows that the model is well trained and what is predicted by the AI model is the actual intended value.

Here is an image of how cross validation works:
![Image of Cross Validation](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/crossValidation.png)

SVM Heatmap:
![Image of SVM Heatmap](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/svmHeat.png)

K Nearest Neighbors Heatmap:
![Image of KNN Heatmap](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/knnHeat.png)

Random Forest Heatmap:
![Image of RF Heatmap](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/rfHeat.png)

MLP Heatmap:
![Image of MLP Speed](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog7/mlpHeat.png)

## User Interface

As far as the UI is concerned, last week we had filler data for the graphical output, and this week since we were able to get actual results, we were able to start putting those results on the graph.

## Other Documentation

This week we were also able to complete Deliverable 9, which is the final demonstration script. This script will be used for when we present our final completed project.
In our demonstration we will be showing viewers the UI's capabilities and how we were able to implement the AI models and run them locally on one machine.

#### Submitted by Cameron Ho on 2/7/2021
#### Return [Home](index.md)
