[![CI/CD Pipeline](https://github.com/diegobotia/virtualfake/actions/workflows/build.yml/badge.svg)](https://github.com/diegobotia/virtualfake/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=bugs)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=coverage)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_virtualfake&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=diegobotia_virtualfake)


# virtualfake

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
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

