gatling-load-tests 
==================

## Introduction

### [Gatling](http://gatling.io/)

Gatling is an open-source load test tool, that makes a break from 
traditional load-tools by using asynchronous concurrency and 
a Scala DSL for its scripting.

### [SBT](http://www.scala-sbt.org/)
SBT is the de-facto build tool for Scala projects.

## Installation 
### SBT
```bash
$ wget https://dl.bintray.com/sbt/rpm/sbt-0.13.7.rpm
$ sudo yum install -y sbt-0.13.7.rpm
```

### Test Resources
```bash 
$ git clone git@github.com:BBC/gatling-load-tests.git; cd gatling-load-tests
```

## Execution
```bash
$ sbt
> testOnly *SampleTest
```
