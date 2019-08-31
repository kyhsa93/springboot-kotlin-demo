# Spring boot kotlin demo

- default port: 8080

```bash
  ./gradlew build && java -jar build/libs/demo-0.0.1-SNAPSHOT.jar
```

```bash
  docker build -t test .
  docker run -d -p 8080:8080 test
```