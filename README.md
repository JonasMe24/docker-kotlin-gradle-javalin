# docker-kotlin-gradle-javalin
This project is for testing development with docker, kotlin, gradle and javalin

## Technologies used
* Kotlin
* Gradle
* Docker
* Javalin

## Getting started
## Running locally

### Building the application
#### Compile and package application
To build locally and run the integration tests you can simply run `./gradlew shadowJar` or on windows 
`gradlew.bat shadowJar`

#### Creating a docker image
Creating a docker image should be as simple as `docker build -t docker-kotlin-gradle-javalin .`

#### Running a docker image
`docker run --rm -it -p 8080:8080 docker-kotlin-gradle-javalin`

## Contact us
### Code/project related questions can be sent to
* Joakim Kartveit, `joakimkartveit@gmail.com`
