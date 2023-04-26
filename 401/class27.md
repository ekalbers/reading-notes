# Django Models

## Reading
### [Using Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)
### [Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
### [Beginner's Guide to Django - Part 1](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html)

## Bookmark and Review
### [Beginner's Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)

## Questions
1. Explain the purpose and basic structure of Django models. How do they help in creating and managing database schema in a Django application?
   - The purpose is to give an outline for what a database schema should look like. Each model is basically just an object that has certain information.
2. Describe the primary features and functionality of the Django Admin interface. How can it be customized to suit the specific needs of a project?
   - Django Admin interface allows you to create a superuser that has access to everything to add and change things within the database.
3. Briefly outline the key components and workflow of a Django application, as discussed in the Beginner’s Guide to Django. How do these components interact with each other to create a functional web application?
   - admin is a config file for the built in django admin, apps is a config file for the app itself, models is where the entities of the application are stored(they are automaticaly translated into database tables), tests is for testing, views is where the WRRC is handled.