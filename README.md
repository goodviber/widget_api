# README

## Project information

Lawbite has decided to branch out into the Widget market. We require a new API to serve our client facing inventory application.

The application currently has:

* A Sqlite3 database
* RSpec is installed
* A Widget model
* A Widgets table


## Tasks

* Extend the api to respond as a read only RESTfully for widgets within ‘/api/v1/’:
    * Return a list of widgets as JSON.
* Extend so widgets have a list of widget items:
    * Name, Description.
* Implement search functionality with:
    * Widgets by name.
    * WidgetItems by created_at date range.
* Discuss any trade offs made.
* Discuss how you would implement API security.
* Discuss picking an appropriate database if this was a real project.
    * E.g. mongo, vs, mysql vs ...
* Discuss what tools/gems you normally use in a project by standard.
    * E.g. dot-env etc.
* Discuss using middleware to throttle API requests.
* Please implement TDD.
