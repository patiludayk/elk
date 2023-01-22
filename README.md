# README #

___________
## ELK - ElasticSearch, Logstash, Kibana #

Elastic search, Logstash and Kibana for log management.
___________

## What is this repository for? ##

* Quick summary
    * ELK stack implementation for log management with springboot
    * Complete setup of ELK stack with lproduction ready setup with minimal change in configuration.
    * logstash - with spring logging config using logback-spring.xml
* Version
    * elk - 0.0.1-SNAPSHOT
    * Java - 8
    * Springboot - 2.7.8
    * Elastic search - 8.6.0
    * Logstash - 8.6.0
    * Kibana - 8.6.0
    * maven - 3.8.1
* [Learn Elastic search](https://www.elastic.co/webinars/getting-started-elasticsearch?utm_campaign=getting-started-sitelink&utm_content=&utm_source=adwords-s&utm_medium=paid&device=c&utm_term=elasticsearch&gclid=EAIaIQobChMIpa68y4jc_AIVjLHtCh3YDwQHEAAYASABEgKLE_D_BwE)
* [Learn Logstash](https://www.elastic.co/logstash)
* [Learn Kibana](https://www.elastic.co/kibana)

## How do I get set up? ###

* Prerequisite
  * Knowledge of Docker environment, basic commands and eco system.
      * [Java](https://www.oracle.com/uk/java/technologies/javase/javase8-archive-downloads.html)
      * [Maven](https://maven.apache.org/download.cgi)
      * [Springboot](https://spring.io)
          * create basic springboot project from [here](https://start.spring.io)
      * [Docker Desktop](https://www.docker.com/products/docker-desktop/)
      * [Rest API tool](https://www.postman.com/downloads/)
          
* Configuration
    * Download and install docker desktop
    * from terminal go to docker-compose.yaml file and run command docker-compose up
* Dependencies
    * spring-boot-starter-web
    * logstash-logback-encoder
    * lombok
* Database configuration
    * NA
* How to run tests
    * under development
* Once checkout build using below command from project root folder.
    * mvn clean install
* Deployment instructions
    * build deployable artifact using jar/war option and deploy to server.
    * No special requirement except docker configuration.

## How to Run/start
* Run as normal spring boot project from IDE.
* If not using STS or any springboot supported plugin run as below maven goal for class _ElkSetupApplication.java_
    * spring-boot:run
    * from any API tool, hit API - / to generate logs

