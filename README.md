# spring-academy-cash-card

My work through the Spring Academy course
[Building a REST API with Spring Boot](https://spring.academy/courses/building-a-rest-api-with-spring-boot).
The course builds a "Cash Card" REST API test-first. I follow the labs locally in
this repo instead of the course's virtual environment.

This is learning work based on the course's exercises, not an original product.

## Stack

- Java 17+
- Spring Boot 3.x (Spring Web)
- Gradle (wrapper included)
- JUnit 5 / Spring Boot Test

## Run

```bash
./gradlew test       # run the tests
./gradlew bootRun    # start the app on http://localhost:8080
```

## Approach

- Test-first: write a failing test, make it pass, then refactor.
- One commit per lab step, so the history shows the progression.
