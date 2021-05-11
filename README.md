# Wow-Labz-Internship-DataScience-Flask
My second goal was too study about Flask.

Flask is a web application framework written in python. Flask is based on the Werkzeug WSGI toolkit and jinja2 template engine. Importing flask module in the project is mandatory.
The flask application is started by calling the run() method. However, while the application is under developemnt, it should be restarted manually for each change in the code. 
To avoid this inconvinience, enable debug support. The Debug method is enabled by setting the debug property of the application object to True before running or passing the debug 
parameter to the run() method.
The route() in flask is used to bind the URL to a function.

What is the purpose of flask?
Flask is light weight web application framework. It is designed to make getting started quick and easy, with the ability to scale up the complex applications.

For e.g "Hello, world!" web application with flask.
from flask import flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
    
if __name__=='__main__':
    app.run()
    
Above code will give the output-------> "Hello, World!"<----------- on localhost port 5000 in a web browser when you run with the python app.py command and the Flask library 
installed.
