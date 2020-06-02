### Insta clone
This is a clone of the popular app, Instagram.

### By Hudson Kishoyian


### Description

The application allows users to sign up, upload pictures,view other user's pictures,like them, comment on them and also follow the other users. Users can also search for other users using their user names.


### Setup/Installation Requirements
<ul>
<li>Ensure you have Python 3.7</li>
<li>Clone the Instagram repository</li>
<li>Create your own virtual environment and activate it using these respective commands:python3.7 -m venv --without-pip virtual && source virtual/bin/activate</li>
<li>Install all the necessary dependencies necessarry for running the application using this command: pip install-r requirements.txt</li>
<li>Create a database: psql then create the databse using this command: CREATE DATABASE     database-name </li>
<li>Run migrations using these respective commmands: python3.7 manage.py makemigrations images then: python3.7 manage.py migrate</li>
<li>Run the app using this command: python3.7 manage.py runserver on the terminal.You can then open the app on your browser</li>
</ul>  

### Technologies Used
<ul>
<li>Python 3.7</li>
<li>Django</li>
<li>Bootstrap</li>
<li>CSS</li>
<li>HTML</li>
</ul>

### User stories
 As a user of the application I should be able to:

Sign in to the application to start using.
Upload my pictures to the application.
See my profile with all my pictures.
Follow other users and see their pictures on my timeline.
Like a picture and leave a comment on it.


### BDD SPECIFICATIONS