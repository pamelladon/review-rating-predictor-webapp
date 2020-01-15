# Review Ratings Predictor Web Application
Author: Xavier M. Puspus

### Description

[Click this link to explore the web application hosted in Heroku.](https://review-rating-predictor.herokuapp.com/)  


I used a sample dataset on insurance pricing and built a simple web application with a machine learning backend to see live changes to predicted/suggested prices based on changes in input data.

### Data

You can get the [data](https://www.kaggle.com/nicapotato/guided-numeric-and-text-exploration-e-commerce/data) here.
 
### Model

I only used a low-order machine learning technique for demo purposes. The web app's backend can work for more complex models.

### Deployment Through Web Application

I used the most recently released API of [Streamlit](https://streamlit.io) to deploy the ml model and locally serve the web app.

### Running the App

In order to run the app, you must have the basic data science packages available on your machine, (`pandas`, `numpy`, `seaborn`, `matplotlib`, `sklearn`) and install streamlit using:  

```console
foo@bar:~$ pip install streamlit
```

Checkout the `requirements.txt` file for installation specs. You can install packages needed for this repo through:

```console
foo@bar:~$ pip install -r requirements.txt
```

Afterwards, `cd` into the directory of `app.py` and run this on the terminal:  

```console
foo@bar:~$ streamlit run app.py
```

### Display

The web app should look something like this:

![Sample image of the review ratings predictor web application.](review_ratings_image.png)