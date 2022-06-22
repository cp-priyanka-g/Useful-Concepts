# Useful-Concepts

Sprint-6 includes Some Advance Concepts.

1. Http Protocols

HTTP:

> The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems.

HTTP - Parameters

- HTTP Version
- Uniform Resource Identifiers
- Date/Time Formats
- Character Sets
- Content Encodings
- Media Types
- Language Tags

HTTP- Header fields

- General
- Reponse
- Request

HTTP- Status Code

- 1XX : informational
  - request/received processing
- 2XX: Success
  - Successfully understood,received and accepted.
- 3XX: Redirect
  - further action must taken/ redirect.
- 4XX: Client Error
  - Request doesn't have what is requested.
- 5XX: Server Error - Server fail to fulfil an apparent valid request.

            - 200 : OK
            - 201 : Ok created
            - 301 : move to new url
            - 304 : Not Modified
            - 400 : Bad request
            - 401 : UnAuthorized
            - 404 : Not found
            - 500 : internal server error

2. Asynchronous vs synchronous behaviour

- https://www.geekinsta.com/difference-between-synchronous-and-asynchronous-programming/

3. Caching(Understanding of Redis)

- https://www.nexcess.net/blog/what-is-redis-cache/#:~:text=So%2C%20what%20is%20Redic%20cache,almost%20all%20major%20programming%20languages.

4. Testing : unit and feature testing overview

   > For unit Test

   - https://www.zealousweb.com/unit-testing-vs-functional-testing-a-guide-on-why-what-how/#:~:text=Unit%20testing%20and%20Functional%20testing,the%20level%20of%20system%20testing.

   - https://www.guru99.com/unit-testing-guide.html

   > For Feature Test

   - https://www.softwaretestinghelp.com/feature-testing-tutorial/

5. Docker in detail
   - https://docker-curriculum.com/
6. Nginx vs Apache server

- https://www.javatpoint.com/difference-between-apache-and-nginx

7. Server Login with Password/SSH Keys

- https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server

8. IP tables

- https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall/

9. Php-fpm and httpd

- https://www.digitalocean.com/community/tutorials/how-to-configure-apache-http-with-mpm-event-and-php-fpm-on-ubuntu-18-04

10. Basic linux commands

- https://maker.pro/linux/tutorial/basic-linux-commands-for-beginners

- Cloud

1. What is AWS?

- https://www.techtarget.com/searchaws/definition/Amazon-Web-Services

2. S3 :Simple Storage Service

- Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.

- https://www.youtube.com/watch?v=e6w9LwZJFIA

3. EC2: Amazon Elastic Compute Cloud.
   Amazon EC2 provides cloud hosted virtual machines, called "instances", to run applications.

- https://www.youtube.com/watch?v=8TlukLu11Yo

4. RDS: Relational Database Service
   It provides affordable relational databases in the cloud, that is easy to use.

- Amazon RDS minimizes relational database management by automation.
- Amazon RDS creates multiple instances for high availability and failovers
- Amazon RDS supports PostgreSQL, MySQL, Maria DB, Oracle, SQL Server, and Amazon Aurora

- https://www.youtube.com/watch?v=tLp8pPNdDXQ
- https://www.w3schools.com/whatis/whatis_aws_rds.asp

5. Elasticache: Amazon ElastiCache is a fully managed, in-memory caching service supporting flexible, real-time use cases. You can use ElastiCache for caching, which accelerates application and database performance, or as a primary data store for use cases that don't require durability like session stores, gaming leaderboards, streaming, and analytics.

- https://aws.amazon.com/elasticache/
- https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/GettingStarted.html?pg=ln

6. Route 53:Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. You can use Route 53 to perform three main functions in any combination: domain registration, DNS routing, and health checking.

- https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html

7. SES

- Amazon Simple Email Service (SES) is a cost-effective, flexible, and scalable email service that enables developers to send mail from within any application. You can configure Amazon SES quickly to support several email use cases, including transactional, marketing, or mass email communications. Amazon SES's flexible IP deployment and email authentication options help drive higher deliverability and protect sender reputation, while sending analytics measure the impact of each email. With Amazon SES, you can send email securely, globally, and at scale.

8. Cloudwatch : Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), IT managers, and product owners.

- https://aws.amazon.com/cloudwatch/

9. VPC : Amazon Virtual Private Cloud (Amazon VPC) enables you to launch AWS resources into a virtual network that you've defined. This virtual network closely resembles a traditional network that you'd operate in your own data center, with the benefits of using the scalable infrastructure of AWS.

- https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html

10. AWS Lamda

- https://www.guru99.com/aws-lambda-function.html

-AWS Lambda is a serverless, event-driven compute service that lets you run code for virtually any type of application or backend service without provisioning or managing servers. You can trigger Lambda from over 200 AWS services and software as a service (SaaS) applications, and only pay for what you use.

11. AWS API Gateway : Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

- https://aws.amazon.com/api-gateway/

12. Microservices : Microservices are an architectural and organizational approach to software development created to speed up deployment cycles, foster innovation and ownership, improve maintainability and scalability of software applications, and scale organizations delivering software and services by using an agile approach that helps teams work independently.

- https://aws.amazon.com/microservices/

13. What are microservices? How AWS implement it?

- https://docs.aws.amazon.com/whitepapers/latest/microservices-on-aws/microservices-on-aws.html

14. Microservices implementation using Go

- https://blog.canopas.com/golang-serverless-microservices-with-gin-f3c2a4943a6d
