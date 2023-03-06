# database_project
Incorporation of CRUD functionalities with web-based UI and database
* This project incorporates 5 SELECT, 5 INSERT, 5 UPDATE, and 4 DELETE queries.
* This project is adapted from the flask-starter-guide provided by the class: https://github.com/osu-cs340-ecampus/flask-starter-app 


<br>

There are 4 major entity tables and one intersection table: 
* pastries - a record of all the pastries available at Lucky Bakery
* chefs - a record of the present chefs at Lucky Bakery
* customers - a record of all the current and potential customers
* orders - a record of all past orders
* order_details (intersection table) - a transaction table between orders and pastries giving details of each order.

<br>

# USUAGE
user must have python-dotenv download and an .env with the following credentials:
* 340DBHOST='classmysql.engr.oregonstate.edu'
* 340DBUSER=cs340_[username]
* 340DBPW=XXXX
* 340DB=cs340_[username]

# pages:
* Homepage
* Pastries:
  * SELECT, INSERT, UPDATE
* Chefs
  * SELECT, INSERT, UPDATE, DELETE
* Customers
  * SELECT, INSERT, UPDATE, DELETE
* Orders
  * SELECT, INSERT, UPDATE, DELETE
* Order Details
  * SELECT, INSERT, UPDATE, DELETE
* Citation:
  * Source: https://github.com/osu-cs340-ecampus/flask-starter-app
  * ADAPTED FROM: Flask-Starter-Guide
  * Templates/Pages:
    * HTML organization, Input organization, Table organization, app.py oraganization
  * References Flask-Starter-Guide
    * How to configure db_connector.py to load project
  * Date: 3/6/23


