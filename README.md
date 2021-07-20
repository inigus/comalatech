How to compile and run the project.

This is a java project which requires the next software:
	- git as source code repository
	- jdk version 1.8.
	- eclipse as develope enviroment
	- maven for library dependencies
	- Tomcat 8 or similar to deploy the application
	
The steps to follow are:

1. Download code from Github => git clone --progress -v "https://github.com/inigus/comalatech.git" "C:\DOCS\comalatech"

2. Open Eclipse and select the path to your_worspace.
	- Configure a Tomcat Server which was previous installed on your local.
	- Import the downloaded project.
	- Over the project, right button -> Maven -> update project to buuild the project. 
	- Deploy the application "Comalatech-bank" in Tomcat and star it.
	
3. Open an Internet navigator and type: http://localhost:8080/comalatech-bank/ to access the application.

About the code:

The relevant technology used is Java Server Faces. I've decided it because I feel more comfortable and I dispose some projects. 
In fact, the project is developed over a framework "Primafaces-California" which brings a friendly interface web to use in different devices, with multiples visual components.

The java code is composed by the packages:
_comalatech which contains
	_ model
	_jsf
	_data
	
_org.primafaces.california  is specific of the framework

The webcontent is composed by:
comalatechsample.xhtml which contains the exercise you asked me

You can watch a video presentation of the project in this link (12 minutes):
https://share.vidyard.com/watch/rk7c4G2bMCXe1ja6kb8xMk?