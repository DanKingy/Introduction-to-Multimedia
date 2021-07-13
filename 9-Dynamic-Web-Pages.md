# Dynamic Web Pages

* Content is changing
* Processing is performed
  * Server-side scripting
  * Client-side scripting



# Server Side Scripting

* Dynamic web server in which page requests are fulfilled by running a script directly on the web server to generate dynamic HTML pages
* These scripts reside either in the HTML document or in another document pointed to from the HTML document
* Generally most functionality is performed by both an executing script and a database

There are many server side scripting technologies:

* PHP
* ASP.net
* Python
* JSP



## PHP

* Script is embedded into the page along with the HTML and is run when the page is requested
* Open source, cross platform and free
* Parses code within its delimiter tags
* Anything outside these tags (HTML) is sent directly to the output and is not parsed by PHP



## Active Server Pages (ASP)

* Microsoft technology that enables dynamic web pages using VB Script or C#
* Pages contain code that the server executes
* Code can do anything such as read databases, run other programs, etc.



## Java Server Pages (JSP)

* Java Server Pages are an extension to the Java servlet technology that was developed by Sun
* Dynamic scripting capability that works in tandem with HTML code



## Python

* Interpreted high level programming language for general purpose programming
* Requires a web framework such as Django, Flask etc



## Server Side Applications

* Common Gateway Interface (CGI) defines a standard interface between a Web Server and an independent application
* CGI is very general because application is completely decoupled from the Web Server
* No convenient place to store state information between web requests

* CGI applications can be written using any language that the application machine can execute:
  * Perl, Java, C++, C etc



# Server Side vs Client Side

* All of the dynamic web page technologies so far have been server based
  * The server runs the script/application
  * Code is not visible to the client
  * The client gets sent formatted HTML



# Client Side

* Scripts are programs that run inside an Internet browser on the client machine
* Small programs in the source form of an interpreted language are embedded directly into the Web Page
* Browser has a built-in interpreter that reads the script code it finds in the page and runs it



## Plug-ins

* Add on software application that permits software developers to add new capabilities to the browser using a defined programming interface
* Provides the ability to display a new type of data using the browser itself rather than starting a separate application



## Java

* Object oriented programming language
* Compiles to Java byte code, able to run on any instantiation of a Java Virtual Machine



### Java Applets

* Browsers include a Java Virtual Machine
* Applets are downloaded from the server and run on the browsers virtual machine - Java Runtime Environment (JVE)
* Even though they are run on the client, Java applets are restricted so that they cannot damage the client machine
* Now deprecated since Java 9