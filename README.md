# CarPricePrediction
## Table Of Content
..* [Demo][1]





## Demo
[![Front-End view of the app car prediction](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(114).png "Outloook")]   
[![Front-End view of the app car prediction](https://github.com/hitesh0103/Images/blob/main/Screenshot%20(113).png "Outloook")] 

Link:<https://carprediction123.herokuapp.com/>

## Overview
This is a simple Car Price Prediction APP.It takes in the 'year', the respective Car was purchsed on, the showroom price, the number of Kilometers driven, the number of owners that previously have had this car, the fuel type of the car, whether it is Petrol or Diesel. Transmission type and whether you are a dealer or not a dealer. Based upon this information entered by the user, it can predict the car price. The model has been trained on Random Forest Regression from scikit-learn library.

## Motivation
Welcome reader, so from past one year i have been actively planning and working upon my transition into data science. I started learning Python from youtube in the beginning of january this year and i am so very comfortable at using it now, that i have deployed this basic app on Heroku platform. So, i wish everybody best in their life and personal goals.

## Technical Aspect
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
