Crud generator
======

This is a module that will create a crud for your table in Codeigniter hmvc.

All you need to do is:

    - Setup your database(config/database.php),
    - Set an encryption key(config/config.php)->['encryption_key'] ='Whatever';.
    - Copy the module "crud" into "modules" folder. 
    - Point your browser to yourdoain/crud.


The script checks if the fields in your table are int,email or varchar and sets the specific validations.
If you have created and modified columns(int type). it will automaticly add the timestamp when created and modified on add and edit and it will display them in a date forma on index.

This script will work only in HMVC CODEIGNITER 
	It will create a module with the following structure and populate the files with the required code based on you sql table selection.

		tablename
			controllers
				tablename.php
			models
				tablename_model.php
			views
				add.php
				edit.php
				index.php
				view.php


Donations-paypal mainerici.angel@gmail.com