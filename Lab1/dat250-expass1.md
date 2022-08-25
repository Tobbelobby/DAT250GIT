# First Lab 

## Intro 

For the first lab in DAT250, we were setting up our developer environment. Software such as Java Development Environment (JKD), Maven, Postgres and the platform Heroku.  

Installing the tools for the most part went fine, the only problems i hade was with some java extension to vscode, and a port problem with Heroku. The problem is describe in the problem and how i solve them is described in the problem section. 

The main part of the lab task was getting familiar with the Heroku platform. We where ask to do a small tutorial, provided by the Heroku web site. We walk through steps as Preparing the app, scaling, Database and more. In the tutorial i used the provided code by Heroku, so no code is provided here.    


## Problems 

I hade some difficulty of installing the vscode java extension. Vscode did not find the installed expansion, and kept asking me to install it. The problem was most likely caused by not have installing the coding pack for java. After installing the coding pack for java and reinstalling the vscode extension, it was working. 

## Validation 

Java 

Running a small hello world program, and also under the heroku tutorial.

Maven

After installing Maven and configure the .bach fil, I validated the installation by using the command mvn -v. We also use Maven in the Heroku tutorial mvn clean install.

Postgres

Adding a local db to the Heroku application, and going to /db. And seeing the Database Output Red from DB:2022......


## Technical problems during the Heroku 

Heroku use port 5000 by default when running a application locally, this port was in use. I tried to kill the port, but for some reason it did not work. I fix the problem by specifying the prot number "heroku local -p 8080". 


## The application 

The url wil take you to the example cloned in the Heroku tutorial pag, if you go to /hello you wil see i added a header "The First Lab".

https://polar-inlet-12528.herokuapp.com/



### Tobias Sagvaag Kristensen 