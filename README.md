* Building a web scrapping app with Python Flask/Django using MVC

# IT Jobs Watch Data

## Introduction
* The aim of this project is to create a simple service that can scrape useful data from ITJobswatch.

## Current Scope

1. Home page top 30 job/roles / skills which can be found on
![](https://www.itjobswatch.co.uk/)

The aim will be to expand this to further services such as:

* Regular polling of pages and writing to a database/CSV for longer terms stats
* Bespoke calls for specific job role data

And much more.

## Usage
_Pre-Requisites_
* Pycharm IDE
* Python 3.x + installed

### Installing packages
* The necessary packages needed to run this program should automatically be picked up by pycharm. You may find a a few pop ups within the IDE that state there are dependencies missing, if you simply install these through the IDE you should be set up correctly.  

### TDD to build tests
* All tests must pass

### Building front end using flask or Django to display jobs in the web browser

* Follow the instructions to download via the various options given.

#  Steps
* Adding a job details search option (essentially be able to search for a specific role and return the details in a CSV)
* create a connected database for full deployment
* Build a scheduler as part of a full deployment to poll and add to the database 
* deploy the app using dev env with Vagrant
* implement reverse proxy so the app can be loaded in the browser without the port
* automate deployment steps with provisioning script so with vagrant up command we should be able to deploy the app and access it in the browser

