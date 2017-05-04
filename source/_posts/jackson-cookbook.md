---
title: Hello World
---


# Resources for Jackson


## Install Jackson using Maven
Add this to your pom.xml file. We need three artifacts (but maybe we do not use all of them).
Jackson Core
Jackson Annotations
Jackson Databind

```
<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-core</artifactId>
  <version>2.5.3</version>
</dependency>

<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-annotations</artifactId>
  <version>2.5.3</version>
</dependency>

<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-databind</artifactId>
  <version>2.5.3</version>
</dependency>
```

## TODO
- How to prevent null value when writing to string?
- 


## References
[Jenkov - Jackson Tutorial](http://tutorials.jenkov.com/java-json/jackson-installation.html)

