# AmirBABA: Advanced Flight Booking Platform

## Overview

AmirBABA is an advanced flight booking platform that enhances the interaction between passengers and airlines through a microservices architecture. This platform offers scalable, isolated services that are specifically tailored to meet the diverse requirements of different user groups.

## Platform Highlights

### User-Friendly Registration System
AmirBABA features a dedicated microservice for user registration, accommodating both passengers and airlines. New users can sign up effortlessly, using a username and password, and integrate seamlessly with the platform.

### Dynamic Flight Management
Our Flight microservice enables airlines to add and manage flight schedules comprehensively. Passengers logged into the system can view a real-time list of all available flights across various airlines, helping them make well-informed booking decisions.

### Efficient Ticketing Interface
The Ticket microservice allows passengers to book tickets and review their purchase history. Airlines benefit from this service as well, as it enables them to track ticket sales efficiently. All transactions are processed smoothly, ensuring immediate updates and confirmations.

### Seamless Front-End Experience
The FrontEnd microservice is responsible for all user interactions, providing a smooth and responsive experience through a well-designed interface that supports HTML and JSP files, backed by robust FrontEnd Servlets.

## Technical Details

### Dedicated Databases
Each microservice operates its own MySQL database, containerized using Docker. This setup simplifies deployment across various environments and enhances the consistency and scalability of our application infrastructure.

### Asynchronous and Synchronous Communications
AmirBABA utilizes Kubemq for asynchronous messaging between microservices, which facilitates fast and reliable data transfer without requiring response waits. For synchronous operations, a Kubernetes cluster enables direct, real-time communication among services, essential for tasks that demand immediate data consistency.

### N-layer Architecture
Our microservices are developed using an n-layer architecture, separating business logic, data access, and user interface layers. This architecture improves maintainability and supports agile development and testing practices.

### Cloud Deployment and Kubemq Integration
Hosted on the Google Cloud, AmirBABA benefits from the robustness of cloud infrastructure and utilizes Kubemq for efficient inter-service messaging. This ensures optimal performance, even under high demand.

## Conclusion

AmirBABA combines the convenience of online booking with the efficiency of modern software architectures, positioning it as a top choice for today's dynamic travel industry. It offers a transparent, easy-to-navigate platform for passengers planning their journeys and airlines managing their operations.

## Tools Used

1. Java
2. Apache Tomcat
3. Docker Containers
4. Kubernetes Cluster
5. Kubemq Channel
6. Google Cloud Environment
7. MySQL Database
8. HTML
9. CSS
10. Servlet
