# Chapter 1: Setting Things Up

First, we'll add everything you need for creating a local web server where our bot will live and an https ngrok tunnel so that our bot can connect to Slack.
After we've set up our development environment, we'll set up a new Slack App and bot user and then we'll connect Slack to our local environment.
Once our environment is set up, we'll get our Flask application server running.



</br>

### List of what we'll need for our Dev Environment

- **[Python](https://www.python.org/downloads/)**,  version 2.7 is being used as the programming language for this example.

- **[Pip](https://pip.pypa.io/en/stable/installing/)**, the Python package manager we'll use for installing packages we need.

- **[Virtualenv](https://virtualenv.pypa.io/en/latest/installation/)** or another tool to manage a virtual environment

- **[Ngrok](https://ngrok.com/)**, an easy to use tunneling tool that supports HTTPS, which we'll use to connect our app to Slack over _teh interwebz._


After you’ve installed Python, pip, ngrok and virtualenv you’ll need to generate and activate a new virtualenv.
Once your virtualenv is turned on you can install all the additional dependent libraries using pip and the `requirements.txt` file in this project,
including [Flask](http://flask.pocoo.org/), a web development microframework for Python, [python-slackclient](http://python-slackclient.readthedocs.io/en/latest/), a Slack client for Python and the [Slack Events Adapter for Python](https://github.com/slackapi/python-slack-events-api). :snake:


