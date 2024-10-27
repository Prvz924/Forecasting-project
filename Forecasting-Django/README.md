[//]: # (The project is based on Data Science and Django and available at https://github.com/Prvz924/Forecasting-project
  
)


## Goal
<p> 
  To forecast stock data and develop a web application
</p>


  
## Tech stack Used:

<p>HTML</p>
<p>CSS</p>
<p>JAVASCRIPT</p>
<p>PYTHON</p>
<p>DJANGO</p>

## Data
<p> 
  Real time stock data using API
</p>



## Prerequisites:
```bash
  Django==3.2.6
  django-heroku==0.3.1
  gunicorn==20.1.0
  matplotlib==3.5.2
  matplotlib-inline==0.1.3
  numpy==1.23.0
  pandas==1.4.1
  pipenv==2022.6.7
  plotly==5.9.0
  requests==2.28.1
  scikit-learn==1.1.1
  scipy==1.8.1
  seaborn==0.11.2
  sklearn==0.0
  virtualenv==20.14.1
  virtualenv-clone==0.5.7
  yfinance==0.1.72
```

## Project Installation:
**STEP 1:** Clone the repository from GitHub.
```bash 
  git clone https://github.com/Prvz924/Forecasting-project
```

**STEP 2:** Change the directory to the project.
```bash
  cd Forecasting-Django
```

**STEP 3:** Create a virtual environment
(For Windows)
```bash
  python -m venv virtualenv
```
(For MacOS and Linux)
```bash
  python3 -m venv virtualenv
```

**STEP 4:** Activate the virtual environment.
(For Windows)
```bash
  virtualenv\Scripts\activate
```
(For MacOS and Linux)
```bash
  source virtualenv/bin/activate
```

**STEP 5:** Install the dependencies.
```bash
  pip install -r requirements.txt
```

**STEP 6:** Migrate the Django project.
(For Windows)
```bash
  python manage.py migrate
```
(For MacOS and Linux)
```bash
  python3 manage.py migrate
```

**STEP 7:** Run the application.
(For Windows)
```bash
  python manage.py runserver
```
(For MacOS and Linux)
```bash
  python3 manage.py runserver
```


## Output Screen-shots:
The Home page of the application that displays real time data of stock prices.
![image](/img1.png)

To Predict stock price we move on to predicition page where we need to enter valid ticker value and number of days and click predict button.
![image](/img2.png)

This page displays the predicted stock price alsong with searched ticker details and also generating unique QR Code to view the predicted result.
![image](/img3.png)

The Left Graph is the real time stock price of the searched ticker for past 1day & the Right Graph is the predicted stock price for the number of days searched.
![image](/img4.png)

The Ticker Info page displays the details of all the valid tickers accepted by the application.
![image](/img5.png)





