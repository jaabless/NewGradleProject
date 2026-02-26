# NewGradleProject

A simple Gradle project with Kotlin support.

## About

This is a modern Kotlin/Gradle project configured with:
- **Kotlin JVM Plugin** v1.9.22
- **Java 21** target runtime
- **JUnit 4** for testing
- **GitHub Actions CI/CD** for automated builds and tests

## Building

```bash
./gradlew build
```

## Running

```bash
./gradlew run
```

## Testing

```bash
./gradlew test
```

## CI/CD Pipeline

This project uses GitHub Actions for continuous integration. The CI pipeline automatically:
- Builds the project on every push to `main` and `develop` branches
- Runs unit tests
- Uploads build reports as artifacts
- Publishes test results

The workflow file is located at `.github/workflows/ci.yml`

