# Car-Damage-Assesment

## Problem Statement

This project aims at automatically classifying the car damage impacts on cars, based on photos and using AI algorithms. Evaluating damage is time consuming process in insurance industries. Expert are physically delegated to take photos and evaluate the damages. Receiving accidented car’s photos from different sources (client mobile app, mails from client, delegates, and others) and automatically classifying them will help expert to quickly confirm and focus on more complex situation.

Also, in industry, a lot of money is being wasted on claims leakage. Claims leakage is the gap between the optimal and actual settlement of a claim. Visual inspection and validation are being used to reduce claims leakage. But doing inspection might take a long time and result in delaying of claims processing. An automated system for doing inspection and validation will be of great help in speeding up the process.

## Solution

We are trying to automate the Visual inspection and validation of car damage. The input data we have are random images.

For Validation of car damage, we will divide the problem into four stages. Firstly, we check whether the input image is of a car or not. Then, we check whether the given input image of car has been damaged or not. Then, we check on which side (Front, Rear, Side) the Car in image has been damaged. At the end, we check for the Severity of damage (Minor, Moderate, Severe).

This problem is a classification problem and since we will be dealing with images as input, we will be using Convolutional Neural Networks (CNN).

## Working

Our solution is to build a convolution neural network model capable of accepting images and determining the location and severity of the damage. The model will pass through multiple checks that would first ensure that it is a image of car, then validate that the car is damaged, find location of damage as front, rear or side and also determine the severity of the image as minor, moderate or severe. Then the results are shown to the users. Future scope includes, obtaining a cost estimate for the damages and sending a assessment report to the insurance company.

The car dataset is collected from the Stanford car image dataset. Model development is performed using TensorFlow, Keras, Numpy, Scikit-Learn.

## Improving the model

Increasing the car dataset. With a wider range of dataset featuring multiple components of the car, the model can also be trained to identify what components are damaged, also classifying the varying degree of damage of each.

With a highly expansive dataset containing the make, model, year of the car and the possible cost estimates for the varying degrees of damage, the model can also predict the value for the user, before he submits the more advanced and detailed assessment for evaluation.

The application can also be updated to recommend the user of policies pertaining to the specific accounts and other insurance benefits.




