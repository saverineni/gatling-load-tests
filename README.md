gatling-load-tests 
==================

## Introduction

### [Gatling](http://gatling.io/)

Gatling is a Scala based open-source load test tool which makes a break from 
traditional load tools by utilising asynchronous concurrency and 
a DSL for scripting.

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

## Real-time metrics
David Blooman has created [InfluxDB and Grafana Docker containers](https://github.com/DaveBlooman/gatling-docker) to view and persist realtime data. 

