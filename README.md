# IHD Flash Talks Talk: Joint Attention, Computer Vision, and Foundation Models: How State-of-the-art AI approaches can analyze instances of early childhood development




# Overview

This project seeks to develop a tool to help with the Filming Interactions to Nurture Development (FIND) project. By using multimodal modeling we are developing a human in the loop software that aims to identify the serve and return process within developmental psychology.


# Software
![Software_Overview](Software_Overview.png)

Above is the is the high level process flow the application.

## Clip Matching Script
This script is located in the utility folder. The function is matching existing raw footage (full length unedited videos) to currently existing coaching clips to create a rudimentary labeled dataset. This **Semi-Labeled Dataset** could be useful in various ways but **becareful as this data set contains many false negatives.** Generally the raw footage will have more serve and return behaviors that are contained in the video then the clips identified in the coaching session. This creates unbalance in our data set.

## Front End User Interface [1]

## Machine Learning Model [2]

## Human Inspection

## Machine Learning Training Process
Two potential ways of training the modles
- Train off of the output features of each up stream model
- Remove the decoder of each up stream model and pool the outputs into a neural net
- Rule based modeling
