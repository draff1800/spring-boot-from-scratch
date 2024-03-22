# Spring Boot From Scratch
A simple Spring Boot web application with some useful services - Built from scratch.

## Guide

* To start the app, run: `./gradlew bootRun`. This also prints a sorted list of all Beans.

* A GET endpoint is defined. Run: `curl http://localhost:8080` in a separate terminal to receive a greeting.

* Tests were added. Run: `./gradlew test` to activate them and see the results.

* Actuator services were added. Run:
  * `curl 'http://localhost:8080/actuator/health' -i -X GET -H 'Accept: application/json'` to see the health of the app.
  * `curl 'http://localhost:8080/actuator/info' -i -X GET` to see info about the app.
  * `curl 'http://localhost:8080/actuator/shutdown' -i -X POST` to shutdown the app.


