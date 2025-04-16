

### Introduction

This document describes how to create, change and cancel job scheduler with UI screens using reactJS and spring boot.

### Technology Stack

The technologies used in this application are given below. 

   **Front End**

    * ReactJS 
    * Typescript
    * Webpack

   **Back End**

    * Maven
    * Spring Boot
    * Spring Data JPA
    * Quartz Scheduler
    * H2 DB (InMemory)
    
### Prerequisite

Make sure to install below tools and set the path in the system before proceeding to quick deployments.

* Java - JDK 1.8
* Maven Build Tool [Download][Maven]
* Node [Download][Node] - Optional

``` maven requires JAVA_HOME variable, kindly follow the path setup given below.```

#### Windows

> set PATH=path/to/JDK/bin;%PATH%

> set JAVA_HOME=path/to/JDK

> set PATH=path/to/Maven/bin;%PATH%

#### Linux

> export PATH=path/to/JDK/bin:$PATH

> export JAVA_HOME=path/to/JDK

> export PATH=path/to/Maven/bin:$PATH

### Limitations 

In order to check the priority job execution, I have considered frequency as corn expression (String) because I have tried considering frequency as seconds (number) but there is a difference in seconds / milliseconds while trying to create same Job frequency twice.  

### Source Code Download

If you have the GIT you can clone the application using below link else use the direct download link. 

> git clone https://github.com/aapkasachin/Job-Scheduler





