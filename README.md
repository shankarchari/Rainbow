# Rainbow

## Scope

**Environment**
 - Java - Spring Boot Client Server Application (Embedded Web Server) - **Done v0.0.1**
 - Python - Django Application
 - Ruby on Rails - RoR Client Server App
 - Scala (tentative)

**Data Stores**
 - H2 - **Done v0.0.1**
 - H2 - MongoDB Integration
 - H2 - HSQL Integration
 - H2 - PSQL Integration

**Messaging**
 - AMQP, RabbitMQ
 - MQTT, RabbitMQ
 - REST 
 - Web Sockets
 - Android - GCM
 - iOS

**Search**
 - Apache Solr
 - Apache Lucene

**Complex Event Processor**
 - Event Handlers for Pre & Post Processing - **Done v0.0.1**
 - Asynchronous, Non thread blocking events using Java Reactors - **Done v0.0.1**
 - Event Processor

**Security**
 - OAuth 2.*
 - LDAP Integration
 - Active Directory Integration

**Load Balancing & High Availability**
 - NGINX Integration for Soft Load Balancing

**Rule Engine**
 - Integration with MVEL Expression Parser
 - Groovy Integration
 - DSL: Drools Knowledge Base Support 

**Data Science, Machine Learning etc**
 - Integration with Apache Spark
 - Neo4j Graph Database
 - Integration with Apache Storm

**Loggers**
 - Cloudwatch kind of features for plumbing and managing
 - Management console
 - Network Logging

**MISC**
 - Payment Gateways
 - Bitcoin Integration

## Release: Capabilities and Features

### Version 0.0.2 - October 23, 2015

 - Asynchronous, Non thread blocking events using Reactors
 - Event Processor Placeholder added.


### Version 0.0.1 - October 20, 2015 

 - Spring Boot Application Enablement
 - Integration with H2 in-memory Data Store, DB configured @ "/console"
 - Data Store table creation through Schema and JPA(ORM)
 - HATEOAS Support for simple Pagination, Search and Sort.
 - Event Handlers for Pre & Post Processing Enabled


## Bugs

### v0.0.1
 - Error handling when wrong parameters are sent as query params or path params or post params. 
 - Systems attempts to close DB second time while shutting the embedded webserver component.
 
### v0.0.2
 - Publisher is breaking with "This Dispatcher has been shut down" message while calling from Post and Pre Processing Event Handlers.