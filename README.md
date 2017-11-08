# camel-twit-assign2

### Introduction
This Assignment utilizes APIs to access twitter information using Apache camel infra. The application is deployed on Apache karaf container. The purpose is to demo the powerful features of both camel and karaf.

### Build
Update the karaf deploy directory(eg: /home/makalapp/Downloads/apache-karaf-4.1.2/deploy)

Build and install the jar file into karaf using the cmd:
  mvn install
 

### Run with Karaf
Start karaf(if not running already)

	${karaf_home}/bin/karaf

The jar files in deploy directory will get installed automatically.
Run the below cmd to make sure the application camel-twit-assign2 is installed and started successfully.

	list
	
Use the below cmd to view the logs if need be.

	log:tail
	
Then open a browser to see live twitter updates in the web page

	http://localhost:9090/index.html
	