# Data Science Lifecycle: Collect, Clean, Predict &amp; Analyze your Data

## Workshop Resources

- Login/Sign Up for IBM Cloud: https://ibm.biz/CleanAndPredict 
  
- Hands-On Guide: https://ibm.biz/CleanAndPredict-HandsOn 

- Slides: https://ibm.biz/CleanAndPredict-Slides 

- Workshop Replay: https://www.youtube.com/watch?v=3DElV51FqL8

## Table of Contents
1. [Prerequisites](#Prerequisites)
1. [About the Workshop](#About-the-Workshop)
1. [Tutorial](#Tutorial)
  
## Prerequisites
  
### **Sign-up/Login to IBM Cloud**

If you are an existing user please [login to IBM Cloud](https://cloud.ibm.com/registration?utm_medium=Inpersondirected&utm_content=000039JL&utm_term=10010797&utm_id=Sep2021-datasciencelifecyclecollectcleanpredictanalyzeyourdata-eventid-6142e1a9e48d51644c391e14-global-devadvgrp-dubai-franchise-workshop-dubai)

And if you are not, don't worry! We have got you covered! There are 3 steps to create your account on [IBM Cloud](https://cloud.ibm.com/registration?utm_medium=Inpersondirected&utm_content=000039JL&utm_term=10010797&utm_id=Sep2021-datasciencelifecyclecollectcleanpredictanalyzeyourdata-eventid-6142e1a9e48d51644c391e14-global-devadvgrp-dubai-franchise-workshop-dubai): <br>
1- Put your email and password. <br>
2- You get a verification link with the registered email to verify your account. <br>
3- Fill the personal information fields. <br>
** Please make sure you select the country you are in when asked at any step of the registration process.
  
<img width="1188" alt="Screen Shot 2021-05-31 at 11 25 01 AM" src="https://user-images.githubusercontent.com/15332386/120156441-0769d980-c203-11eb-8cb3-29f4a8d5616a.png">


## About the workshop 
AutoAI is a capability that automates machine learning tasks to ease the tasks of data scientists. It automatically prepares your data for modeling, chooses the best algorithm for your problem, and creates pipelines for the trained models, and it can be run in public clouds and in private clouds, including IBM Cloud Pak for Data.

This tutorial explains the benefits of the AutoAI service on a use case. This will give you a better understanding of how regression and classification problems can be handled without any code — and how the tasks (feature engineering, model selection, hyperparameter tuning, etc.) are done with this service. This tutorial also includes details for choosing the best model among the pipelines and how to deploy and use these models via IBM Cloud Pak for Data platform.

Customer churn is an important aspect for any business, it gives them insights about their prospective customers. In this tutorial we will be predicting customer churn of car owners. We will be utilizing Watson data refinery to alter our data, and then use AutoAI to rapdliy develop a classfication machine learning model in a matter of minutes and predict our customer chrun.

## Architecture   

![Achitecture](/images/Architecture.png)

## Tutorial

### Step 1. Create Cloud Pak for Data as a Service (Watson Studio)
 On top of the page, you will see a search bar. Search for "Watson Studio". Watson Studio service will show up. Click on it, if you already have an instance of Watson Studio, it should be visible. If so, click it. If not, click Watson Studio under Catalog Results to create a new service instance.

![WS](https://github.com/IBMDeveloperMEA/Recurrent-Neural-Networks-using-TensorFlow-Keras/raw/main/images/select-watson-studio-service.png)

Select the type of plan to create if you are creating a new service instance. A Lite (free) plan should suffice for this tutorial). Click Create.

![WS2](https://github.com/IBMDeveloperMEA/Recurrent-Neural-Networks-using-TensorFlow-Keras/raw/main/images/watson-studio-lite-plan.png)

### Step 2. Create Object Storage

Search for "Object Storage". Object Storage service will show up. Click on it. If you already have an instance of Object Storage, it should be visible. If so, click it. If not, click Object Storage under Catalog Results to create a new service instance.

![ObS](https://github.com/fawazsiddiqi/WatsonSPSS/raw/main/images/ob1.png?raw=true)
![ObS2](https://github.com/fawazsiddiqi/WatsonSPSS/raw/main/images/ob2.png?raw=true)

### Step 3. Create a Watson Machine Learning Service instance

To create a Watson Machine Learning instance, search for Machine Learning and create a lite instance. If you already have an instance of Machine Learning, it should be visible. If so, click it. If not, click Machine Learning under Catalog Results to create a new service instance.

![ML1](https://github.com/fawazsiddiqi/WatsonSPSS/raw/main/images/wml1.png?raw=true)
![ML2](https://github.com/fawazsiddiqi/WatsonSPSS/raw/main/images/wml2.png?raw=true)

### Step 4. Download/Clone the repository

``` git clone https://github.com/IBMDeveloperMEA/Data-Science-Lifecycle-Collect-Clean-Predict-Analyze-your-Data```

To download this repository, click [here](https://github.com/IBMDeveloperMEA/Data-Science-Lifecycle-Collect-Clean-Predict-Analyze-your-Data/archive/refs/heads/main.zip) Or click on the green code icon, and download the ZIP file. You will need the repository for the data that is required for this tutorial.

![Download](/images/download_repo.png)

### Step 5. Create a new project

## Workshop Resources

- Login/Sign Up for IBM Cloud: https://ibm.biz/CleanAndPredict 
  
- Hands-On Guide: https://ibm.biz/CleanAndPredict-HandsOn 

- Slides: https://ibm.biz/CleanAndPredict-Slides 

- Workshop Replay: https://www.youtube.com/watch?v=3DElV51FqL8

## Reference Links
  
## Done with the workshop? Here are some things you can try further

## Authors
