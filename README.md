# GraalVM-POC

Proof of concept repository for building and testing a Java application with GraalVM and Maven.

## Build

Use the Maven wrapper to compile and package:

```bash
./mvnw clean package
```

## Run

Run the generated JAR:

```bash
java -jar target/graalvm-0.0.1-SNAPSHOT.jar.original
```

## Tests

Run unit tests with:

```bash
./mvnw test
```

## Notes

- Project includes GraalVM native-image metadata in `target/graalvm-reachability-metadata`.
- The repository uses Maven Wrapper scripts for consistent builds.
