# Serenity JUnit Starter project


This is the simplest possible build script setup for Serenity BDD using Java. 

This is a very minimal sample project using JUnit and Serenity BDD in Java. 
You can use this project as a quick starting point for your own projects.

## Get the code

Git:

    git clone https://github.com/serenity-bdd/serenity-junit-starter.git
    cd serenity-junit-starter


Or simply [download a zip](https://github.com/serenity-bdd/serenity-junit-starter/archive/master.zip) file.

## Use Maven

Open a command window and run:

    mvn clean verify

## Use Gradle

Open a command window and run:

    gradlew test 


## Viewing the reports

Both of the commands provided above will produce a Serenity test report in the `target/site/serenity` directory. Go take a look!

## The project structure
Now import the project into your IDE (be sure to import the project as a Maven or Gradle project). The project structure looks something like this (some less interesting files and directories have been left out):

    ├── pom.xml                                 1            
    ├── build.gradle                            2            
    ├── src
       ├── main
       ├── test                                 3           
           ├── java
               ├── starter                      4  
                   ├── ASimpleTest.java         5        
                   ├── steps                    6                   
                       ├── MathWizSteps.java    7   
1. Maven POM file
2. Gradle build script
3. Test code
4. Root package
5. A sample test case
6. Step library package
7. A sample step library
