# cs50-finance

## Another fun and exciting project: I built a full-stack web app with Bootstrap UI, Flask back-end, and SQLite3 database.

# Description
<img src='https://user-images.githubusercontent.com/58123635/121849668-9eca3480-ccb9-11eb-9b1a-4f1040cd3b6e.png' height='300px' />
<img src='https://user-images.githubusercontent.com/58123635/121849797-cfaa6980-ccb9-11eb-806c-073d6730ea0c.png' height='300px' />
<img src='https://user-images.githubusercontent.com/58123635/121849824-d9cc6800-ccb9-11eb-87e2-afe2aa7243bd.png' height='300px' />
<img src='https://user-images.githubusercontent.com/58123635/121849696-abe72380-ccb9-11eb-8bd1-656effeab191.png' height='300px' />
<img src='https://user-images.githubusercontent.com/58123635/121849719-b7d2e580-ccb9-11eb-8f11-3d8a4d92ba29.png' height='300px' />
Transaction history
<img src='https://user-images.githubusercontent.com/58123635/121849877-e9e44780-ccb9-11eb-85b2-4548e91d2db1.png' height='300px' />
Orders table
<img src='https://user-images.githubusercontent.com/58123635/121850000-1dbf6d00-ccba-11eb-8830-fc6054a27919.png' height='300px' />


# Tools and Technologies:
	• cs50
	• Flask
	• VS Code
	• Flask session
	• SQLite


# RUN:

First, you will need to get an API key from [IEX](iexcloud.io/cloud-login#/register/) (free account registration), which lets you download stock quotes via their API (application programming interface) using URLs like https://cloud.iexapis.com/stable/stock/nflx/quote?token=API_KEY

With the API, run the following within a CS50 IDE's terminal: $ export API_KEY=value (value is your acquired personal API KEY)

Start Flask’s built-in web server:
$ flask run

## In this pset, I have implemented:
- App Features: register, quote, buy, index, sell, history
- most of html templates (lots of Jinja dynamic content generation) and their UIs
- application.py (lots of routing, logics, and Sqlite3 QUERIES)
- Design an `orders` table to keep track of all stock transactions by all users. It is stored in finance.db

Flask app file structure:
	• application.py
	• static/
	• templates/
