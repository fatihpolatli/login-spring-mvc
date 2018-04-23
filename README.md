# login-spring-mvc

to compile
> mvn clean install

this will build application and run tests.

after that in a command line

> java -jar {application-jar}

this will run application at http://localhost:8080

in order to login

> http://localhost:8080/login


to register

> http://localhost:8080/registration.html


i have used hsqldb, so you dont need to set database configuration

## Tests

- username should be at least 3 characters
- email should be well formatted
- password should be at least 7 characters and include uppercase,lowercase,special and numeric characters


## Requirements
- java 1.8
- maven or junit to run tests
