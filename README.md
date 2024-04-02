[![CI/CD Pipeline](https://github.com/danielcanoh22/laboratorio22024/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/danielcanoh22/laboratorio22024/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=danielcanoh22_laboratorio22024&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=danielcanoh22_laboratorio22024)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=danielcanoh22_laboratorio22024&metric=bugs)](https://sonarcloud.io/summary/new_code?id=danielcanoh22_laboratorio22024)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=danielcanoh22_laboratorio22024&metric=coverage)](https://sonarcloud.io/summary/new_code?id=danielcanoh22_laboratorio22024)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=danielcanoh22_laboratorio22024&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=danielcanoh22_laboratorio22024)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=danielcanoh22_laboratorio22024&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=danielcanoh22_laboratorio22024)

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random aviation
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```