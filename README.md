# Session 04

The purpose of this activity is twofold: Practice Flask, and make sure we've all gotten hooked into github classrooms.

This activity asks you to get a simple flask project set up -- As you do this, I recommend taking personal notes on what you had to do (You can do that in this file) -- this is the EXACT same initial steps as you'll need for Homework 1.

1. Set up a pipenv environment. In linux this was done with a command like `pipenv --python 3.10` although you may need to change the python version
2. install flask `pipenv install Flask`
3. Add your Pipfile and Pipfile.lock to git
4. Setup your `static` and `templates` folder, as well as a basic server file such as `server.py` (I recommend starting by copying out of the [quick start guide](https://flask.palletsprojects.com/en/2.2.x/quickstart/#a-minimal-application)
5. Add your "fan site" from Sesion 02 to the static files and get it up and running (you may have done this already...)
6. Add a "quiz" feature. This will ultimately have some question about your fandom and a page to check if the answer is correct -- this should be done with HTML forms and checked server-side, not using javascript. This will have a few core parts:
  * a GET request which returns a simple page with a question and a form for answering the question
  * A POST request (that gets called by the form) which checks the answer
  * A template which shows the person their answer, the correct answer, and has a picture IF the person answered correctly!
7. Don't forget to commit and push your code!
8. Don't forget to share your favorite resources with your peers on slack!
