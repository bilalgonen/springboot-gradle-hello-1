# springboot-gradle-hello-1

Spring Boot, Gradle Hello World multi-module

./gradlew build

java -jar my-webapp/build/libs/my-webapp-0.0.1-SNAPSHOT.jar

./gradlew clean : Removes build folders.

./gradlew test : Runs tests in the src/test folders and generate reports in my-webapp/build/reports/tests/test/index.html.

./gradlew test -p my-webapp : Runs tests for a specific submodule only.
