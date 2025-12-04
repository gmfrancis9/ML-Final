# Predicting Health Scores through Lifestyle Habits

## Problem Statement:
There is a lot of information out on the internet that tells us if we are doing healthy things or not and this can be paralyzing at some points when making decisions related to our own health. Is red meat good for us or not? Is diet soda worse than regular soda? How important is sleep? There are so many of these kinds of questions that doctors and “health professionals” online argue over that you can never really know for sure if you are living a healthy lifestyle or not. The question that this project is trying to answer is whether we can notice general trends in people’s lifestyles that are indicative of a better quality of life, as well as the length of life. I will be utilizing a neural network to try to analyze this problem due to the high dimensionality of the data and the non-linear relationships in the data. 

## Results: 
The main findings of my work is that there was a lot of linearity in the data and that this data might have been handled better with a different model. I got great results using the MLP + LightGBM ensemble model but I think that you could get similar results using a Random Forest model or something similar to that. Ensemble models are great when you reach a plateau with one model and you want to improve your model performance. Adding another model in can make the model more well rounded and able to recognize new relationships which is why the ensemble model had the best performance out of all the models we tried. I think that the project did fall short on the accuracy predictions since I was originally shooting for .9 R2 score and only reached a .87. 


## How to Setup Project:
* Python Version: 3.9
* Download Jupyter Notebook
* Clone or Download (.zip) Repository 
* Download all Dependencies listed in requirements.txt

