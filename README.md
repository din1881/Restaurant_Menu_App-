# Item Catalog Web App (Restaurant Menu App)

This web app is the second project for the Udacity [FSND Course](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).

## About this project

This is a RESTful web application using the Python framework Flask along with implementing third-party OAuth authentication. In this project I use the various HTTP methods and relate them to CRUD (create, read, update and delete) operations.

## Skills Required
1.Python
2.Flask Framework
3.SQL database
4.AJAX
5.Json
6.HTML
7.CSS
8.OAuth

## How to run the program?
1.  _First of all, it's adviced that you use a virtual machine. So Please download Vagrant and VirtualBox to manage your Virtual machine. To bring up your virtual machine use  `vagrant up`  and  `vagrantt ssh`  to log in._
2. The Vagrant file is present in this repo.
3.  _Use  `cd /vagrant`  to access your shared files._
4.   Initialize the database
```$ Python database_setup.py```
5.  Populate the database with some initial data
```$ Python lotsofmenus.py```
6. Run your Application
```$ Python project.py```
7. Access the application locally using [http://localhost:5000](http://localhost:5000/)

## JSON Endpoints
#### Route for returning JSON for all restaurants
```/restaurant/JSON ```

#### Route for returning JSON of menu
```/restaurant/<int:restaurant_id>/menu/JSON ```

#### Route for returning JSON of specific menu item
```/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON ```


