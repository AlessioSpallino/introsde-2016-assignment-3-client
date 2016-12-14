**Client Assignment 3 | University of Trento**

SOAP Web Services

## Client

* ```introsde.document.client```: it contains all the files in order to make requests to my server;
* ```introsde.document.ws```: it contains all the generated files with wsimport of my server;

## Configuration files

* ```build.xml```: it contains all the targets to run the code;
* ```ivy.xml```: it contains all the dependencies needed to run the project and it downloads them.

## Setup

In order to clone the project and run it against the server deployed on Heroku:
* ```git clone https://github.com/AlessioSpallino/introsde-2016-assignment-3-client.git```

#### How to run the client
 
My server wsdl file is at: https://pure-shelf-14716.herokuapp.com/ws/people?wsdl  
 
Working with it:
* ```cd introsde-2016-assignment-3-client```
* ```ant execute.client```
