# Astrophysics Dashboard

## About
 A dashboard style web application for visualizing astrophysics data, to aid in exoplanets discovery.
 
 This application is similar to one I made for the Institute of Astrophysics and Space Sciences / Astrophysics Centre of the University of Porto. Comparing to the original one, this application has some details modified to not use their intellectual property. The original one accesses their API for data, whilst this one uses a different data source.
 
 Made in Python, it uses Plotly Dash for the data visualization elements and UI, Pandas for data manipulation, Flask microframework as the web server gateway interface (WSGI). It uses Jinja, HTML, JavaScript, and is styled with Bootstrap 5 and CSS.

 <img width="500" alt="screenshot" src="https://github.com/carlahnr/astrophysics_dashboard/assets/100738389/47cd75de-242d-4be5-a757-371efa21eff8">

## Project Setup

### General setup
 The app contains 3 views:
 - **Home view:** description of the app.
 - **Dashboard view:** main funcionality view, with all data visualization resources.
 - **Sourcepath management view:** view to add and remove sourcepaths to the Dashboard.

### Directories distribution
 - **/ :** root directory of the project, with the python application. Also contains the project's metadata files, and configuration files.
 - **/static :** all static assets, such as images, icons, javascript files and css files.
 - **/templates :** templates for the views using mainly HTML and Jinja.

### Techstack
 - Flask
 - Plotly Dash
 - Pandas
 - Bootstrap 5

## Dependencies

### Getting Started with Plotly Dash
[Plotly Dash](https://dash.plotly.com/installation) framework is used for data visualization UI items.

### Getting Started with Flask
Web framework in [Flask](https://flask.palletsprojects.com/en/3.0.x/installation/#install-flask).

### Getting Started with Pandas
Data manipulation uses [Pandas](https://pandas.pydata.org/getting_started.html).

### Getting Started with Bootstrap
Styled with [Bootstrap 5](https://getbootstrap.com/docs/5.2/getting-started/download/) and [Dash Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/docs/).
