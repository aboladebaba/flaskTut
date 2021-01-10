# flaskTut

#### 1.0 Initial setup

#### 2.0 Templates

#### 3.0 Web Forms
Web forms are one of the most basic building blocks in any web application. I will be using forms to allow users to submit blog posts, and also for logging in to the application. I'm going to use the [Flask-WTF](http://packages.python.org/Flask-WTF) extension, which is a thin wrapper around the WTForms package that nicely integrates it with Flask.
<b>Configuration</b>: There are several formats for the application to specify configuration options. The most basic solution is to define your variables as keys in app.config, which uses a dictionary style to work with variables. A format that I really like because it is very extensible, is to use a class to store configuration variables. To keep things nicely organized, I'm going to create the configuration class in a separate Python module.

In this section, I will implement LogIn form, form validation, receiving form data and n=many cool stuffs that webforms brings to the mix.
