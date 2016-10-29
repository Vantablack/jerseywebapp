# Java Webapp with RESTful Web Service

Project created using [Jersey Quickstart Webapp Archetype](https://mvnrepository.com/artifact/org.glassfish.jersey.archetypes/jersey-quickstart-webapp).
List of [Jersey Archetypes](https://mvnrepository.com/artifact/org.glassfish.jersey.archetypes).

- Jersey Version: `2.23.2`
- Servlet Version: `2.5` (defined in `web.xml`)

## Maven Dependency Tree

![Dependency Graph](/images/graph.png?raw=true "Click to View")
```
jerseywebapp>mvn dependency:tree

[INFO] --- maven-dependency-plugin:2.8:tree (default-cli) @ jerseywebapp ---
[INFO] jerseywebapp:jerseywebapp:war:1.0-SNAPSHOT
[INFO] \- org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.23.2:compile
[INFO]    +- org.glassfish.hk2.external:javax.inject:jar:2.5.0-b05:compile
[INFO]    +- org.glassfish.jersey.core:jersey-common:jar:2.23.2:compile
[INFO]    |  +- javax.annotation:javax.annotation-api:jar:1.2:compile
[INFO]    |  +- org.glassfish.jersey.bundles.repackaged:jersey-guava:jar:2.23.2:compile
[INFO]    |  +- org.glassfish.hk2:hk2-api:jar:2.5.0-b05:compile
[INFO]    |  |  +- org.glassfish.hk2:hk2-utils:jar:2.5.0-b05:compile
[INFO]    |  |  \- org.glassfish.hk2.external:aopalliance-repackaged:jar:2.5.0-b05:compile
[INFO]    |  +- org.glassfish.hk2:hk2-locator:jar:2.5.0-b05:compile
[INFO]    |  |  \- org.javassist:javassist:jar:3.20.0-GA:compile
[INFO]    |  \- org.glassfish.hk2:osgi-resource-locator:jar:1.0.1:compile
[INFO]    +- org.glassfish.jersey.core:jersey-server:jar:2.23.2:compile
[INFO]    |  +- org.glassfish.jersey.core:jersey-client:jar:2.23.2:compile
[INFO]    |  +- org.glassfish.jersey.media:jersey-media-jaxb:jar:2.23.2:compile
[INFO]    |  \- javax.validation:validation-api:jar:1.1.0.Final:compile
[INFO]    \- javax.ws.rs:javax.ws.rs-api:jar:2.0.1:compile
```
