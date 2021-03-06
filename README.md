# What are these files?
These are the files of a Python program (a.k.a. App 1) built in the Udemy course  "The Complete Python Course in the Professional OOP Approach."
The course covers how to make this program step by step, plus nine other Python programs. 
If you want to learn Python, you can take the course for a high discount in the link below: 
https://www.udemy.com/course/the-python-pro-course/?referralCode=D1224FDF916B73D7E740
# What does the program do?
The program is written in Python. When the program is executed, an HTML file is generated. The file contains a Leaflet web map with multiple clickable point markers. 
When the user clicks on a marker, a popup window shows up displaying 
the weather forecast for the marker location for the next 12 hours.
# How to run the program
1. Either clone this repo or download all these files by going to _Code -> Download ZIP_.
2. Create a PyCharm (or other IDE) project and configure a Python interpreter for the project.
3. Open the terminal and install the required packages by running:
   `pip install -r requirements.txt`
4. Go to https://openweathermap.org/api, and create an account to get an API key.
5. Go to _geo.py_, and change the "INSERT YOUR API KEY HERE" string to your own Openweathermap API key.
6. Run _main.py_ with Python.
7. The expected output is an HTML file created in the project directory. Double-click the file to see the web map.
