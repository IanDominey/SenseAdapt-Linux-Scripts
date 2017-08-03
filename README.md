# SenseAdapt-Linux-Scripts

## Installation
To use this application, you will need to have [Docker](http://www.docker.com) installed on the server

## Configuration
Place the ```license.lic``` file in the```App_Data``` directory.

In the ```config``` directory, you will need to supply your configuration files. 
 * ``visualisation.config``
 * ``NLog.config``
 * ``Web.config``
 
Note, if these files are not present, the container **will not** run.
Also, note that SenseAdapt databases will be created under ``App_Data``

## Running the application
To run the application, use``docker-compose up``

If you want to run the application in the background, use ``docker-compose up -d`` 


