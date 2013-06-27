# Zscaler Candidate Evaluation UI Project

## Objective

Your goal is to build a simple CRUD-type web app that will be used to manage user accounts for some company.

## Requirements

The basic requirements for the app are covered in the provided mockups:

* mockup-1.png (user's table)
* mockup-2.png (add/edit user's dialog)

A simple REST API that you must integrate with has been provided:

* GET /api/users?search={contains}
* GET /api/users/{id}
* PUT /api/users
* POST /api/users/{id}
* DELETE /api/users/{id}
* GET /api/groups
* GET /api/departments

The app is already seeded with some test data using an in-memory datastore.

## Deploying the REST API

Instructions for deploying the web app to Apache Tomcat:

1. Follow the instructions [here](http://tomcat.apache.org/tomcat-7.0-doc/RUNNING.txt) to download and install Apache Tomcat.
2. Delete any existing directories in *{TOMCAT_INSTALL_LOCATION}/webapps*.
3. Copy *ROOT.war* to *{TOMCAT_INSTALL_LOCATION}/webapps*.
4. Run *{TOMCAT_INSTALL_LOCATION}/bin/startup.sh* (*startup.bat* on Windows) to start Tomcat.
5. While Tomcat is running, you can access the app at *http://localhost:8080*.
6. Stop Tomcat by running *{TOMCAT_INSTALL_LOCATION}/bin/shutdown.sh* (*shutdown.bat* on Windows).

## Testing Your Web Application

Place any HTML, JavaScript, and CSS files you create in *{TOMCAT_INSTALL_LOCATION}/webapps/ROOT* to test the front-end you build with the REST API.
You can add/modify web files in the ROOT directory while Tomcat is running; just refresh the browser to see your changes.