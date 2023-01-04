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

# CDN Solutions & Cloud Technologies</br>
1. Cloudflare - Cloudflare offers ultra-fast static and dynamic content delivery over our global edge network. It helps reduce bandwidth costs and takes advantage of built-in unmetered DDoS protection.</br>
2. Fastly - Fastly's Deliver@Edge is a modern, efficient, and highly configurable CDN that gives you the freedom to control how your content is cached so you can deliver the content your users want quickly.</br>
3. Akamai - Akamai has a large variety of offerings for API Acceleration, Global Traffic Management, Image & Video Management, Media Delivery, and much more.</br>
4. Amazon CloudFront - Amazon CloudFront is a content delivery network (CDN) service built for high performance, security, and developer convenience. Some of its use-cases include delivering fast secure websites, accelerating dynamic content delivery and APIs, live streaming, video-on-demand, and others.</br>
5. Google Cloud Platform CDN - GCP CDN offers fast, reliable web and video content delivery with a global scale and reach.</br>
6. Microsoft Azure Content Delivery Network Microsoft's CDN solution offers global coverage, full integration with Azure services, and a simple setup.</br>

# Non-Relational Databases - Solutions</br>
1. Key/Value Stores Examples</br>
a. Redis</br>
b. Aerospike</br>
c. Amazon DynamoDB</br>

2. Document Store Examples</br>
a. Cassandra</br>
b. MongoDB</br>
c. Graph Databases Examples</br>
d. Amazon Neptune</br>

3. NEO4J</br>

# Scalable Unstructured Data Storage - Cloud and Open Source Solutions</br>
1. Cloud-Based Object Store Solutions</br>
a. Amazon S3 (Simple Storage Service) - Amazon's highly scalable cloud storage service that stores object data within buckets. Designed to store and protect any amount of data for various use cases, such as websites, cloud-native applications, backups, archiving machine learning, and analytics.</br>

b. GCP Cloud Storage - Google Cloud's managed service for storing unstructured data for companies of all sizes</br>

c. Azure Blob Storage -  Microsoft's massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning</br>

d. Alibaba Cloud OSS (Object Storage Service) - Fully managed enterprise-ready Object Storage Service to store and access any amount of data from anywhere.</br>

2. Open Source and Third-Party Object Store Solutions</br>
1. OpenIO - A software-defined open-source object storage solution ideal for Big Data, HPC, and AI. It is S3 compatible and can be deployed on-premises or cloud-hosted on any hardware that you choose.</br>

2. MinIO - High-performance, S3-compatible object storage. It is native to Kubernetes and 100% open source under GNU AGPL v3.</br>

3. Ceph - Open-source, reliable and scalable storage. Ceph provides a unified storage service with object, block, and file interfaces from a single cluster built from commodity hardware components.</br>
