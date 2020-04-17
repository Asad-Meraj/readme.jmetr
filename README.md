# readme.jmetr

#### Q1.1 Describe your automated testing tool based on the rubric and detailed questions developed by the class. This should describe the type of testing tool it is, what is its main characteristics, how it is being developed and maintained, which type of models and information is based on etc. Write down your answers that describe (as well as links) to the tool. 

### Apache JMeter (http://jmeter.apache.org/) 
The Apache JMeter™ application is open source software, a 100% pure Java application designed to load test functional behavior and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.
JMeter is a load testing tool, which works at protocol layer. It mainly supports Web Applications which uses HTTP/HTTPS protocols, irrespective of the technology used to build the applications such as Java, NodeJS, PHP, ASP.NET etc. JMeter also supports various other protocols such as FTP, SMTP, SOAP / REST Webservices, Database via JDBC, LDAP, TCP, Java Objects etc.

### JMeter Features 
--> Ability to load and performance test many different applications/server/protocol types:
--> Web - HTTP, HTTPS (Java, NodeJS, PHP, ASP.NET, …)
--> SOAP / REST Webservices
--> FTP
--> Database via JDBC
--> LDAP
--> Message-oriented middleware (MOM) via JMS
--> Full featured Test IDE that allows fast Test Plan recording (from Browsers or native applications), building and debugging.
--> CLI mode (Command-line mode (previously called Non GUI) / headless mode) to load test from any Java compatible OS (Linux, Windows, Mac OSX, …) https://jmeter.apache.org/usermanual/get-started.html#non_gui
--> Full multi-threading framework allows concurrent sampling by many threads and simultaneous sampling of different functions by separate thread groups.
--> Highly Extensible core:
--> Pluggable Samplers allow unlimited testing capabilities.
--> Scriptable Samplers (JSR223-compatible languages like Groovy and BeanShell)
--> Several load statistics may be chosen with pluggable timers.
--> Data analysis and visualization plugins allow great extensibility as well as personalization.
--> Functions can be used to provide dynamic input to a test or provide data manipulation.
--> Easy Continuous Integration through 3rd party Open Source libraries for Maven, Gradle and Jenkins.


### Jmeter Requirements
Although there are no specific requirements to start working on Jmeter other than the need of having JAVA installed on your device. Once you have the JAVA 8 or latest with 64 bit operating system requirement fullfilled you can easily setup Jmeter in your device for free.

### Pros
·         Very light weight tool and can be installed easily
·         As it is an open source tool you need not to be worried on license
·         There are multiple plugins that are available in the market and can be installed easily according to the requirement
·         Caching and offline analysis/replaying of test results

### Cons
·         It can be used only on web applications
·         Consumption of memory is high in GUI Mode and performance testing like Load, Stress and Endurance with high user load are preferred to run in NON-GUI mode
·         Complex scenario cannot be done using JMeter thread group
·         Recording in this is complex, as we need to setup the proxy manually
·         It supports only Java coding for custom coding

Jmeter uses automated scripting and manual scripting to test applications. Furthermore, you can use external softwares to record actions being performed and later export them into the Jmeter for further testing of the application.

### Updates
There have been numerous updates in the software and with every new version being released, They focus on resolving bugs encountered in the last update. Latest update includes 5.2.1 released on 2019-11-24.

### Tutorials and documentation
For tutorials there are many youtube channels that teaches the use of Jmeter till advance level. One of them is 

(https://www.youtube.com/watch?v=8loLHbhfyh0&list=PLhW3qG5bs-L-zox1h3eIL7CZh5zJmci4c&index=3)

The official Documentation can be found here

https://jmeter.apache.org/usermanual/index.html


#### Usage examples

Step 1) Add Thread Group

Start JMeter

Select Test Plan on the tree

Add Thread Group

Right click on the "Test Plan" and add a new thread group: Add -> Threads (Users) -> Thread Group

In the Thread Group control panel, enter Thread Properties.

Number of Threads: 100 (Number of users connects to the target website: 100)
Loop Count: 10 (Number of time to execute testing)
Ramp-Up Period: 100

Step 2) Adding JMeter elements

Now we determine what JMeter elements in this test. The elements are

HTTP request Default

This element can be added by right-clicking on the Thread Group and selecting: Add -> Config Element -> HTTP Request Defaults.

In the HTTP Request Defaults control panel, enter the Website name under test (www.facebook.com)

Right-click on Thread Group and select: Add -> Sampler -> HTTP Request.

In HTTP Request Control Panel, the Path field indicates which URL request you want to send to facebook server.

Step 3) Adding Graph result

JMeter can show the test result in many formats so lets take example of Graph format.

Right click Test Plan, Add -> Listener -> Graph Results

Press the Run button (Ctrl + R) on the Toolbar to start the software testing process. You will see the test result display on Graph in the real time.

