# locallibrary
using ts venv unless otherwise stated

WLTHB34998(Tech Hub)
==========

/Users/stephanmunn/consolidation/WLTHB34998/djangoflaskprojects

Python-Flask-Datepicker
	FLASK_APP=app.py
	flask run
		ModuleNotFoundError: No module named 'flask_wtf'
django-locallibrary-tutorial 
	fails looking for dj_database_url see the README, may be missing environment.
djangogirls
	server starts, browser defaulting to /catalog (wtf), seem to have got round this by setting 'blog' in urls.py, must be a browser thing. Sure it ought to do more. Works ok on safari
flask-tutorial
	export FLASK_APP=flaskr
	flask run
		Success!
forms
	server start says
	ImportError: cannot import name 'CreateNewList' from 'forms.forms' (/Users/stephanmunn/consolidation/WLTHB34998/djangoflaskprojects/forms/forms/forms.py)
myFirstProject
	is 36K, there might be nothing in it at all
mysite/polls - works, less developed but no other junk
omnistat
	server runs
		booking/destinations resolves but cannot find template
twtsite
	another variation of techwithtim, index page renders a list of very little interest
		also fails to insert a row into the database that clearly does exist!



consolidation/djangoflaskdev-WLWFD37709-20230515 (Tooting)
	scrubbed, 22-05-2023

Stephans-MacBook-Air.local
OR
Stephans-Air.cust.communityfibre.co.uk
======================================
/Users/stephanmunn/git

/Users/stephanmunn/git/.idea
	seems to be part of gitignore.
/Users/stephanmunn/git/Python-Flask-DatePicker
	works using local venv
/Users/stephanmunn/git/bike
	New! trips not defined in bike.admin (env: ts)
/Users/stephanmunn/git/bk
	environment
/Users/stephanmunn/git/blog16
	CRUD - works!!! (env: ts)
/Users/stephanmunn/git/django_tutorial_progress
	restarted django tutorial again...
	reasonably complete django tutorial using bk venv.
/Users/stephanmunn/git/djangogirls
	renders, links do not work (env: tutorial-env)
	onr url, one view
	no idea what admin user and password are
/Users/stephanmunn/git/flask
	(tutorial-env) stephanmunn@Stephans-Air flask % cd examples/tutorial 
	(tutorial-env) stephanmunn@Stephans-Air tutorial % export FLASK_APP=flaskr
	(tutorial-env) stephanmunn@Stephans-Air tutorial % flask run

	server starts but 127.0.0.1:5000 fails with

	[2023-05-22 10:47:50,795] ERROR in app: Exception on / [GET]
Traceback (most recent call last):
  File "/opt/homebrew/lib/python3.9/site-packages/flask/app.py", line 2528, in wsgi_app
    response = self.full_dispatch_request()
  File "/opt/homebrew/lib/python3.9/site-packages/flask/app.py", line 1825, in full_dispatch_request
    rv = self.handle_user_exception(e)
  File "/opt/homebrew/lib/python3.9/site-packages/flask/app.py", line 1823, in full_dispatch_request
    rv = self.dispatch_request()
  File "/opt/homebrew/lib/python3.9/site-packages/flask/app.py", line 1799, in dispatch_request
    return self.ensure_sync(self.view_functions[rule.endpoint])(**view_args)
  File "/Users/stephanmunn/git/flask/examples/tutorial/flaskr/blog.py", line 20, in index
    posts = db.execute(
sqlite3.OperationalError: no such table: post
127.0.0.1 - - [22/May/2023 10:47:50] "GET / HTTP/1.1" 500 -
127.0.0.1 - - [22/May/2023 10:47:50] "GET /favicon.ico HTTP/1.1" 404 -

/Users/stephanmunn/git/flask-tutorial
	success! (env: ts)

/Users/stephanmunn/git/forms
	stephanmunn@Stephans-Air forms % . venv/bin/activate
	(venv) stephanmunn@Stephans-Air forms % flask run          
	Usage: flask run [OPTIONS]
	Try 'flask run --help' for help.

	Error: While importing 'app', an ImportError was raised:

	Traceback (most recent call last):
	  File "/Users/stephanmunn/git/forms/venv/lib/python3.11/site-packages/flask/cli.py", line 218, in locate_app
	    __import__(module_name)
	  File "/Users/stephanmunn/git/forms/app.py", line 2, in <module>
	    from wtforms.fields.html5 import DateField,DateTimeField
	ModuleNotFoundError: No module named 'wtforms.fields.html5'

/Users/stephanmunn/git/gitignore
	a whole repo for a single file, wildly over the top, see github.
/Users/stephanmunn/git/locallibrary
	(env: ts)
	fails with 
		NoReverseMatch at /catalog/books/
/Users/stephanmunn/git/myFirstProject
	no urls in the app
/Users/stephanmunn/git/mydb
	LAMP
/Users/stephanmunn/git/mysite
	Django tutorial again, works but not very far down the line (env: ts)
/Users/stephanmunn/git/mysql-app
	flask app, renders a form, does not appear to submit anything.
/Users/stephanmunn/git/namesviewsforms
	django app, server runs but cannot locate template ffs/index.html at /
/Users/stephanmunn/git/omnistat
	this url http://127.0.0.1:8000/booking/destination/
	renders a page but the links fail with "no destination available", probably not true...
/Users/stephanmunn/git/picker
	fails using local venv, cannot import a form, seems very small, may nver have worked.	
/Users/stephanmunn/git/scl
	environment
/Users/stephanmunn/git/social
	using ~/git/ts env, this is failing to start as it cannot import url from django.conf.urls (seen this elsewhere), suspect it worked before BUT does start using ~/git/scl. If you connect as a user on 127.0.0.1/admin it mostly works. Odd tutorial, very obsessed with css.
/Users/stephanmunn/git/ts
	environment
/Users/stephanmunn/git/tsite
	another attempt at techwithtim's slightly flakey tutorial, once again, renders but does not save rows to database.
/Users/stephanmunn/git/tt
	environment
/Users/stephanmunn/git/wired
	python scripts
