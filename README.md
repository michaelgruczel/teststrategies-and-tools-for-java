# teststrategies-and-tools-for-java

> :warning: TODO this tutorial is under development, don't use it at the moment

This repo is just a collection of best practices and tools with simple example snippets for the development of Java Applications.
It starts with the Teststrategy since often discussion are fought about tools without understanding the 
context and because more testing does not mean better testing.

Before selecting the "right" tools, I recomment to setup a strategy.
A strategy starts with the risks and requirements.
The second step is to select the most effective approaches to cover these.

## Functional testing


![](https://github.com/michaelgruczel/teststrategies-and-tools-for-java/raw/master/testpyramid.png "")

In a perfect world you add them into one pipeline.

![](https://github.com/michaelgruczel/teststrategies-and-tools-for-java/raw/master/perfect-pipeline.png "")

The lack of testsystems and long running test times often forces you to a pragmatic tradeoff.

![](https://github.com/michaelgruczel/teststrategies-and-tools-for-java/raw/master/real-pipeline.png "")

Some of the well known tools (in the java world) are:

* Mockito
* Spock
* Restassured
* Hamcrest
* Junit
* TestNG

There are of course more tools.

## Non-functional tests

Apart from the functional aspects also non-functional requirements have to be taken into consideration:

* Performance tests
* Security tests
* Failover tests
* Code quality checks

### Performance tests

I will showcase two tools to executre perfomance tests

* Gatling
* Jmeter

Also in this field there are of course more tools.

### Security tests

I will showcase

* OWASP’s Zed Attack Proxy

And there are of course more tools.

### Code quality checks

I will showcase one tool:

* findbugs
* sonar

Again there are of course more tools.

### Failover tests

For Failover tests, let us concentrate on some tools from the Simian Army (https://github.com/Netflix/SimianArmy)

There are of course more tools.
