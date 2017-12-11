# launchpadCodeTests
This is the repository for three launchpad coding tests that I am designing for applicants to the Launchpad Programme in 2018

## Ground rules for all submissions:
Please choose one of the *Coding Challenges* below for submission (you can feel free to submit more than one if you have the time/inclination)
The following are a list of rules that apply to all submissions: 

### Grading criteria:
We will be looking at a lot of standard expectations for these types of applications, such as:
   _Unit Tests_
   _Commenting_
   _Modularity_
   _Input sanitization_
Please feel free to utilize any library or framework that you would like provided that you can package it for submission.  
Please provide a _README.md_ explaining how to launch your application locally and how to contact you if we have any problems with the application. 

### How to submit:
Please compress and package your submission and place it in a github repo and send us the link OR email us directly at "fernando.pombeiro@falmouth.ac.uk" and "ben.sewell@falmouth.ac.uk". 
And now onto the challenges...

## Coding Challenge One: The best Pasty in Cornwall

### Coding Challenge One Scenario:

As you will be living in Cornwall once you have joined the course it is important to find the best reviewed local cornish pasty! One of the best ways to do this is by examining various review sites like *yelp!* to help you decide. The problem? *yelp!* lacks an api...

### Coding Challenge:
Write a web scraping application in the language of your choice (.NET, Python, Node.js, PHP, C##, etc) that scrapes the yelp site for various cornish pasty shops in *cornwall* and returns the top ten highest reviewed local pasty shops. 
The application should accept two user inputs:
   1. _n_ where _n_ is the number of results to be returned (_n_ can be assumed to be < 10)
   2. _l_ where _l_ is the location to be passed to yelp.co.uk for the pasty shops (for example: "Falmouth" or "Penryn" or "Truro")
The application should take the average of the reviews and rank them in the order of "highest rated" to "lowest rated" based on the mean of the *star rating* according to Yelp!
Additionally the application should provide weighted ratings to the more recent reviews based on an algorithm of the candidate's choice. The essential part here is that the more recent reviews are weighted more heavily than the reviews further in the past.

## Coding Challenge Two: Surf's Up in Cornwall!

### Coding Challenge Two Scenario:

One of the favourite habits of our local residents is hitting the local surf locations (of which there are many available here in the south west!). 
To do this, however, we need to make sure that our local weather readings are amenable to such activity. Fortunately for us there are several apis available that feed us regular weather updates based on our local areas, including: 
   1. [openweather](https://openweathermap.org/api)
   2. [Met Office](https://www.metoffice.gov.uk/datapoint)
   3. [Apixu](https://www.apixu.com/)
   4. ...and any others you would prefer!
What we need is a front end to effectively _present_ this data to ourselves (and anyone else we might want to add). In order to do this let's create a website that hits any weather api and presents the information to your customers in effective, eye catching, well designed ways. Take the JSON returns from these apis and manipulate them into a pleasing website. *This is your chance to show off your design and front-end coding skills in HTML, CSS and Javascript!*

## Coding Challenge Three: Virtual Sailing

### Coding Challenge Three Scenario:

Another favourite habit down here on the coast is sailing. For centuries the cornish have had a special relationship with the sea and as a future resident of the southwest you will too (albeit on the virtual plane).
And speaking of "virtual planes": our third coding challenge is based on game engines: create a boat/wave effect using a games engine (like Unity or Unreal). Using a games engine add in effects like wind, waves, and current. Show us your games engine skills on a games engine effect of a sailboat at sea. Please include instructions on how to launch the application.
