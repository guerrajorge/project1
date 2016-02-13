# Overview of Project 1

In Project 1, you will build a substantial real-world database application of your choice. 
This project is split into three parts:

* [Part 1](./part1.md): come up with a web application and design the database on paper using ER-modeling.
* [Part 2](./part2.md): implement your database by translating your model into a database schema and example data.
* Part 3: implement an application that accesses and modifies your database.

Pick an application that you will enjoy working with, because you will be working on it for a substantial part of the semester! 
A suggestion is that you build a database about something that you are interested in
-- a hobby, a favorite web site, material from another course, a research project, etc. 

It's nice if you pick an application where you can populate your database using real data, although it is not necessary.
As the project progresses, you'll end up creating a database of at least dozens of entities/relationships. 
If you can get real data to populate your database, it does help a bit, but again it is not needed. 


# Summary of Deadlines

* **1/21**: Find team-mate in class or on Piazza to find one.
* **1/25-29**: Meet with course staff to discuss your application and design.  This is a required meeting.
* **2/4**: Submit Part 1
* **2/25**: Submit Part 2
* **3/29**: Submit Part 3

Note: you can only use late days for the project description submisson, not for finding a teammate nor for meeting with the staff. Please read the Project Lateness Policy carefully. 


# Getting Help

We _strongly suggest_ you use the following approach when you encounter bugs.  This is basically what
professional software engineers and data scientists do:

1. Use Google or StackOverflow by searching for the error message (the Internet is your friend!)
1. Look for previous answers on Piazza
1. Ask on Piazza including:
  * what you're trying to do
  * describe the approach you took
  * the error message
  * what solutions you've tried
1. Ask the staff


# Teams

You will carry out this project in teams of two. If you can't find a team-mate, please follow these steps:

* Post a message on Piazza asking for a team mate - the best way.
* Send email to Jincheng right away (and definitely before Wed Jan 27th at 5 PM) asking him to pair you up with another student without a team-mate.
* You do not need to notify us of your team composition. 
  Instead, when you submit the first part of your project, please write the name and UNI of both members.
* See Part 1 for a contingency plan to protect yourself in case your teammate drops the class.


### Important notes:

* If you decide to drop the class, or are even remotely considering doing so, please be considerate and notify your team-mate immediately.
* Do not wait until the day before the deadline to start working on the project, only to realize that your team-mate has dropped the class or moved to another planet. It is your responsibility to start working on the project and spot any problems early.
* Please check the Collaboration Policy web page for important information of what kinds of collaboration are allowed for projects.


# Programming Environment: Python on Microsoft Azure

We ask you to use cloud-based technologies for the projects, and the instructions are written
assuming their use. You can work on the project using your own machine, or some other environment.
However, the course staff can only support the enviroment we are providing.

The staff has worked to setup Microsoft Azure credits for you, so you get experience working
with the same cloud infrastructure that real companies (e.g. [Apple iCloud](http://www.theregister.co.uk/2011/09/02/icloud_runs_on_microsoft_azure_and_amazon/)). [HW0](https://github.com/w4111/hw0) describes how to set this up. We will provide the credits after the proposals are submitted.


### GitHub

One drawback of using a cloud computing platform is that it is difficult to open GUI text editors
such as Sublime Text to write your code.  We recommend setting up a version control system, 
such as git on [GitHub](http://www.github.com), so your team can share code.  
This way, you can code on your desktop, commit your changes, and pull the updated changes on your 
cloud virtual machine.

### Flask Python Webserver (For part 3)

We will use the [Flask Python webserver](http://flask.pocoo.org/) in this course.
It is a lightweight webserver that requires a minimal amount of understanding of how the webserver framework is implemented.
In the class github website, we have included a dummy webserver with an example of how to connect to the database.


To use it, go to your Azure machine and first install the webserver package (ideally in a "virtualenv"):

        pip install Flask

Then type the following and follow the instructions:

        git clone https://github.com/w4111/proj1part3.git
        cd proj1part3/webserver
        python server.py

We strongly recommend reading the following documentations:

* [General Flask Documentation](http://flask.pocoo.org/)
* [Jinja Templates](http://jinja.pocoo.org/docs/dev/templates/): this makes it easy to send data (e.g., arrays, dictionaries) 
  to your HTML code and dynamically render them.


### Computer Accounts

If you would like to use Columbia's unix machines for this course, you will
need a CS account.  You can open one from on the [CRF webpage](https://www.cs.columbia.edu/~crf/accounts/cs.html):
and choose the appropriate "student" category as the _account type_

There is a $50 charge to open a CS account. 
Please refer to CRF's homepage for details on infrastructure and policies of the CS department.
