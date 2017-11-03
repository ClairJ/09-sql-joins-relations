
# Project Name SQL-Joins-Relations

**Author**: Joel Clair & Will Reid
**Version**: 1.0.0

## Overview
This codebase allows a user to build and maintain a blog called Kilovolt, initializing with 250 articles.  In today's release, the user will be able to create articles in a new.html page and have them added to a DB in a postgresql environment on the model which can be served back to the viewer by way of the controller.  The connections should allow the user to perform the full CRUD cycle, including modifying existing articles and destroying them.

## Getting Started
The technical user must fork and clone the repo to their local machine.  To run the site, a user must install the dependancies: postgresql, express, body-parser and pg.  Once the site is deployed to production, a non-techincal user should be able to make front-end updates without dependancies since they would be handled in the runtime environment.

## Architecture
The site is framed on HTML pages with normalized CSS and mobile-first design, and with page content (including dynamic filtering) provided by JS and jQuery.  The article data and article author data are stored in a postgresql environment in separate, joined tables.

## Change Log
10:00am 11/3/17 -- updating conString for psql connections
11:00am 11/3/17 -- updating SQL query syntax for Create Table, Insert Into, Joins
12:00pm 11/3/17 -- updating SQL query syntax for Delete article by id, Delete all articles
1:00pm 11/3/17 -- finishing conString connection and ReadMe.
```
