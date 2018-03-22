# SBHS


# Flask: 
To run Flask apps locally: Make a local copy of the repository.  Then run "pip install -r requirements.txt".  Then run "python -m webapp".
Focus on rendering templates, accessing request data, and storing user data in sessions: http://flask.pocoo.org/docs/0.12/ 
Example app that renders templates (fork this repository and be able to run the code locally as well as on Heroku): https://github.com/sky-adams/DSW-templates-example
Example of sending data to the server using a GET request and processing the data on the server: https://github.com/sky-adams/DSW-forms-example

# Jinja (templating language):
See Flask example for basic rendering of templates
Focus on variables, if-else, and extending templates: http://jinja.pocoo.org/docs/2.10/
Context Processors: http://flask.pocoo.org/docs/0.12/templating/#context-processors
Heroku:
This is the service that hosts our websites.  Make an account, make an app, and connect it to the Github repository for your app.  Heroku only allows 5 free apps.

Example assignment using Flask, JSON, and Jinja:
Part 1:
Look through the CORGIS JSON data sets and find a data set that you find interesting and would like to use for your next project.

Do some research about the  source of the data, the significance of the data, and how it is calculated and regulated. As you do your research, keep track of your sources.
For example, for the "Food Access" data set, the source of the data is the US Department of Agriculture, and the USDA's website has lots of relevant information about the data.  However, the USDA's website does not have enough information about the data to really interpret what the numbers in that data mean, or how they relate to issue of 
access to nutritious food in society.  If you choose this data set, you might read some articles about the issue of "food deserts."
For the Cars dataset, some of the data includes gas mileage numbers for various vehicles.  You might research how those numbers are calculated, how they are regulated by the government, and what some of the policy issues related to gas mileage are (for example, the Volkswagen scandal, the "CAFE standards")
For each dataset, you should be able to come up with your own questions, and then practice your scholastic research and writing skills to summarize your findings.
When you are finished, present your findings on a nicely formatted HTML page with links to appropriate online references, and CSS that makes the page readable.   If you link to any images, be sure that you respect any applicable copyrights, and provide suitable image credits as needed.
Paste the link to your Github repository and website for this project below.
Note: After you research your data set and present your findings on a web page, you will expand your page into a website which provides ways to analyze the data in interesting and meaningful ways.

Part 2:
Create a user-friendly website that presents various analyses of the data set you used for your CORGIS data research.  Your research should be included in the website.  For an example site, see https://rocky-retreat-39127.herokuapp.com/. 

Your grade will be based on having a complete and functioning web site and your effort.  You should spend at least an hour a week working on this project outside of class time.

To turn in your website, paste the link to it and the link to your github repository below.


# OAuth:
OAuth is used for securely logging in to web apps without having to write your own log in code or store passwords.  While there are many OAuth providers (Google, Facebook, Twitter, Github, etc.) we use Github in class because everyone has a GitHub account to log in with.
Example web app that uses OAuth: https://github.com/sky-adams/spis16-webapps-oauth-example

# MongoDB and mLab:
See attached document: Getting Started with MongoDB
Example intro assignment:
In this assignment you will learn how to access data stored in a MongoDB database using Python code.

Directions:

If you have not already done so, install the Flask-PyMongo module using "pip install Flask-PyMongo".
Download this Python file: (See attached)
Use this tutorial on MongoDB and PyMongo to complete the code you downloaded.  Be sure to run your env.bat file to set your environment variables before you run your Python code.
