# Astrophysics Dashboard

![Flask](https://img.shields.io/badge/flask-red?style=for-the-badge&logo=flask) 
![Pandas](https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-css3-1572B6?&style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap5](https://img.shields.io/badge/bootstrap-%237952B3?style=for-the-badge&logo=pandas&color=%237952B3)


## Table of Contents
 - [About](#about)
 - [Project Setup](#project-setup)
 - [Dependencies](#dependencies)

## About
 A dashboard style interactive web application for visualizing astrophysics data, to aid in exoplanets discovery.
 
 This application is similar to one I made for the Institute of Astrophysics and Space Sciences / Astrophysics Centre of the University of Porto. Comparing to the original one, this application has some details modified to not use their intellectual property. The original one accesses their API for data, whilst this one uses a different data source.

 <img width="500" alt="screenshot" src="https://github.com/carlahnr/astrophysics_dashboard/assets/100738389/47cd75de-242d-4be5-a757-371efa21eff8">

## Project Setup

### General GUI setup
 The app contains 3 views:
 - **Home view:** description of the app.
 - **Dashboard view:** main funcionality view, with all data visualization resources.
 - **Sourcepath management view:** view to add and remove sourcepaths to the Dashboard.

### Directories structure
 - **/ :** root directory of the project, with the Python application. Also contains the project's metadata files, and configuration files.
 - **/static :** all static assets, such as images, icons, Javascript and CSS files.
 - **/templates :** templates for the views using mainly HTML and Jinja.

### Techstack
 Made in Python, it uses Plotly Dash for the data visualization elements and UI, Pandas for data manipulation, Flask microframework as the web server gateway interface (WSGI). It uses Jinja, HTML, JavaScript, and is styled with CSS (Bootstrap 5 and Dash Bootstrap). For more details, see [Dependencies](#dependencies).
 
 - Python (3.9.18)
 - Flask
 - Plotly Dash
 - Pandas
 - Bootstrap

## Dependencies

### Getting Started with Plotly Dash
[Plotly Dash](https://dash.plotly.com/installation) framework is used for data visualization UI items. Using Plotly (5.22.0) and Dash (2.17.1).

### Getting Started with Flask
Web framework used was [Flask](https://flask.palletsprojects.com/en/3.0.x/installation/#install-flask) (3.0.2). Application uses [Jinja](https://jinja.palletsprojects.com/en/3.1.x/intro/#installation) (3.1.3) templating.

### Getting Started with Pandas
Data manipulation uses [Pandas](https://pandas.pydata.org/getting_started.html)  (2.2.2).

### Getting Started with Bootstrap
Styled with [Bootstrap 5](https://getbootstrap.com/docs/5.2/getting-started/download/). Also uses [Dash Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/docs/) (1.6.0) and [Dash Bootstrap Templates](https://pypi.org/project/dash-bootstrap-templates/) (1.1.2).
