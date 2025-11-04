# Hello Java Maven - Jenkins Build

## Overview
Simple Java application demonstrating CI/CD with Jenkins and Maven.

## Project Structure
```
hello-java-maven/
├── src/main/java/HelloWorld.java
├── pom.xml
└── README.md
```

## Prerequisites
- Java JDK 8 or 11
- Maven 3.6+
- Jenkins (Docker or native)

## Local Build
```bash
mvn clean package
java -cp target/hello-java-maven-1.0.0.jar HelloWorld
```

## Jenkins Setup
1. Install Jenkins
2. Configure Maven in Global Tool Configuration
3. Create Freestyle job
4. Set Maven goals: `clean package`
5. Build Now

## Build Results
- ✅ Compilation successful
- ✅ JAR created: hello-java-maven-1.0.0.jar
- ✅ Build time: ~3 seconds

## Author
Gaurav Balpande
DevOps Internship - Task 8
```
---
