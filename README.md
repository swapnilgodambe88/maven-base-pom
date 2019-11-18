# maven-base-pom
This is the grandfather Maven parent POM for projects which instill best
practices for Maven plugins. This project has the following goals:

* Centralize and share Maven build knowledge
* Define a set of best practices for Maven builds
* Minimize (or completely avoid) replicated Maven skeleton code on projects
* Facor failing builds violations vs build reports that require human inspection
* Provide build consistency

## Prerequisites

The build environment must have the following prerequisite software installations:
* [Maven 3.6.2+](https://maven.apache.org/docs/history.html)
* Java 8 or Java 11+

## How to use it

First, you need your project to reference this as a parent pom

```xml
<parent>
    <groupId>com.maven.base</groupId>
    <artifactId>maven-base-pom</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</parent>
```

Note: _(Since this maven-base-pom is not available on any maven repository, you will need to locally install it on the local machine using - 'mvn clean install' command)_ 
