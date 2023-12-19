
# YogaClassroom

A Django React Application 

# This application is made in such a way that you dont need to compile react files in `frontend`, because django directly looking for the main `templates/frontend/index.html` HTML file, and all the neccesary compiled javascript is pointing to this file.
So just directly run `python manage.py runserver` after installing neccesary modules.

## All the neccesary validations is happening in the backend of the application i.e `./YogaForm`.

## Entity-Relationship Diagram For YogaClasses
![image](https://github.com/divyapakanati3535/yoga_form_admission/assets/124708902/00cf0f05-f97c-49a5-81c7-20cf2ac48d10)
## DATABASE
![DB-1](https://github.com/divyapakanati3535/yoga_form_admission/assets/124708902/47a135e3-a9c6-467e-8791-3696d981fd27)
![DB-2](https://github.com/divyapakanati3535/yoga_form_admission/assets/124708902/8a044c01-a3cf-414c-9ded-f2093215b7af)
![DB-3](https://github.com/divyapakanati3535/yoga_form_admission/assets/124708902/df3eebba-9e13-4631-9048-88a04e71bb9a)

# Try It

https://flexmoney-yoga-form.herokuapp.com/

## Setup Instructions

### Clone this repo

`https://github.com/divyapakanati3535/flexMoney_Yogaform.git`

### Create Virtual Environment and Install Required Python Modules                                                           
`cd YogaClassroom`

Install venv
`pip install virtualenv`

For Creating a venv run this 
`virtualenv -p python3 venv`

Activate virtualenv 
`venv\Scripts\activate`

Install requirements
```bash
pip install -r requirements.txt
```
### Start Web Server

To start the web server you need to run the following sequence of commands.

Run the django web server.
```bash
python manage.py runserver
```

## [Install Node.js](https://nodejs.org/en/)

## Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```
#



