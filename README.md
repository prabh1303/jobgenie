<div align="center"><h1>
 <mark style="background-color: white; color: black;" align="center"><b>Job Genie</b></mark></h1>
</div>

>Don't judge the name, it's given by me and that's how I am !!

## <mark style="background-color: white; color: black;"><b>Demo:</b></mark>  </>
## <mark style="background-color: white; color: black;"><b>Video Discription:</b></mark>  <https://youtu.be/ZM-q2rMCrl8>

## <mark style="background-color: white; color: black;"><b>Text Description (About):</b></mark>

The project I chose for the capstone project is a Employment Website that allows users to log in and find jobs or create companies that will provide jobs to other peoples. Users can create new companies or join existing once. All companies are visible to everyone so they can join, leave, check status or view past history of the company. All the user and companies data is saved into Django's SQLite3 database and can be quickly accessed.

## Project distinctiveness, complexities and future scope:

In this project I have tried to develop a web application, in which you can join a company and become employ of that specific company, this web application has its own database where all the data related to it is stored. In this there are 2 dashboards, Employ dashboard and Company Dashboard. Company dashboard is visible to all users, the companies history of employment and also the presently employed workers. At company dashboard you get an option to join that company, and also to leave the company he/she has joined in the past. A user can also create their own company by just giving a specific name to their company. It properly tracks the employment history of a person. The employ dashboard is private, a user can only see their own dashboard and also the history of their own employment. 
<br>
<br>
In this I have done a huge work on frontend, I have developed every single thing by myself instead of using bootstraps library beacuse I don't like the colour setup of the buttons of css. I have created similar button like bootstraps primary button but in red colour. Background, logo and other curvy details give it a huge visual attention. Also used JavaScript to make it more user intractive. For me it was a huge challenge to develop frontend as I am not good at it.
<br>
<br>
Future scope: This website is useful for low level jobs like construction works and for the jobs that have daily paying system or no application or interviewing is involved, in that type of jobs. So that a worker can join a work which is going on and leave at anytime, without taking the hassle of salary and all that stuff. This is for providing jobs without experience and study, for those who can't afford to do all that stuff can join these low level jobs and make money that will help them to get along with there daily expenses.
<br>
<br>
I think this idea will be very useful in coming time, as it will help many homeless to get jobs at minimum wages!!
<br>

## Why:

CS50's projects were challenging to say the least. My prior experiences with other web development courses were elementery compare to the challenges set forth by the instructors of this course. I truly appreciate the spirit of pushing students to problem solve, instead of hand holding. This course has done more to help me as a developer because I was thrown into the deep end forced me to understand programming at a fundamental level. It was important for the capstone project to embody that same spirit, so I decided to work with technologies that removes me from my comfort zone. I had no exposure to Python when I began the course, let alone the Django framework. I needed to learn a new language, a new framework, how databases worked, websockets, authentication.. etc. In essense, the reason for this project selection was to remain in a state of growth and discomfort.

## Files:

The following is the file structure of the project where I added or modified. Default project files are ommitted.

```
/ (folder)
-- (files)

/final_project - main project folder
 --README.md - this file
 --requirements.txt - list of libraries needed to run
 --manage.py - start the server and check proper functioning
 --db.sqlite3 - sql database to store data
  /final_project - Django main project folder
   --asgi.py - asynconous web servers and wrapped in middleware
   --settings.py - slightly modified settings
   --urls.py - path configuration
   --utils.py - used for jwt response handler
  /employment - Django Chat app
   --templates\employment - templates used to initial build HTML
   --static\employment - contains JS, CSS and other static files
   --admin.py - admin settings for model view
   --app.py - employment config
   --models.py - database models
   --tests.py - to run some predefined tests
   --urls.py - all standard HTTP request routing handled here
   --views.py - most of the Chat API handled here
  
```

---

<br>

## How to run application:

The project has frontend and backend on the same framework, so to launch... <br><br>
**Django server setup**

1. Navigate to the project folder and create a virtual enviornment and activate it.

```
virtualenv venv
source venv/Scripts/activate
```

2. Install all required packages.

```
pip install -r requirements.txt
```

3. Initialize the database with makemigrations, migrate, then create superuser.

```
py manage.py makemigrations
py manage.py migrate
py manage.py createsuperuser
```

4. Launch the Django server. If set up correctly, server will launch on http://127.0.0.1:8000/.

```
py manange.py runserver
```

<br>


