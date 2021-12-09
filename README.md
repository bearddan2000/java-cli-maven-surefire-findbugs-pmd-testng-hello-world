# java-cli-maven-surefire-findbugs-pmd-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using TestNG.
Writes test results to console and html.

## Tech stack
- java
- maven
	- findbugs
  - TestNG
  - PMD

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Build code concept](https://github.com/maven/maven-testng)
- [PMD example](https://github.com/eugenp/tutorials/blob/master/static-analysis/src/main/resources/logback.xml)
