<img src= https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/TechForGood_Logo.png.webp width = 200>

# Tech For Good Inc - Summer Internship 2021

### Table of Contents
- [Introduction to IDDPS project](#x)
- [What was my role in this project?](#y)
- [How was IDDPS implemented](#z)
- [What type of models where used](#a)
- [Programming languages and platforms used](#b)
- [Dataset used for training models](#c)
- [Some sample outputs](#d)
- [What were the final numbers?](#e)
- [Constraints faced](#f)
- [Solutions for constraints](#g)


<div name = 'x'/>

## Introduction to IDDPS (Impared Driver Detection and Prevention System)

#### The main aim of this project was to create a prototype app on a phone that could detect drunk/drugged people before driving, and distracted driving while driving. The plan was to have users use the phone first to detect that they were not drunk, and then allow them to drive. After they passed the first portion, the plan was to have the user place the phone in a mount to the right of them, and our app would use the phone camera to detect if they were distracted, and if they were, we would send an alert.

#### We used Flutter for the frontend of the app, and FastAPI for the backend. The computer vision is all built in TensorFlow in Python

<div name = 'y'/>

## What was my role?

#### I worked on a project called the IDDPS (Impared Driver Detection and Prevention System). The main aim of this project is to reduce traffic accidents that are caused by distracted drivers which can be texting, drunk and the like.

#### I worked on a team called CV3 (```as a Team Lead and Software engineering intern```), which is basically one of three machine learning teams that works on making models that will detect dsitracted drivers during the driving. In our case, these srivers are usually texting, not focusing on the road or not paying attention to their frontal view.  This team took the reactive approach to distracted driver detection meaning we will notfiy users when they appear to be distracted(other ML teams work on preventive procedures, like for drunk drivers).


<div name = 'z'/>

## How was the IDDPS implemented?

#### The main aim of the IDDPS team was to make a prototype application using flutter which has a machine learning model which will later be used in a raspberry pi type of system where insurance companies can use so that can maximise their profit. After the prototype is tested, the system will be deployed to better embedded systems that will have the power to scan the iris and determine if one is drunk or not or even slow down car if drivers are distracted.

<div name = 'a'/>

## What type of models where used?
    - Inception Model
    - VGG model
    - ResNet model
    - MobileNet Model

<div name = 'b'/>

## What programming language and platfrom was used to design and train this models?
    - 🐍 Python
    - ⚙️ Google Colab
 

<div name = 'c'/>

## What data set was used to train the Models?
<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/thumb76_76.png width= 70> 

|Name|Kaggle Link|
|-----|--------------------|
|StateFarm Dataset | https://www.kaggle.com/c/state-farm-distracted-driver-detection/data|


<div name = 'D'/>

## Some sample outputs (images that models where able to identify successfully)

|Photo| Identification Output|
|----------|------------------|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/1.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/01.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/2.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/02.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/3.jpg width = 250>|<img src =https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/03.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/4.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/04.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/5.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/05.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/8.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/06.jpg width = 250>|

<div name = 'e'/>

## What were the final numbers?
- We were able to get a training acuuracy of 99% and validation accuracy of 62%

<div name = 'f'/>

## What were some constraints while training these models?
- The main issues we faced for machine learning was the overfitting of the models. Originally, our models were overfitting on the single dataset, and when training them on one dataset, and testing on another, they performed even worse. 
- limited computation was an important factor while training models because personal computers and laptops were predominantly used. Epochs would take long and repeated trainings would take about 2-3 hours sometimes. Uploading the dataset to Google colab was also a problem we face.

<div name = 'g'/>

## What solutions where used?
-  We overcame overfitting by applying a few different techniques. The first approach we took was applying data augmentation to training data, and continuing to fine-tune the models. After that, to improve the models even more, we used foreground segmentation to remove the background of the images, and keep only the driver. This allowed us to make more accurate predictions because the model was only seeing the person.
-  We used the Kaggle API to upload our datasets to Google Colab. This reduced the time it takes to uplaod our datasets to a great extent.
