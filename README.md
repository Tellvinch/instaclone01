
### Instaclone

Instaclone is a platform where users can upload  their photos and add caption to the photos for friends  to view, like and comment on the photos.Users can also follow each other, see their profile with all the photos they've posted and see their friends photos on their timeline too.

### Requirements
##### These are the requirements you need to get the project running locally on your machine:
  - Text Editor
  - Install python
  - Install and activate virtual
  - Setup Database
  - Install Django


### Installation Process

Download any text editor of your choice, either Sublime, Visual-Studio-Code or Atom.

##### Install your preferred version of python

  - ```sudo apt-get install python3.6```.
  - ```python --version``` to confirm that python has been installed.

##### Open the command-line and run the following command to open a directory:

  - ```cd your preferred directory``` => ```cd Desktop```

##### Git clone the project on your current directory by:

  - ```git clone https://github.com/Tellvinch/instaclone.git```.

##### Move to your project directory:

- ```cd instaclone```.

##### Open the project on your terminal:

  - ```atom . or code .``` , according to the type of your text editor.

##### Install virtual environment using python:

  - ```python3.6 -m venv virtual```, check your project to confirm you have a folder called virtual,
  - then activate it by running ```source virtual/bin/activate```
##### To install the packages in the ```requirements.txt file```,

  - ```pip install -r requirements.txt```  That will install all packages including Django.

##### To open python shell:

  - ```python3.6``` ,
  - ```import django```
  - And lastly ```django.get_version()``` to see and confirm the version of django installed.
  - You can then ```ctrl z``` to get out of the shell,

##### After ensuring you have all the above

  - ```python3 manage.py runserver``` to run the project.
  - Then click the local host link given to open the project on a browser ```http://127.0.0.1:8000/```.


#### For more information read the following django and python documentation:

  - [DjangoDocumentation](https://docs.djangoproject.com/en/1.11/intro/install/)
  - [PythonDocumentation](https://www.python.org/doc/)

### Behavior Driven Development

 Given that a user sign-up with the correct details, and use those details to login successfully, then they should be able to access the application and it's features.

 Given that the user has uploaded a photo, then, the application should display the photo uploaded.

 Given that a user has logged in, created a profile and posted a picture, then they  should be able to view their profile and all the photos they've posted.

 Given that a user has an account, then they should be able to follow other users, see the photos of the users they are following on their timeline and also like and comment on those photos.



### Technologies Used
1. Python
2. Django
3. PostgreSQL
4. HTML5
5. CSS3

### Contact

tellvinchimani@gmail.com

### License
<!-- [MIT LICENCE](https://github.com/Tellvinch/Instaclone/blob/master/License.md) -->