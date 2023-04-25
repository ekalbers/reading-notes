# Intro to Django

## Readings
### [Getting Started with Django](https://www.djangoproject.com/start/)
### [How Django Works Behind the Scenes](https://wsvincent.com/how-django-works-behind-the-scenes/)
### [What is Tailwind CSS](https://blog.hubspot.com/website/what-is-tailwind-css)

## Bookmark and Review
### [What is Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
### [First Django App - Part 1](https://docs.djangoproject.com/en/4.1/intro/tutorial01/)
### [First Django App - Part 2](https://docs.djangoproject.com/en/4.1/intro/tutorial02/)
### [Tailwind CSS Django - Flowbite](https://flowbite.com/docs/getting-started/django/)

## Reading Questions
1. What are the key components of the Django framework, and how do they contribute to building a web application?
   - Templates, forms, allow a user to easily create a functional website
2. Explain the role of Django’s MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.
   - The MTV is how Django passes information around the application, the model represents the data and the databas schema, the view is renders the data, and the template defines the structure and layout of the user interface. So iin the context of the WRRC, the user makes a request, the correct view is routed based on the url, the view then gets correct data from the model, and then send it to be rendered as part of the template, then the rendered template is passed back to the user.
3. What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?
   - It is a framework for creating websites much like Bootstrap but it differs in the fact that it does not have built in buttons and drop downs, but instead has utility classes to aid in the creation of your own reusable components. This allows for more flexibility in the creation and styling of a website.