# Griniaris Server

Server application for Griniaris.

## Requirements

- Java 21+
- Maven 3.9+

## Run in Development

```bash
mvn clean javafx:run
```

## Build Executable JAR

```bash
mvn clean package
```

Generated file:

- `target/GrinirisServer.jar`

## Run JAR

```bash
java -jar target/GrinirisServer.jar
```

The server starts and listens on the configured port (default: `7777`).
Make sure firewall rules allow inbound connections on this port if clients connect from other machines.
