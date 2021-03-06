# Gauge example in Javascript

This is an example project for doing web automation testing with [Gauge](http://getgauge.io). This project tests some of the functionalities of the [active admin demo](https://github.com/getgauge/activeadmin-demo) app. This app is hosted as a Java WAR (with embedded Jetty).

## Running this example
The tests are run on Chrome by default.

### Prerequisites

This example requires the following softwares to run.
  * [NodeJS](https://nodejs.org/en/)
  * [Gauge](https://docs.gauge.org/getting_started/installing-gauge.html)
  * [NPM](https://www.npmjs.com/)
  * [Docker](https://www.docker.com/)

### Setting up the System Under Test (SUT)

* docker run -p 8000:8000 sasilverain/activeadmin-demo
* The SUT should now be available at [http://localhost:8000/](http://localhost:8000)

## Run specs

This runs Gauge specs with [NPM](https://www.npmjs.com/)
* `npm install`
* `npm test`

## Topics covered in the example

* [Concepts](https://docs.gauge.org/latest/writing-specifications.html#concept)
* [Specification](https://docs.gauge.org/latest/writing-specifications.html#specifications-spec), [Scenario](https://docs.gauge.org/latest/writing-specifications.html#longstart-scenarios) & [Step](https://docs.gauge.org/latest/writing-specifications.html#longstart-steps) usage
* [Table driven execution](https://docs.gauge.org/latest/execution.html#data-driven-execution)
* [External datasource (special param)](https://docs.gauge.org/latest/execution.html#external-csv-for-data-table)
* Running Gauge specs with [NPM](https://www.npmjs.com/)

# Copyright
Copyright 2016, ThoughtWorks Inc.
