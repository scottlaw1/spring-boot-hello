# spring-boot-hello

This repo contains my implementation of the tutorial found here: https://spring.io/guides/gs/spring-boot/

I built with Maven (instead of Gradle) and used Visual Studio Code as the IDE.  I installed the Spring Boot CLI using Homebrew with the following commands:
```bash
$ brew tap pivotal/tap
$ brew install springboot
```
This only worked after I installed Apple Command Line Tools with this command:
```bash
$ xcode-select --install
```
Verify that Homebrew can "see" the command line tools with this command:
```bash
$ brew config
```
The output should look something like the following if the tools are available:
```bash
...
Java: 1.8.0_131, 1.8.0_45
macOS: 10.14.4-x86_64
CLT: 10.1.0.0.1.1539992718
Xcode: 10.1
...
```
