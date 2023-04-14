
# MiniBlog

MiniBlog is a web application built using Django, a Python-based web framework, and Bootstrap, a popular frontend framework. The application is a simple blogging platform that allows users to sign up, log in, create posts, and view posts from other users.
The frontend of the application is designed using HTML, CSS, JavaScript, and Bootstrap. It includes templates for rendering the blog pages and forms for user registration, login, and post creation. jQuery is used to handle form validation and submission.
On the backend, Django is used to manage the application logic, including handling user authentication, post creation and modification, and rendering the appropriate templates. The application uses a SQLite database to store user and post data.
Overall, MiniBlog is a simple and lightweight blogging platform that provides users with basic functionality for creating and sharing posts.


# Screenshots

## Home Page

![Home](https://user-images.githubusercontent.com/114723254/232064726-1d87a25c-2ae8-4c60-9112-ac9579129755.png)


## Dashboard Page

![dashboard](https://user-images.githubusercontent.com/114723254/232065138-c2164bd4-04a0-4802-9d3b-37b19de028cb.png)


## Contact Page

![contact](https://user-images.githubusercontent.com/114723254/232065252-d97157bc-1b13-4bfa-aa8f-70bf2ea7abb4.png)


## Add Blog Page

![Add Blog](https://user-images.githubusercontent.com/114723254/232065463-fe51416f-4c2d-4e0f-b564-29abdaa93463.png)


## Edit Blog Page

![Edit Blog](https://user-images.githubusercontent.com/114723254/232065677-73ae3b14-1f23-4c5e-9010-3cdc6136dc94.png)

## Installation

1. Clone the repository: git clone https://github.com/MayankKushwah96/Django-MiniBlog.git
2. Run the migrations: python manage.py migrate
3. Create a superuser: python manage.py createsuperuser
4. Run the development server: python manage.py runserver

## Usage
1. Open your web browser and go to http://localhost:8000/
2. Sign up for an account or log in if you already have one.
3. Create a blog post by clicking on the "Add Post" button on the dashboard page.
4. View your blog post by clicking on the "View Post" button on the dashboard page or by going to http://localhost:8000/post/{post_id}/ where {post_id} is the ID of your blog post.
5. Update your blog post by clicking on the "Edit Post" button on the dashboard page or by going to http://localhost:8000/updatepost/{post_id}/ where {post_id} is the ID of your blog post.
6. Delete your blog post by clicking on the "Delete Post" button on the dashboard page or by going to http://localhost:8000/delete/{post_id}/ where {post_id} is the ID of your blog post

## Frontend:

* HTML
* CSS
* JavaScript
* Bootstrap

## Backend:

* Python
* Django framework
