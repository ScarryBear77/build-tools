# Builders task
Before trying to build the projects make sure that you have __maven__ and/or __gradle__ installed.
## Maven
To be able to build the project with __maven__ first you have to move to the *builders-maven* directory:
***
cd builders-maven
***
Then you can build the project with the following command:
***
mvn clean package
***
After the build has finished you can find the admin jar file in the *admin/target* folder, and the web war file in the *web/target* folder.

If you want to run the tests only you need to run the following command:
***
mvn test
***
## Gradle
To be able to build the project with __gradle__ first you have to move to the *builders-gradle* directory:
***
cd builders-gradle
***
Then you can build the project with the following command:
***
gradle clean build
***
After the build has finished you can find the admin jar file in the *admin/build/libs* folder, and the web war file in the *web/build/libs* folder.

If you want to run the tests only you need to run the following command:
***
gradle test
***
