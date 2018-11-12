# Linux Project

# Server Information
- **IP Address** needed is 18.188.85.112
- **URL** is 18.188.85.112.xip.io
- **SSH Port** 2200

# Installation of Dependancies
- **Linux Users** To install dependancies open the pg_confih.sh file that is a part of this applications package.

- This Program is designed for Python 2.7 you must go to the website @ https://www.python.org/download/releases/2.7/
Select the proper installer for your machine.

- To Install the Flask Application: Open your Terminal and enter "pip install Flask". Installation Documentation can be found @ http://flask.pocoo.org/docs/1.0/installation/

- To Install the SQLAlchemy application: Open your Terminal and enter "pip install SQLAlchemy".
Documentation can be found here https://docs.sqlalchemy.org/en/latest/intro.html

- After downloading the Files, extract them to a known location. Run the File named **"db_setup"** to setup the database for the application's use. This will create a SQL database File named **"categorywithusers.db".** This file will hold your data from the Flask application.

## **Running the Program**

- Once the **"db_setup.py"** file has been ran and you have located the database file you can set up the Flask Application. 
- To initiate the flask run the File named **"ItemCatalog.py"**.

## **Usage**

- The Application will Seperate data into Categories or Items within a Category.
- Each Category has a JSON Endpoint for WebScraping.
- The Templates Folder located within the Downloaded files provide the HTML endpoints for the Web Application.
- The Static Folder located within the Downloaded Files provides the Images and CSS for the Web Application.

# **Special Thanks**

- Amazon Lightsail is used to host this server

- Udacity.com Full Stack Web Development Program for the large amount of resources and videos about each topic.

- Markdown Guide from Udacity.com for writing a detailed document for readers.