# The Vonette Way Blog
## Author

[Vonetta Orinda](https://github.com/VonettaOrinda)

# Description
This  is a flask application that allows writers to post blogs, edit and delite blogs. It also allows users who have signed up to comment on the blog posts that have been posted. It also allows fans to subscribe to the email list in order to get notifications whenever a new blog post is posted.

## Live Link



## User Story

* A user can view the most recent blog posts.
* View and comment on the site.
* A user should get an email alert when a new post is written.
* Registered User is allowed to log in to the application
* A user sees random quotes on the site
* A writer can create a blog from the application and update or delete blogs I have created.

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all blogs, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with blogs that have been posted by writes and be able to subscribe to the blog|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|
|Subscription | **Email Address**| Flash message "Succesfully subsbribed to D-Blog"|





## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  
  ```
2. Move to the folder and install requirements
  ```bash
  cd The Vonetteway_blog
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python manage.py server
  ```
5. Testing the application
  ```bash
  python manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [thevonetteway@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2019 **Vonetta Orinda**