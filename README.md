# Data-Scrapping-of-Google-Images

A Deep Dive Into Web Scraping Using MechanicalSoup 
MechanicalSoup is a python package that automatically stores and sends cookies, follows redirects, and also can follow hyperlinks and forms in a webpage. It was created by M Hickford. He was always amazed by the Mechanize library. Mechanize was a John J. Lee project which enables programmatic web browsing in Python, and it was later taken over by Kovid Goyal in 2017.

Some of the features of Mechanize was:

    mechanize.browser: which uses urllib2.OpenerDirector to open any Url on the internet
    Easily filling HTML form
    Automatically observing robots.text
    Automatically handling HTTP-Equiv 
    Browser .back() and .reload() method.

Unfortunately, Mechanize is not compatible with Python3 programming language, and also its development stalled for many years.

So Hickford came up with a solution: MechanicalSoup, which provides the same API, built on Python Requests(for better HTTP sessions), and BeautifulSoup(for data navigation). Since 2017 this project has been maintained by Hemberger and moy.

MechanicalSoup is designed to mimic the behavior of how humans interact with web browsers. Some of the possible use-cases include:

    Interacting with websites that don’t provide API
    Testing a website, you’re currently developing.
    Browsing interface 

Installation

You can install MechanicalSoup using PyPI (python package manager).

Mechanical soup install command will download BeautifulSoup, requests, six, Urllib, and other libraries. 

# pip install MechanicalSoup

