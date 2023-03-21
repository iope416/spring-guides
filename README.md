# spring-guides

## How to run the application from the command line

### Gradle
```bash
./gradlew bootRun
```

### Maven
```bash
./mvnw spring-boot:run
```


## How to build and run the JAR file

### Gradle
build the JAR file
```bash
./gradlew build
```
run the JAR file
```bash
java -jar build/libs/demo-0.0.1.jar
```

### Maven
build the JAR file
```bash
./mvnw clean package
```
run the JAR file
```bash
java -jar target/demo-0.0.1.jar
```
