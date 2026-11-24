CloudConnect Portal – AWS 3-Tier Web Application
Project Overview
CloudConnect Portal is a cloud-based 3-tier web application deployed on Amazon Web Services (AWS). The project demonstrates how to build and host a web application using AWS infrastructure, load balancing, database services, and Python Flask.
The application uses a frontend built with HTML, CSS, and JavaScript, a Python Flask backend to handle application requests, and Amazon RDS MySQL for database storage.
The application is hosted on an Apache HTTP Server and made accessible through a custom domain configured using Amazon Route 53.

## Architecture
The project follows a 3-tier architecture:

**1. Presentation Layer (Frontend)**
- HTML
- CSS
- JavaScript
- Apache HTTP Server (httpd)

**2. Application Layer (Backend)**
- Python
- Flask Framework
- REST API
- Application Load Balancer

**3. Database Layer**
- Amazon RDS
- MySQL
- MariaDB

## AWS Services and Technologies Used

- **Amazon EC2:** Hosted frontend and backend application servers.
- **Amazon VPC:** Created an isolated network environment.
- **Public and Private Subnets:** Organized resources based on network accessibility.
- **Route Tables:** Managed network traffic routing.
- **Internet Gateway:** Enabled internet connectivity for public subnets.
- **NAT Gateway:** Enabled outbound internet access for private subnet resources.
- **Security Groups:** Controlled inbound and outbound traffic.
- **Application Load Balancer:** Distributed incoming application traffic.
- **Amazon RDS:** Hosted the relational database.
- **Amazon Route 53:** Configured domain name routing.
- **Apache HTTP Server:** Served frontend web pages.
- **Python Flask:** Developed backend APIs.
- **HTML, CSS and JavaScript:** Built the frontend interface.
- **MySQL / MariaDB:** Worked with relational database management.

## Key Features

- Cloud-hosted web application.
- Custom domain access using Route 53.
- Frontend and backend deployed on separate EC2 instances.
- Backend API integration using Python Flask.
- Database connectivity with Amazon RDS.
- User information retrieval from the database.
- Application traffic management using an Application Load Balancer.
- Network isolation and access control using VPC, subnets, route tables, and security groups.

## Project Learning Outcomes

- Hands-on experience with AWS networking and infrastructure.
- Understanding of public and private subnet architecture.
- Practical experience deploying web applications on EC2.
- Configuring Apache HTTP Server.
- Connecting Python Flask applications with Amazon RDS.
- Understanding load balancing and domain configuration.
- Implementing a cloud-based 3-tier application architecture.

## Conclusion

This project provided practical experience in designing, deploying, and managing a cloud-based web application using AWS services and open-source technologies. It helped strengthen my knowledge of cloud infrastructure, networking, backend development, and database integration.
