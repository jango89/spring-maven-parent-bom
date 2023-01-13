# README #

### What is this repository for? ###

This repository will act as a parent POM for maven projects. 
Helps to manage the spring dependencies for child services using this parent POM. 

### How to publish the Parent POM? ###

Individual versions can be commited and the command `./mvnw clean compile install deploy` will publish a new POM version to the nexus.

### Things to Remember ###

```     
    <version>2.0.0.RELEASE</version>
```
Version names can be same as the spring version used. 
This will help us to identify the spring version used by looking into the name/version of parent POM itself.

### Spring Release Notes ###
https://github.com/spring-projects/spring-cloud/wiki/Spring-Cloud-Finchley-Release-Notes

### Local Services Development ###

Add the `settings.xml` to `~/.m2` folder. Later update the credentials to fetch parent pom and start downloading dependencies.
