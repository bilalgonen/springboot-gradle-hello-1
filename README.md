# springboot-gradle-hello-1

Spring Boot, Gradle Hello World multi-module

## Application tasks

- bootRun - Runs this project as a Spring Boot application.

## Build tasks

- ./gradlew assemble - Assembles the outputs of this project.
- bootBuildImage - Builds an OCI image of the application using the output of the bootJar task
- bootJar - Assembles an executable jar archive containing the main classes and their dependencies.
- bootJarMainClassName - Resolves the name of the application's main class for the bootJar task.
- bootRunMainClassName - Resolves the name of the application's main class for the bootRun task.
- build - Assembles and tests this project.
- buildDependents - Assembles and tests this project and all projects that depend on it.
- buildNeeded - Assembles and tests this project and all projects it depends on.
- classes - Assembles main classes.
- clean - Deletes the build directory.
- jar - Assembles a jar archive containing the main classes.
- testClasses - Assembles test classes.

## Verification tasks

- check - Runs all checks.
- ./gradlew test : Runs tests in the src/test folders and generate reports in my-webapp/build/reports/tests/test/index.html.
- ./gradlew test -p my-webapp : Runs tests for a specific submodule only.

## Help tasks

- buildEnvironment - Displays all buildscript dependencies declared in root project.
- dependencies - Displays all dependencies declared in root project.
- dependencyInsight - Displays the insight into a specific dependency in root project.
- dependencyManagement - Displays the dependency management declared in project ':my-backend'.
- javaToolchains - Displays the detected java toolchains.
- outgoingVariants - Displays the outgoing variants of root project.
- projects - Displays the sub-projects of root project.
- properties - Displays the properties of root project.
- tasks --all : Displays the tasks runnable from root project (some of the displayed tasks may belong to subprojects).

## Other Commands

- java -jar my-webapp/build/libs/my-webapp-0.0.1-SNAPSHOT.jar

## Videos

- [Gradle Tutorial - Crash Course, Marco Codes](https://www.youtube.com/watch?v=gKPMKRnnbXU)
- [Full Stack Development with Java Spring Boot, React, and MongoDB – Full Course](https://www.youtube.com/watch?v=5PdEmeopJVQ)
