<img src= https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/TechForGood_Logo.png.webp width = 200>


# Tech For Good Inc - Summer Internship 2021

## Introduction to IDDPS (Impared Driver Detection and Prevention System)

#### I worked on a project called the IDDPS (Impared Driver Detection and Prevention System). The main aim of this project is to reduce traffic accidents that are caused by distracted drivers which can be texting, drunk and the like.

#### I worked on a team called CV3, which is basically one of threee machine learning teams that works on making models that will detect dsitracted drivers during the driving. In our case, these srivers are usually texting, not focusing on the road or not paying attention to their frontal view.  This team took the reactive approach to distracted driver detection meaning we will notfiy users when they appear to be distracted(other ML teams work on preventive procedures, like for drunk drivers).

## How was the IDDPS implemented?

#### The main aim of the IDDPS team was to make a prototype application using flutter which has a machine learning model which will later be used in a raspberry pi type of system where insurance companies can use so that can maximise their profit. After the prototype is tested, the system will be deployed to better embedded systems that will have the power to scan the iris and determine if one is drunk or not or even slow down car if drivers are distracted.


## What type of models where used?
    - Inception Model
    - VGG model
    - ResNet model
    - MobileNet Model

## What programming language and platfrom was used to design and train this models?
    - 🐍 Python
    - ⚙️ Google Colab
   
## What data set was used to train the Models?
<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/thumb76_76.png width= 70> 

|Name|Kaggle Link|
|-----|--------------------|
|StateFarm Dataset | https://www.kaggle.com/c/state-farm-distracted-driver-detection/data|


## Some sample outputs (images that models where able to identify successfully)

|Photo| Identification Output|
|----------|------------------|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/1.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/01.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/2.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/02.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/3.jpg width = 250>|<img src =https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/03.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/4.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/04.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/5.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/05.jpg width = 250>|
|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/8.jpg width = 250>|<img src = https://github.com/Nlege001/ReactiveRiskIdentification/blob/main/06.jpg width = 250>|


## What were the final numbers?
- We were able to get a training acuuracy of 99% and validation accuracy of 62%

## What were some constraints while training these models?
- limited computation was an important factor while training models because personal computers and laptops were predominantly used. Epochs would take long and repeated trainings would take about 2-3 hours sometimes. Uploading the dataset to Google colab was also a problem but using the Kaggle API solves this.
