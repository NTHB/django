![django Logo](https://www.djangoproject.com/s/img/logos/django-logo-positive.svg)

The web framework for perfectionists with deadlines

### Resource
- [Lynda](https://www.lynda.com/Django-tutorials/Learning-Django/656811-2.html)
- [Djangoproject](https://www.djangoproject.com/start/)
- [Django Documents](https://docs.djangoproject.com/en/1.10/intro/overview/)

### Progress Report
- [Oct 5,2018](https://nthb.github.io/django/#friday-oct-5th-2018)

# What is Django?

**Django** is a high-level framework for developing website application with **Python** language which can help you creating website faster and easier by reducing the obstrucles in web development. And yes, it's **free** and *open source*.

## Why Django?
 - **FAST**

Django was designed to help developer create application as quick as possible

- **WELL PACKED**

Django is fully loaded with extra tools to make handling common Web development tasks such as content administration, authentication and so on

- **SECURE**

Django helps developers avoid many common security mistake such as SQL injection, clickjacking etc.

- **SCALABLE**

Django can be scaled quickly to meet the busy traffic demands


As mentioned above, Django provides extra tools or features to help building website. Here are the main features from Django:

1. The Model Layer
2. The Views Layer
3. The Template Layer 
4. Forms
5. The Development Process
6. The Admin
7. Security
8. Internationalization and Localization
9. Performance and Optimization
10. Python compatibility
11. Geographic framework
12. Common Web Application Tools
13. Other Core Functionalities

## How does it work?

The simple workflow of how Django works is shown below:

![django workflow](https://qph.fs.quoracdn.net/main-qimg-23768cfe8a5c4be3c6b6d26611b8d651.webp)
*[source:https://www.quora.com/What-exactly-is-the-Django-framework-and-how-does-it-work](https://www.quora.com/What-exactly-is-the-Django-framework-and-how-does-it-work)*

When web server is requested by client, the request is passed to Django. Django tries to figure out what to do with web page address. This process is done by _URL RESOLUTION_ and then start to creating _View_ by passing request and related function.

At this point, the data and information are transferred back and forth from database. After that Django will compose with template to create html page for returnning back to client as it has been requested for. 

### Conclusion
Django is a framework written in Python language and it provides pre-build tool to help developing web application easier and faster.


## PROJECT

# Blog JOURNAL

![project Logo](/images/project_logo.png)

__Write everything…__

It is a web application which able to let user create
journal or blog to display on website.


__Manage with Django…__

With extra tool from Django, managing content in
website can be easier than before

## USER STORY

### As a user,


I would like to write a blog for myself and share with everyone in a website.


I want to add pictures to the article I wrote.


### As a developer, 

I want to create a authentication for my website.


I prefer to maintain content in my site using Django.


I would rather explore more funtionalites about Rest API with Django REST Framework.


## Friday, Oct 5th, 2018


### Retrospectives

I would like to create a small web application which could be used to write Blog or Journal. Users must login first and then start creating his/her own blog. User may attach some pictures to the blog. As a admin, Managing contents(Blog) can be done backend using Django content management with authorization.

This week, I did a working environment setting and an installations to start creating web application. I tested to run server with Django framework which was successful. 

Something that did not work well is that version of Python and Django. In my machine, I used PIP operation install which I got an error at first place, then I figured out that it is because of my PIP version is too old after upgraded to latest version everythings worked as it should be.

The interesting things is the virtual working environment. I have to run Django in virtual environment and has to be activated every times before running server.

### Next Week

I would like to create backend function to be the fundamental of the web application which is Models, and Views.

### Back Log for Oct 5,
![BackLog Oct 5](https://raw.githubusercontent.com/NTHB/django/master/images/Oct5_Backlog.png)
      
