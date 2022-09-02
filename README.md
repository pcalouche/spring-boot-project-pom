# Spring Boot Project Common POM

This is a convenience parent POM artifact to help not only manage Spring Boot dependencies and maven plugin versions,
but also commonly used application dependencies like Apache POI, database drivers, etc.

## How to Install

Include this repository in your pom.xml.

```xml

<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

Include as a parent pom in your pom.xml

```xml

<parent>
    <groupId>com.github.pcalouche</groupId>
    <artifactId>spring-boot-project-pom</artifactId>
    <version>3.0.0</version>
</parent>
```