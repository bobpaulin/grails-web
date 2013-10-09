#Grails Web Template for Continuous Delivery

run the following to get started:

    gradle init
This will create the grails project

Change the grails-app/conf/BuildConfig.groovy by:
Uncommenting
grails.project.war.file = "target/${appName}.war"

Building:
gradle :clean :grails-war

