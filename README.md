# Bikes_Catalogue
## udacity-item-catalogue
This is my project for Udacity's catalogue app project. It is a CRUD implementation using python and it does oauth2 authentication, while also having the editing and deleting capabilities blocked by anyone who did not create the material. The exception to this rule is if the owner of a category decides to delete it, then it will also delete all of the items in that category from the database.

## Steps To Run:

You will need to have Python installed. Which can be obtained from: https://www.python.org/downloads/ The version used when writing this code was Python 2.7.15

Using a vagrant configuration
You  need to install virtual box which can be downloaded from the link: https://www.virtualbox.org/wiki/Downloads

You  need to install vagrant which can be found in the link: https://www.vagrantup.com/downloads.html

You  need the vagrant environment that can be downloaded from the link: https://github.com/udacity/fullstack-nanodegree-vm

## Connecting to vagrant
Once you have the environment ready you have to locate the vagrant environment in your terminal and then use the command: vagrant up which will boot up the vagrant environment on your machine.

Then you can be able to connect to it using: `vagrant ssh`

Once ssh'd into the vagrant instance is created you need to change to the directory with the python file. `cd /vagrant`

## Files needed to run vagrant
Insert this repository into the vagrant folder. You can use your normal desktop environment to do this. Putting these files into the vagrant folder will allow you to use them from the terminal while being ssh'd to the virtual machine instance.

Database
The database is already initialized and pre-filled with some data. If you wish to start from scratch you may delete the Biketypes.db file and then run: python databse_setup.py in the terminal to start cleanly.

Procedure to run the code:
Once your environment is setup: All you need to do is run the project.py file through the python interpreter.

final project.py

## Output
 Now open your browser and go to localhost:5000 You can add Bike categories and Bike models after you login using `Google sign-in`. Any Bike category or Bike model that you created you also have the ability to edit and delete, but you will be prevented from being able to edit or delete any data that you don't create personally.
