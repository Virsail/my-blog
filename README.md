# Blog
## Author

[Virsail](https://github.com/virsail)

# Description
This is a flask appication that allows a user to write a blog ,see all other posted blogs .A writer is able to sign in and write a blog ,the writer gets to delete a blog he or she does not like or finds inapropriate ,the writer also gets liberty of saving his or her credentials to the user profile page.

## Live Link
[View Site](https://blosite.herokuapp.com//)

## User Story
As a user i would like to:
* View blog posts on the site 
* Comment on the blog posts
* View the most recent blogs posted
* Get an email when a new blog is posted by joining a suscription
* See random quotes on the site
* Sign in to the blog
* Create a blog from the application
* Delete comments that i find insulting
* Upgrade or delete blogs i posted


## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all blogs, Select between signup and login if you already have an account|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirects to page with blogs  based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |**submit**  | Redirects to all comments tamplate with your comment and other comments|





## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  https://github.com/Virsail/my-blog.git
  ```
2. Move to the folder 
  ```bash
  cd my-blog
  
  ```
3. Running the application
  ```bash
  python3.8 manage.py server
  ```
4.Testing the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.8](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)
* HTML
* Mako
Powershell
* Css
* Bootstrap

## Contact Information 

Reach me on @Ericmbagaya@gmail.com
Also check out (https://github.com/Virsail)

### License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
Copyright (c) 2020 @mbagaya

