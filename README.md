# MY-NEIGHBOURHOOD

## Author
[Jacquline Wangu](https://github.com/JacqulineWangu)

## Description
This a django web application that allows registered users to know about everything happening in your current neighborhood and allows you to be in the loop about everything happening in your neighbourhood . 

## BDD

| Behaviour                                                | Input                                   | Output                                                                                       |
|----------------------------------------------------------|-----------------------------------------|----------------------------------------------------------------------------------------------|
| The program navigates to the authentication page         | On application load                     | Navigate to the login/register page                                                            |
| Navigate to the Registration Page                        | Click on Register link                  | A registration form is displayed                                                 |
| If registration is successful navigate to login page     | Click on Login Link                     | Application navigates to the homepage where posts are displayed                                          |
| A post creation form is displayed with the empty fields. After saving the user is redirected to homepage to view the posts.          | Click on create post button and submit button             |A form with post picture,name,description is displayed.     |
| Application navigates to the business creation form . After saving user is redirected to all businesses page. | Click on create business button       | A form with business name,email and hood name is displayed.A submit button is also displayed. |
| All user details including the name, posts and businesses created by the user are displayed | User clicks on the Profile link | A User profile with all info pertaining the user is displayed. |
| An Edit Form is displayed to update user info. | Use clicks the edit profile button, makes changes and submits the form | A user edit form with update fields is shown to the user to enable them update necessary info. |
| A list of all businesses in that neighbourhood is displayed with all the information | User clicks on View businesses link on the navbar | All businesses are displayed in that particular neighbourhood|
| User is logged out of the application | User clicks on the Logout dropdown | User logged out and redirected to the register/login page. |

### Setup instructions

- git clone `https://github.com/JacqulineWangu/My-Neighbourhood.git`
- install `python 3.6`
- Install [Postgresql](https://www.postgresql.org/download/)
- cd MY-NEIGHBOuRHOOD/
- Navigate to the virtual environment using `source virtual/bin/activate`
- `atom .`  //For those using atom text editor.
- `code .`  //For those using Visual Studio editor.

### Install dependancies
Install dependancies that will create an environment for the app to run `pip install -r requirements.txt`

### Create the Database
```
psql
CREATE DATABASE <name that you want your database to be named>;
```
- Run `python3.6 manage.py runserver`
- Access the application on this localhost address `http://127.0.0.1:8000`

## Technologies used

1. Python 3.6 
2. Bootstrap
3. HTML
4. CSS
5. Postgresql
6. MDBootstrap
7. Django Framework

## Contact
mobile : 0707518860
email : jacqulinewangu@gmail.com
slack : JacqulineWangu

### License  & Copyright information
Copyright (c) 2019 Jacquline Wangu

[MIT License](./LICENSE)