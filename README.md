# simple-java-app-gradle
Learning how to build and run a simple application with gradle.

Gradle is a build automation tool based on java. (it's like make from Linux.) It automates required to build an application like: compile source code, manage required dependencies/libraries, run autmoated tests, create documentaion, send notifications, etc.

It creates a build.gradle file build script written in groovy

creating a gradle project, it will create a .gradle file created in user's home dir. it is a local repo for gradle on the system, jar, dependencies of gradle will be stored and managed from here.

it will create that project's dir and inside will be a gradle.build build script (which is like maven's pom.xml) where you can add dependencies, plugins, libraries. It is written in groovy syntax.

`repositories {}` indicates where you are getting dependencies from. (usually mavenCentral())

must add  `mainClassName = 'class_name_goes_here'  <may be 'package_name.class_name'>`

follow this ex. building and running java application with gradle: https://www.youtube.com/watch?v=RrVURuzcFhY&t=361s

Commands to run on terminal to build and run:
`$ gradle build`
`$ gradle run`
`$ gradle tasks`

To use gradle wrapper without having gradle installed:
`$ ./gradew build`
` ./gradlew run`
