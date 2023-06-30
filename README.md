# Phone-book-Application-with-python
Flask application that connects to a MySQL database and provides CRUD (Create, Read, Update, Delete) functionality for managing contacts. Simple GUI Application for Contact Manager.

CRUD (Create, Read, Update, Delete) functionality is offered by a Flask application that connects to a MySQL database and is used to manage contacts.
Simple contact manager GUI application.

We need to import the required modules Flask and MySQL.connector in order to build the web application and connect to the MySQL database, respectively.

Using the supplied credentials, the function connect_to_database() creates a connection to the MySQL database.

A route /index that makes a database table query and displays the results in the index.html template.

A /c route that accomplishes the same thing as /index but displays the data in the c.html template.

/search is a route that enables users to look up contacts by name and renders the results in the search.html template.

A route /add that manages to create new routes
simple phone application with python,flask,mysql,html . data saved in database and we can search saved phone number by name .
