# quarkus-microservice-template-messaging

a template base extension for your microservice


## Local build

Add `-DskipTests` if you dont want the devservices test to run:

```bash
mvn clean install
```

## Usage

Create a dependant microservice:

```bash
quarkus create app \
  --maven --java --no-wrapper \
  org.acme:movies:1.0.0-SNAPSHOT
```

add:

```xml
    <dependency>
      <groupId>org.acme.microservice</groupId>
      <artifactId>quarkus-microservice-messaging-deployment</artifactId>
      <version>1.0.0-SNAPSHOT</version>
    </dependency>
```

Code !!
