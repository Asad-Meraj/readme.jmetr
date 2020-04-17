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
