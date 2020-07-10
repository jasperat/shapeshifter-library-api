# uftpapi

To run the api you need to build the uftplib library using the instructions in the uftplib readme. This will produce the library on the relative location:

../uftplib/build/libs/eu.uftplib-0.0.1-SNAPSHOT.jar

In the build.gradle file this library is referenced.

Set the configuration in the application.properties.

The postgres database scheme will be created in the configured postgres database.

Use the following command to start the api:

on linux:
./gradlew bootRun

on windows:
gradlew.bat bootRun
