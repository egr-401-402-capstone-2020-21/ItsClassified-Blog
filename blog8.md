Return [Home](index.md)

# Blog 8: Sprint Iteration 4

This week is the first week of Sprint Iteration 4. The main objectives that we had for this week were more AI implementation, adding features to the UI, and more Research.
Also at this moment, we have completed 71% of our tasks. Remember from the last [blog post](blog7.md), this is only a percentage of the total tasks completed,
and not taking into account the difficulty of the task.

![Image of Burndown Chart](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/71Burndown.png)

## Current State of the AI Implementation

As stated in the last [blog post](blog7.md) we have 4 working AI models. During this sprint we have started to clean up parts of the implementation to make it easier to access.
In addition to that, we have made some changes to the training and testing datasets. Specifically we have increased the amount of images by about 2,000 images, which brings our total training dataset images to 11,000, with 285 images x 42 classifications.
For the testing dataset, we have increased the amount form 2,500 to 12,000.
We have also changed how the datasets are being built. In the previous implementations there were little deviations in the way we were training, but now we are randomizing the training for each classification.
By randomizing the images selected from each classification we are able to get a more true sample for each classification.
After doing some research and analyzing the results of our previous tests, we found out that the accuracies of the AI models were actually between 50-80%. The 97% and above numbers that we were seeing were not a tur representation of the model's abilities.
Below are the images of the old statistics and the new statistics. As you can see, there are a lot more images that are being used to train and test the AI models.

![Image of Old Statistics](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/oldStats.png)

![Image of New Statistics](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/newStats.png)

We have also started the implementation of Unit Testing. This will serve as a double check for all of the training and testing we are doing, and ensure that the AI is doing what we are intending the model to do.

## UI Implementation

For the UI, we have added some new features. These features consisted of a real time line graph that outputs the time and accuracy of the AI model using the live data that is recorded by the model.
Another feature that we were able to complete this week is when the model is done running, it will output the percentage comparison of the different models on their time, efficiency, and accuracy.
This will be demonstrated on a bar graph comparing two or more models and a data frame box. Additionally, to improve the user experience, we have added celebratory balloons to demonstrate the model's completion.

![Video of UI](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/UI.mov)

## Research: Classifications

When classifying images there is an effective practice for data augmentation. To do this, traditional affine and elastic transformations to create new images are used. Some of these transformations include rotation, reflection, zooming in and out, shifting, applying distortion, and changing the colors.
Even using multiple of these techniques might not be enough for an AI model to correctly classify an image.
Using traditional methods of transformations allows the classification of algorithms to be more efficient when training.
Other forms of transformations are using histograms equalization, enhancing the image brightness, white balancing, sharpening, and blurring.
In the real world, the world has depth, its not flat like a piece of paper. By using texture transfer, it is possible to synthesize texture in an image by giving the original image visual attributes.
By using a technique called quilting, it allows for synthesizing a new image by stitching small patches of texture.

## Research: US Street Sign Discrepancies

As for research we have multiple people doing different research that is relevant to the project. One of the research topics that we are currently looking into is the differences in signs across the US.
For this in particular we are considering that some states have different images for certain signs, and to an AI this would be treated as an entire new sign that is not in its database.
During our research we found that the US does have a convention that must be followed called the Manual on Uniform Traffic Control Devices, MUTCD. But much like the government and it's laws here in the US,
the conventions that the MUTCD plan out can be altered to an extent, and there are some that are not altered.
Some of the rules that all of the states follow are the color hues and reflectivity. All of the colors and amount of reflectivity on each of the traffic signs must be the same to ensure that there is no confusion when going through different states.
Below is an image that shows the states and US federal land and which convention they follow.

![Image of MUTCD](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/UMTCDimage.png)

An example of a sign that is a little different between states is the "Parking with Time Restrictions" sign. Below is a picture of California, New York, and Seattle.
As you can see, they are all the same sign and mean the same things, but they have enough of a difference that an AI model might consider it a new classification of sign.

![Image of Different Signs](https://raw.githubusercontent.com/egr-401-402-capstone-2020-21/ItsClassified-Blog/main/images/blog8/differences.png)

#### Submitted by Cameron Ho on 2/14/2021
#### Return [Home](index.md)
