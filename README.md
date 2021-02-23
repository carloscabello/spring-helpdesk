# Spring Helpdesk
Spring Helpdesk is a web application built with spring boot and It implements a simple ticket management system.

This application is intended only as a portfolio project.

[Spring initializr configuration](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.4.3.RELEASE&packaging=jar&jvmVersion=11&groupId=net.carloscabello&artifactId=spring-helpdesk&name=spring-helpdesk&description=Demo%20project%20for%20Spring%20Boot&packageName=net.carloscabello.springhelpdesk&dependencies=web,lombok,security,thymeleaf,data-jpa,devtools,h2,mariadb)

## User roles
* **Customer**: Users demanding help from a professional to solve their problems or resolve their queries.
* **Employee**: Users that are part of the organization providing support for customers. They are responsible to fulfill customers' requests.
* **Manager**: Users that are also part of the organization providing support, but at a management level. They can also fulfill customers' requests but their main task is to maintain the highest level of customer satisfaction.

## User stories

1. [US-1] **Register customer**: As a customer, I want to register in the platform so I can start sending tickets.
2. [US-2] **Register employees**: As a manager, I want to register new employees and managers in the platform so they can start working in customers' tickets.

3. [US-3] **Create ticket**: As a customer, I want to send a ticket through the platform so an employee can fulfill my query.
4. [US-4] **Send ticket message employee**: As an employee, I want to answer to customers' tickets so their requests can be successfully closed.
5. [US-5] **Send tickets message customer**: As a customer, I want to be able to respond to employees regarding my unresolved queries so I can provide further information on them.
6. [US-6] **Send ratings customer**: As a manager, I want customers to be able to leave a rating after each ticket after it is closed so I can have metrics on customer satisfaction.

References:

https://stormotion.io/blog/how-to-write-a-good-user-story-with-examples-templates/

https://www.mountaingoatsoftware.com/blog/names-should-not-be-needed-for-user-stories

https://netmind.net/user-stories-and-the-acronyms-to-help-develop-good-ones/

http://www.agilemodeling.com/artifacts/classDiagram.htm