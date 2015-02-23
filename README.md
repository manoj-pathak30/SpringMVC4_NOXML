# SpringMVC4_NOXML
SpringMVC4 with full annotation
This small application to create user and show existing userlist from DB to demonstrate springMVC4  with fully code based approach. I have used propertySource to support outside *.properties file for configuration out of the box.  

Steps to run this application:
1. Checkout code from github into your local machine. 
2. Create database schema by running given DB script file present on path resource/sql/MySQL_script.sql.
3. Launch command prompt and goto checkout code repo folder
4. Run mvn clean install command to build application. 
5. Deploy created war file into tomcat webapps folder