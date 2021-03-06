![django Logo](https://www.djangoproject.com/s/img/logos/django-logo-positive.svg)

The web framework for perfectionists with deadlines

### Resource
- [Lynda](https://www.lynda.com/Django-tutorials/Learning-Django/656811-2.html)
- [Djangoproject](https://www.djangoproject.com/start/)
- [Django Documents](https://docs.djangoproject.com/en/1.10/intro/overview/)

### Progress Report
- [Oct 5,2018](https://nthb.github.io/django/#friday-oct-5th-2018)
- [Oct 12,2018](https://nthb.github.io/django/#friday-oct-12th-2018)
- [Project User Story](https://nthb.github.io/django/#project-user-story)
- [20% Progress Report: Oct 26,2018](https://nthb.github.io/django/#friday-oct-26th-2018)
- [40% Progress Report: Nov 2,2018](https://nthb.github.io/django/#friday-nov-2nd-2018)
- [60% Progress Report: Nov 9,2018](https://nthb.github.io/django/#friday-nov-9th-2018)
- [80% Progress Report: Nov 16,2018](https://nthb.github.io/django/#friday-nov-16th-2018)
- [90% Progress Report: Nov 23,2018](https://nthb.github.io/django/#friday-nov-23rd-2018)
- [95% Progress Report: Nov 30,2018](https://nthb.github.io/django/#friday-nov-30th-2018)
- [Final Check In: Dec 7,2018](https://nthb.github.io/django/#friday-dec-7th-2018)

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

Something that did not work well is that version of Python and Django. In my machine, I used PIP operation to install which I got an error at first place, then I figured out that, because of my PIP version was too old. After upgraded to latest version everythings worked well as it should be.

The interesting things is the virtual working environment. I have to run Django in virtual environment and has to be activated every times before running server.

### Next Week

I would like to create backend function to be the fundamental of the web application which is Models, and Views.

### Back Log for Oct 5,
![BackLog Oct 5](https://raw.githubusercontent.com/NTHB/django/master/images/Oct5_Backlog.png)



## Friday, Oct 12th, 2018
      
### Retrospectives

This week, I created prototype which is Blog web application using Django as a backend. There is built-in database, sqlite3, where content of the website stores inside. I query the content and combine with other components such as views.py and other static resources for example CSS files.I established authentication for user to login into web application and create the content including admin to manage entire content from backend.

#### Screenshot

![homepage](https://raw.githubusercontent.com/NTHB/django/master/images/Blog_list%20_screenshot.png)

Homepage

![post_List](https://raw.githubusercontent.com/NTHB/django/master/images/post_list_admin.png)

List of posts at in backend

[Go to live site](https://tahsuper.pythonanywhere.com/)

#### Things which went well...

- Everything built-in for web application development from Django is fast and almost ready to use instantly.

- I can use pythonanywhere.com to host my web application for free with limited resource.

#### Concerns...

- I tried to connect external database such as mysql and there is some difficulty to achieve

- There are many aspects to learn for mastering in Django

- Our project will use Django REST api framework to provide data to front-end, so there are more documents to study

### Back Log for Oct 12,
![BackLog Oct 12](https://raw.githubusercontent.com/NTHB/django/master/images/Oct12_Backlog.png)

## Friday, Oct 19th, 2018

## Project User Story

### As a Tenant users,


I would like to find a place for living.

I would like to register for creating user account.

I would like to create a resume for applying home renting.

I would like to look through the list of properties.

I would like to contract the landlord of interesting properties.

### As a Landlord users,

I would like to announce my properties.

I would like to see a risk assessment for tenant who interested in my properties.

I would like to see a dashboard of all my related property information.

I would like to invite interesting tenant to be my tenant.

I would like to register for user account.

I would like to register my properties for renting purpose.

I would like to manage my properties in one place.

### As a developer, 

We want to create a authentication for our web application.

We prefer to maintain content in our site using Django.

We provide data using Django Restframework API.

We would like to display our web application using React.

Django will be our core framework for back-end written in Python.

We would like to display information in infographic and data visualization.

We use mysql as our database to contain information.


## Friday, Oct 26th, 2018


### Retrospectives

This week I tried to use Django Restframework API so that I can publish information from back-end to front-end as a JSON format.So I can query from mysql database using this framework and send to client web browser as following figures.

#### Screenshot of Properties List
![properties_list](https://raw.githubusercontent.com/NTHB/django/master/images/properties_list.png)

#### Screenshot of Property Detail
![property_detail](https://raw.githubusercontent.com/NTHB/django/master/images/property_detail.png)

### Next Week

I will try to manage url routing, then I can organize the entire struture of this web application.

### 20% Progress Report  for Oct 26th,
![BackLog Oct 26](https://raw.githubusercontent.com/NTHB/django/master/images/Oct26_Backlog.png)


## Friday, Nov 2nd, 2018


### Retrospectives

This week I finish routing with urls for backend Django response. All information will be pass in Rest API of JSON file format.

### Next Week

Since our project use React framework as a frontend, so to integrate with current backend, we pass the information back and forth using Rest API. For next week, I would like to learn about React so that I can understand and intergrate with other parts from my team with ease.

### 40% Progress Report  for Nov 2nd,
![BackLog_Nov_2](https://raw.githubusercontent.com/NTHB/django/master/images/Nov2_Backlog.png)


## Friday, Nov 9th, 2018


### Retrospectives

This week I finish integrating basic React for creating article components as my front-end. All information from Django is passed in Rest API of JSON file format and then read by Axios library using get method. 

### Screenshots

Rest API
![API_Listview](https://raw.githubusercontent.com/NTHB/django/master/images/API_ListView_Screenshot.png)

Main Page
![Main_Page_Listview](https://raw.githubusercontent.com/NTHB/django/master/images/React_ListView_Screenshot.png)

### Demo

[![django_react_demo](https://raw.githubusercontent.com/NTHB/django/master/images/Visual_Cue.png)](https://youtu.be/Clx_2aQ8UsM)

### Next Week

Using form for creating input channal so that users can create article in the web application.

### 60% Progress Report  for Nov 9th,
![BackLog_Nov_9](https://raw.githubusercontent.com/NTHB/django/master/images/Nov9_Backlog.png)


## Friday, Nov 16th, 2018


### Retrospectives

This week I finished creating input channal for client site and also maintain update, edit or delete features for exist articles. I combined React as a front-end and Django as a back-end using RestAPI Framework.

### Next Week

Providing authentication features to handle user and maintain security for web application.

### 80% Progress Report  for Nov 16th,
![BackLog_Nov_16](https://raw.githubusercontent.com/NTHB/django/master/images/Nov16_Backlog.png)


## Friday, Nov 23rd, 2018


### Retrospectives

This week I finished creating authentication features so that users can login and manage their articles.

#### Things that went well
Currently, web application can handle register and login for any users

#### Things that went wrong
Web application security is under normal standard which may result in not suitable for deployment in live hosting

#### Interesting
The library Django-rest-auth is being used and it provides many essential features about authentication when using Rest framework API

#### Things I can do different
I feel that there must be another way to provide more security and easier way to handle the request from front end.

### Next Week

Deploy web application into Heroku and have minor adjustments about security

### 90% Progress Report  for Nov 23rd,
![BackLog_Nov_23](https://raw.githubusercontent.com/NTHB/django/master/images/Nov23_Backlog.png)

#### Estimation
- Deployment : 1 day
- Research : 2 days
- Testing : 1 day

#### Velocity
4 tasks/week


## Friday, Nov 30th, 2018


### Retrospectives

This week I did give a presentation about the Django technology we use in our project. It is the same technology as this project which I am implementing. The deploying part is not finished, I have encountered with some problem when trying to deploy to Heroku.

#### Things that went well
- I fixed some warning and error.
- The presentation went well.

#### Things that went wrong
Deploying to Heroku is harder than I though and I am trying to fix this before next week

#### Interesting
I found out that deploying on cloud service such as Heroku has a differrent approach comparing to the local environment that I am using for development.

#### Things I can do different
I need to study more about how to properly deploy on cloud service (Heroku)

### Next Week

Keep working on the deployment to heroku to make the project live and ready for demonstation

### 95% Progress Report  for Nov 30th,
![BackLog_Nov_30](https://raw.githubusercontent.com/NTHB/django/master/images/Nov30_Backlog.png)

#### Estimation
- Deployment : 4 days

#### Velocity
fixing warning and error 2 days


## Friday, Dec 7th, 2018


### Retrospectives

This semester, I have studied Django as a backend technology and I have used it to integrate with React technology as a frontend for my web application. I gave a try for deploying to heroku cloud platform. Unforunately, with other constraints and time duration, I cannot successfully deploy to that platform. There is an error that prevent React displaying the web application content and I have to time left to debug that. At least, I know how to use python language and React knowledge that I can use in future. If there is a chance I would like to study more about these technology and I hope I can do it better.

I have pushed all my code into this github.

[Link to Heroku](https://journalapp-django-react.herokuapp.com/) 
//It display only title of the page.

#### Things that went well
- Web application work well in local machine
- I can partially deploy to heroku platform

#### Things that went wrong
- Some error that preventing react properly display web site content

#### Interesting
It is so hard and consume so much time in deploying process. So next time, I need to carefully plan ahead about deploying process ao that I can recover for unexpected situation the as this current.

#### Things I can do different
- Carefully plan and better in time estimation in deploying process.
- Organizing file structure and environment for both local and live site.
- Have time for unexpected situation.

### Final Check in
![BackLog_Dec_7](https://raw.githubusercontent.com/NTHB/django/master/images/Dec7_Backlog.png)

#### Velocity
4 days with half of the goal
