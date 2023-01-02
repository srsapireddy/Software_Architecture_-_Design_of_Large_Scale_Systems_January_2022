# Software_Architecture_-_Design_of_Large_Scale_Systems_January_2023 </br>
1. How does a CDN work:
- https://www.youtube.com/watch?v=CiphZWq3ST4 </br>
2. Monitor Api Requests in chrome browser:
- https://www.youtube.com/watch?v=2l2yS6IBTIs

# RPC Frameworks
3. What is gRPC?:
- https://www.youtube.com/watch?v=hVrwuMnCtok
4. Apache Thrift:
- https://www.youtube.com/watch?v=tsW6vRVzdXQ
5. RMI (Remote Method Invocation) :
- https://www.youtube.com/watch?v=GKIwu6XyqPI

# Open Source Software Load Balancing Solutions
6. HAProxy
7. NGINX

# Cloud Based Load Balancing Solutions
8. AWS - Elastic Load Balancing (ELB)
a. Application (Layer 7) Load Balancer - Ideal for advanced load balancing of HTTP and HTTPS traffic
b. Network (Layer 4) Load Balancer - Ideal for load balancing of both TCP and UDP traffic
c. Gateway Load Balancer - Ideal for deploying, scaling, and managing your third-party virtual appliances.
d. Classic Load Balancer (Layer 4 and 7) - Ideal for routing traffic to EC2 instances.

9. GCP - Cloud Load Balancing</br>
a. External HTTP(S) Load Balancer - Externally facing HTTP(s) (Layer 7) load balancer which enables you to run and scale your services behind an internal IP address.</br>
b. Internal HTTP(S) Load Balancer - Internal Layer 7 load balancer that enables you to run and scale your services behind an internal IP address.</br>
c. External TCP/UDP Network Load Balancer - Externally facing TCP/UDP (Layer 4) load balancer</br>
d. Internal TCP/UDP Load Balancer - Internally facing TCP/UDP (Layer 4) load balancer</br>

10. Microsoft Azure Load Balancer</br>
a. Standard Load Balancer - Public and internal Layer 4 load balancer</br>
b. Gateway Load Balancer - High performance and high availability load balancer for third-party Network Virtual Appliances.</br>
c. Basic Load Balancer - Ideal for small scale application</br>

11. GSLB Solutions</br>
a. Amazon Route 53 - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service.</br>
b. Google Cloud Platform Load Balancer & Cloud DNS - Reliable, resilient, low-latency DNS serving from Google's worldwide network with everything you need to register, manage, and serve your domains.</br>
c. Azure Traffic Manager - DNS-based load balancing</br>

# Message Brokers Solutions & Cloud Technologies</br>
1. Open Source Message Brokers</br>
a. Apache Kafka - The most popular open-source message broker nowadays. Apache Kafka is a distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.</br>
b. RabbitMQ - A widely deployed open source message broker. It is used worldwide at small startups and large enterprises.</br>

2. Cloud Based Message Brokers</br>
a. Amazon Simple Queue Service (SQS) - Fully managed message queuing service that enables you to decouple and scale micro-services, distributed systems, and serverless applications.</br>
b. GCP Pub/Sub and Cloud Tasks - Publisher/Subscriber and message queue solutions offered by Google Cloud Platform. See this article for comparison between the two offerings</br>
c. Microsoft Azure Service Bus - Fully managed enterprise message broker with message queues and publish-subscribe topics</br>

# Open Source API Gateways</br>
1. Netflix Zuul - Zuul is a free and open-source application gateway written in Java that provides capabilities for dynamic routing, monitoring, resiliency, security, and more.</br>
2. Cloud-Based API Gateways</br>
a. Amazon API Gateway- Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. Supports RESTful APIs and WebSocket APIs (bi-directional communication between client and server).</br>
3. Google Cloud Platform API Gateway - Google Cloud Platform API Gateway enables you to provide secure access to your services through a well-defined REST API.</br>
