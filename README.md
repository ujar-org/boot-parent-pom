Generic Maven 3 parent POM with lots of default configuration. It is pre-configured to handle the "org.ujar.*" software
stack in a suitable way.

The latest released version requires JDK 11 at build time.

# Spring-based parent POM.

To use it as your parent POM using the following snippet:

```xml
  <parent>
    <groupId>org.ujar.bom</groupId>
    <artifactId>parent-pom-base</artifactId>
    <version>0.0.7-SNAPSHOT</version>
  </parent>
```

# Parent POM for all RESTful microservices.

```xml
  <parent>
    <groupId>org.ujar.bom</groupId>
    <artifactId>parent-pom-rest</artifactId>
    <version>0.0.7-SNAPSHOT</version>
  </parent>
```

# Asynchronous service parent POM.

```xml
  <parent>
    <groupId>org.ujar.bom</groupId>
    <artifactId>parent-pom-async</artifactId>
    <version>0.0.7-SNAPSHOT</version>
  </parent>
```
