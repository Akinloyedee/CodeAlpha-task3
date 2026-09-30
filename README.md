# Java Gradle Calculator

A simple calculator application built with Java and Gradle, demonstrating core DevOps build automation principles.

## Features
- Basic arithmetic operations (add, subtract, multiply, divide)
- Dependency management using Gradle (Guava)
- Unit tests with JUnit 5
- Automated CI/CD pipeline via GitHub Actions

## Build & Run

Build the project:
```bash
./gradlew build
```

Run tests:
```bash
./gradlew test
```

Run the app:
```bash
./gradlew run
```

## CI/CD
Every push to `main` triggers a GitHub Actions workflow that builds the project and runs tests automatically. See `.github/workflows/gradle.yml`.
