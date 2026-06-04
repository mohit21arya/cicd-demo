# CI/CD Demo Java Application

This is a simple Java application built with Maven. It prints a demo message to the console and can be used as a small sample project for CI/CD workflows.

## Project Structure

```text
demo-app/
├─ pom.xml
└─ src/
   └─ main/
      └─ java/
         └─ App.java
```

## Files

### `pom.xml`

Defines the Maven project configuration.

It includes:

- `groupId`: The project group name, set to `demo`.
- `artifactId`: The application name, set to `cicd-demo`.
- `version`: The project version, set to `1.0.0`.
- `maven.compiler.source`: The Java source version, set to `17`.
- `maven.compiler.target`: The Java bytecode target version, set to `17`.

Maven uses this file to understand how to build the Java application.

### `src/main/java/App.java`

Contains the Java application code.

The `App` class has a `main` method, which is the entry point of the program. When the application runs, it prints:

```text
Hello CI/CD Demo
```

to the console.

## How to Run

From the `demo-app` directory, compile the app:

```bash
javac -d target/classes src/main/java/App.java
```

Then run it:

```bash
java -cp target/classes App
```
