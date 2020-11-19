# Recipe Web-App

Clean interface that allows users the ability to search from over 365,000 recipes. 

Currently available at: https://myrecipe-master.herokuapp.com/

# Instructions

### Obtain Spoonacular API
  https://rapidapi.com/spoonacular/api/recipe-food-nutrition
  
  Replace "API-KEY-HERE" with assigned key.

### Environment Setup

Create and activate a new Anaconda virtual environment:

```sh
conda create -n recipe-env python=3.7 (first time only)
conda activate recipe-env
```

From within the virtual environment, install the required packages specified in the "requirements.txt" file:

```sh
pip install -r requirements.txt
```
### FLASK

To open and run the website locally on your computer, use the following command:

```sh
FLASK_APP=web_app flask run
```

To visit the website while runninig locally, enter the followinig into your browser:

```sh
http://127.0.0.1:5000/
```
