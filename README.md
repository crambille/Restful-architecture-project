# Restful-architecture-project---C-Sharp---Asp.Net---Windows-Service---WebSite
A restful exchange server information from the database to an application and a website using web service. Moreover the server is running a windows service which complete and updates the information in the database


**Private project no code will be shared!**

**Brief Description of my project**
![](https://github.com/crambille/Restful-architecture-project/blob/master/REST.png)

## A single data base
* Purpose: This database makes it possible to gather data. 
* Tools used : Sql server

## A Windows service
* Purpose: This background can calculate and update regularly the additional information from the database. Also this emits spot and stores messages following the event. The logging is a useful and necessary technical activity in this application to debug (handy when the implementation of a debugger is not easy), get execution traces (start / stop, information, warnings, errors execution, ...) facilitate the search for a source of anomaly (stacktrace ...) and understand or check the flow of executed treatments (traces / O in methods, display the call stack, ...).
* Tools used : Nlog

##  Web services 
* Purpose: To retrieve or modify the database via the application or website, a set of features (http protocol) is exposed on real-time intranet.
* Language : c#

## An application
* Purpose: Displays information remote database on a screen
* Development: To be dynamic and modular I chose to develop programming application object. Because you can easily add elements without changing its code all thanks to the legacy.
* Tools used : ASP.NET
* Language : C#

##  A website
* Purpose: View and edit the remote database
* Development : AngularJs - Bootstrap - Html5 - CSS3

##  A Restful Server
* Purpose: To implement this project, a server must be accessible and configurable. The server to host the database, website and web services. Furthermore it should run the Windows service that calculates and updates the data.
* Tools used : IIS 
