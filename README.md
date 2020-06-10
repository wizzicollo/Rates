# PROJECT NAME
Rate-It-Out-Of-Ten

# AUTHOR
Collins Kiprutoh

# DESCRIPTION
This project allows users to post their projects for other users to rate according to design, usability and content.

# Behaviour Driven Development
Users need to Sign in to the application to post projects and review projects

Users can post a project to be rated or reviewed.

# User Story
Users need to Sign in to the application to post projects and review projects.

Users can view different projects and their details.

Users can post a project to be rated or reviewed.

Users can search for different projects.

Users can view projects overall score.

Users can view their profile page with all their published projects.

Users can rate and review other users' projects.

# SETUP/INSTALLATION.
*** To view the app.Visit -> Rate-It-Out-Of-Ten

Clone this repo: git clone https://github.com/wizzicollo/Rate-It-Out-Of-Ten.

The repo comes in a zipped or compressed format. Extract to your prefered location and open it.

Open your terminal and navigate to gallery then create a virtual environment.For detailed guide refer here

To run the app, you'll have to run the following commands in your terminal

pip install -r requirements.txt

On your terminal,Create database db_name using the command below.

CREATE DATABASE db_name; 
**if you opt to use your own database name, replace db_name your preferred name, then also update settings.py variable DATABASES > NAME
Migrate the database using the command below

python3.6 manage.py migrate
Then serve the app, so that the app will be available on localhost:8000, to do this run the command below

python manage.py runserver
Use the navigation bar/navbar/navigation pane/menu to navigate and explore the app.

# Technologies Used
Python 3.6
Django
Postgresql
Bootstrap4

# APIs
This application comes with two API Endpoints for Profiles and Projects.

Profiles API Endpoint - https://rateitoutoften.herokuapp.com/api/profiles/

Projects API Endpoint - https://rateitoutoften.herokuapp.com/api/projects/


# Known Bugs
There are no known bugs

# Contact Information
Email:[kiprutohcollo@gmail.com]
Phone No. : 0741280908

# live link

https://rateitoutoften.herokuapp.com/

# License
This project is licensed under the MIT License - see the LICENSE file for details.