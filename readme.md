## Java Demo Project ##
The project's pom.xml contains all the dependencies required for the project. Feel free to add any additional dependencies as needed.

Within the src directory, you'll find two main folders: test and main. The test folder houses all the unit tests, while the main folder contains the Model-View-Controller (MVC) components of the application.

## Connecting to MySQL ##
Before proceeding, ensure that you have MySQL installed on your localhost. The connection to the MySQL database is defined in src/main/resources/application.properties. You can make necessary changes to the MySQL connection details, such as username and password, as required.

## Entry Point ##
The main entry point for the application is located at src/main/java/RocketFoodApplication.java. After setting up the dependencies and opening the main entry point, you can run the application by clicking the play button in the top right corner of your development environment.

Please note that this application uses Maven for dependency management.

## Models ##
The models folder contains sample model definitions that correspond to the tables in the database. You can use these sample models as a reference and create additional Entity classes as needed.

## Repository and Service ##
Sample Repository and Service classes have been provided in the project for your reference. Populate the code within these classes according to your requirements.

## Controller ##
An empty sample controller has been created for your reference. The view controller should be annotated with @RequestMapping("/backoffice") to ensure that Spring Security allows access. We will be incorporating Spring Security in the upcoming week.

## View ##
A sample view has not been included in the project. Feel free to conduct research on implementing views in Spring MVC.

## Required Dependencies ##
To run this application properly on your local machine, you'll need Java 17 and MySQL installed. All other dependencies are already defined in the pom.xml.

