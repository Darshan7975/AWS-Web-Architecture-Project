# AWS-Web-Architecture-Project

AWS High Availability Web Architecture using  Load Balancer (LB), two Linux EC2 instances, and Amazon EFS for shared file storage.

## Project Overview

This project demonstrates a highly available web application using AWS Application Load Balancer (ALB), two linux EC2 instances, and Amazon Elastic File System (EFS).

## Architecture

Users → Load Balancer → EC2-server-1 and EC2-server-2 → Shared EFS storage.

## AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Amazon EFS
* Linux servers
* Security Groups

## Working

1. Users access the application through the ALB DNS name.
2. The ALB distributes requests between the EC2 instances.
3. Both EC2 instances access shared files stored in EFS.
4. Health checks allow the ALB to route traffic to healthy instances.

## Benefits

* High availability
* Load balancing
* Shared file storage
* Scalability

## Author

Darshan S R
