# compile and build war
mvn compile war:war

# run with jetty with classes
jetty:run

# run with jetty with war
jetty:run-war

#if deploy on jetty 
http://localhost:8080/company

#if deploy on tomcat
http://localhost:8080/webapp-company-simple-jsp-view-1.0-SNAPSHOT/

