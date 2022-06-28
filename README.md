# Performance-Testing-JMeter-5.4.3

<h1><b>Introduction:</b></h1>

JMeter is an open source Java based software application
which is used to test performance, functionality and load
test of any web application. Apache JMeter can be
used for both static and dynamic websites.

Download: https://jmeter.apache.org/download_jmeter.cgi

<h1><b>Why Performance Analysis?</b></h1>

To help deliver a fast and reliable software system we need to analyze performance of the system. Performance analysis methodology consumes multiple aspects like load testing, stress testing, volume testing etc..It is used to improve user eperience to any web, mobile or desktop applications. Metrics of performance analysis of a software system are described and represented in terms of numeric values.

<h1><b>About Repository:</b></h1>

This repository will consist of following items.
1. JMeter Basics
2. Performance Analysis Samples
3. Performance test for SaaS applications.
4. Building a SaaS model to analyze a performance test.

<h1><b>How to use this repository?</b></h1>

1. Each and every branch will consist of Readme.md file to describe the intention of branch.
2. Master Branch will consist of JMeter Basics README.md file.

<h1><b>Elements of JMeter</b></h1>

1. Test Plan: The element which is the container of running tests. This will consist the execution order of the performance testing.
2. Thread Group: The thread group elements control the number of threads JMeter will use during the test.
3. Controllers: JMeter has two types of controllers. Samplers and Logic Controller.
4. Samplers: Samplers allow JMeter to send specific types of requests to a server.
5. Logic Controllers: Logic Controllers control the order of processing of Samplers in a Thread.
6. Test Fragments: A Test Fragment is a special type of element placed at the same level as the Thread Group element.
7. Listeners: Listeners let you view the results of Samplers in the form of tables, graphs, trees, or simple text in some log files.
8. Timers: Timer element allows to define a period to wait between each request.
9. Assertions: Using assertions it can be proved that the application is returning the correct data.
10. Configuration Elements: They are used to add or modify requests made by Samplers.
11. Pre-Processors: A pre-processor element is something that runs just before a sampler executes. Ideally, to extract value to be used in subsequent requests.
12. Post-Proceesors: A post-processor executes after a sampler finishes its execution.

<h1><b>Execution Order of Test Elements</b></h1>

1. Configuration elements
2. Pre-Processors
3. Timers
4. Sampler
5. Post-Processors (unless SampleResult is null)
6. Assertions (unless SampleResult is null)
7. Listeners (unless SampleResult is null)



