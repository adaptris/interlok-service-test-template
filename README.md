# Overview #

This is the template project for the configuration of an interlok service test project. The configuration is designed to sit alongside an adapter configuration and allow for unit testing of service configuration of an adapter. 

The aim was to remove the need to have working consumers and producers but still be able test the logic, such as branching and mappings. 

It also fits nicely into a continuous integration cycle producing JUnit style xml.

## Setting up your first service test ##

### Pre-requisites ###

* ANT 1.9+
* JAVA 1.8

## Running your first service test ##


```
#!shell

ant clean test
# There will be a ./target/testoutput/html directory that contains the test output.
```