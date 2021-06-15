# Spring Boot Application Google App Engine Standard with Java 11

This sample shows how to deploy a [Spring Boot](https://spring.io/projects/spring-boot)
application to Google App Engine stadndard.

## Local Setup
$ mvn clean package
$ mvn spring-boot:run

Open localhost:8080/

See [Prerequisites](../README.md#Prerequisites).

## Deploying to Google Cloud

```bash
gcloud app deploy
```

To view your app, use command:
```
gcloud app browse
```
Or navigate to `https://<your-project-id>.appspot.com`.
