# CarPricePrediction
## Table Of Content
* [Demo](https://github.com/hitesh0103/CarPricePrediction#Demo)
* [Overview](https://github.com/hitesh0103/CarPricePrediction#Overview)
* [Motivation](https://github.com/hitesh0103/CarPricePrediction#Motivation)
* [Technical Aspects](https://github.com/hitesh0103/CarPricePrediction#Technical Aspects
* [Installation](https://github.com/hitesh0103/CarPricePrediction#Installation)
* [Deployment on Heroku](https://github.com/hitesh0103/CarPricePrediction#Deployment on Heroku)
* [Bug/Feature Request](https://github.com/hitesh0103/CarPricePrediction#Bug/Feature Request)
* [Technologies Used](https://github.com/hitesh0103/CarPricePrediction#Technologies Used)





## Demo 
![Front-End view of the app car prediction](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(114).jpg "Outloook")  ![Front-End view of the app car prediction](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(113).jpg "Outloook")
 

Link:<https://carprice44.herokuapp.com/>

## Overview
This is a simple Car Price Prediction APP.It takes in the 'year', the respective Car was purchsed on, the showroom price, the number of Kilometers driven, the number of owners that previously have had this car, the fuel type of the car, whether it is Petrol or Diesel. Transmission type and whether you are a dealer or not a dealer. Based upon this information entered by the user, it can predict the car price. The model has been trained on Random Forest Regression from scikit-learn library.

## Motivation
Welcome reader, so from past one year i have been actively planning and working upon my transition into data science. I started learning Python from youtube in the beginning of january this year and i am so very comfortable at using it now, that i have deployed this basic app on Heroku platform. So, i wish everybody best in their life and personal goals.

## Technical Aspects
1. Training a RandomForestRegression model from scikit-learn API.
2. Creating a Web App using Flask and deploying the app on Heroku.
   * The Web App asks for basic details such as Fuel-type, the date of purchase.
   * Based upon the training predicts the price of the car.

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```python
pip install -r requirements.txt
```
## Run
> Step 1.
### Linux and macOS User
Open ```.bashrc``` or ```.zshrc``` file and add the following credentials:
   ```
   export AWS_ACCESS_KEY="your_aws_access_key"
   export AWS_SECRET_KEY="your_aws_secret_key"
   export ICP_BUCKET='your_aws_bucket_name'
   export ICP_BUCKET_REGION='bucket_region'
   export ICP_UPLOAD_DIR='bucket_path_to_save_images'
   export ICP_PRED_DIR='bucket_path_to_save_predictions'
   export ICP_FLASK_SECRET_KEY='anything_random_but_unique'
   export SENTRY_INIT='URL_given_by_sentry'
```

> Step 2.
To run the app in a local machine, shoot this command in the project directory:

```web: gunicorn app:app```

## Deployment on Heroku
To deploy the model on Heroku I first created a Repository on GitHub with all the relevant files that are requied. Including the HTML file for the front-end.
The window of Heroku looks something like this.

![Fist window of Heroku Platform](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(152).png "Outloook")

#### This will create new App
1. Click on the new Button.
2. Click on create new App.


![Click on Connect to GitHub](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(153).png "Outloook")

#### This will connect your GitHub Repository to Heroku platform.
> After this, **DEPLOY** Button can be clicked to deploy the model.


## Bug/Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/hitesh0103/CarPricePrediction/issues) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/hitesh0103/CarPricePrediction/issues). Please include sample queries and their corresponding results.

## Technologies Used
![LOgo](https://github.com/hitesh0103/Images/blob/main/carpredLogo/1200px-Scikit_learn_logo_small.svg.jpg "Outloook")
![LOgo](https://github.com/hitesh0103/Images/blob/main/carpredLogo/flask%20logo.jpg "Outloook")
![LOgo](https://github.com/hitesh0103/Images/blob/main/carpredLogo/main-qimg-28cadbd02699c25a88e5c78d73c7babc.jpg "Outloook")


___
___





## Deployment By
**Hitesh Sharma:**
![Profile](https://github.com/hitesh0103/Images/blob/main/Profile%20picture%20compressed.JPG "Outloook")






