# Lab :: Hello World :: Java Application

[![License](https://img.shields.io/github/license/odaceo/lab-hello-world-java.svg)](LICENSE)
[![Build Status](https://travis-ci.org/odaceo/lab-hello-world-java.svg)](https://travis-ci.org/odaceo/lab-hello-world-java)

## Description

A simple Java application on Linux.

## Prerequisites

[Vagrant](https://www.vagrantup.com/downloads.html) must be installed on your 
computer to mount the workbench for this project.

Open a Terminal and run the following commands:

```shell
vagrant up
vagrant ssh
cd /vagrant
```

## Compiling the application

The compile command makes a standalone JAR file.

``` shell
mvn clean package
```

## Running the application

To launch the application use the following command:

``` shell
java -jar target/hello-world-0.1.0-jar-with-dependencies.jar Odaceo
```

## Reporting Issues

Issues can be reported at [https://github.com/odaceo/lab-hello-world-java/issues](https://github.com/odaceo/lab-hello-world-java/issues)

## Source code

The source code is available at [https://github.com/odaceo/lab-hello-world-java](https://github.com/odaceo/lab-hello-world-java)

## License

All the source code is distributed under [ASL 2.0](LICENSE).

## Copyright

© 2017 [Odaceo](http://odaceo.ch). All rights reserved.
