[![Build Status](https://travis-ci.org/kaguna/CP2-yummy-recipes.svg?branch=master)](https://travis-ci.org/kaguna/CP2-yummy-recipes)
[![Coverage Status](https://coveralls.io/repos/github/kaguna/CP2-yummy-recipes/badge.svg?branch=master)](https://coveralls.io/github/kaguna/CP2-yummy-recipes?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/80bf253aa68f42b994e737ef2607d944)](https://www.codacy.com/app/kaguna/CP2-yummy-recipes?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kaguna/CP2-yummy-recipes&amp;utm_campaign=Badge_Grade)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/kaguna/CP2-yummy-recipes/blob/master/license.txt)

# Yummy-Recipes

Yummy-Recipes is an app that manages users recipes. User can create an account. Using the credentials, 
the user can login to access the dashboard where registration of the categories take place.
All operations on the category are displayed. Click **view** to open the recipe under the 
category created. Once on the recipes page of the specific category, you can create a recipe 
by providing *recipe name* and the *procedure* to prepare the recipe.
While on the recipes page you can *view*, *update* or *delete* the recipe.
#### Contains

The application contains the user interfaces for the Yummy-Recipes which are contained in 
the designs directory,

UML diagrams for the Project contained in the UML directory

The falsk application for Yummy-Recipes contained in the app directory

#### Prerequisites

Python 3.6 or a later python version is required to run this app.

#### Installing
clone the repository

FOR HTTPS:
https://github.com/kaguna/Yummy-Recipes

FOR SSH: 
git@github.com:kaguna/Yummy-Recipes.git

#### Change Directory into the project folder

`$ cd Yummy-Recipes`

#### Create a virtual environment with Python 3.6

`$ virtualenv --python=python3.6 yourenvname`

#### Activate the virtual environment you have just created

`$ source yourenvname/bin/activate`

#### Install the application's dependencies from requirements.txt to the virtual environment

`$ (yourenvname) pip install -r requirements.txt`

#### Set up Unit Test Environment

Run the following command to install nose unit testing environment:

`$ (yourenvname) pip install nosetests`

This will enable you to run tests to all the files in the Yummy-Recipes directory.

`$ cd --working directory--`

`$ (yourenvname) nosetests`

#### Running the program

Run the program by typing the command in your terminal :

`$  (yourenvname) python app.py` 

You can now use the application.

The Yummy-Recipes is live at heroku. click  [Yummy-Recipes](https://recipes-yummy.herokuapp.com) 
to open.


