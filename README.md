# Springboot Thymeleaf Demo
Demo app with 2 endpoints, hosted on Heroku 

## Deploy

- [Heroku App](https://springboot-thymeleaf-demo-dfc4920e7ec1.herokuapp.com/)

## Variant op:

- [Hello You App](https://hello-you-springboot-2908d926200a.herokuapp.com)

## Technologie

- Java
- JDK (Java Development Kit)
- Maven
- Spring-Boot
- Thymeleaf templates
- Heroku Automated deploy van GitHub

## Details

### Endpoints:
- /hello
- /goodbye

### Frontend:
Static html file with hyperlinks to /hello and /goodbye in resources folder

### Heroku config:
system.properties: java.runtime.version
Procfile: jar target folder
pom.xml: java version
