# Tarot Card Draw – AWS Deployment

This project implements a client-server Tarot Card Draw application in Java, hosted on AWS using EC2, Docker, and ECS. The server returns three unique Tarot cards (past, present, future) to a client upon connection.

# Key Features

Client-Server Communication: TCP-based communication; server automatically sends three cards to the client on connection.

Dockerized Deployment: Server containerized with Docker, pushed to Docker Hub, and run on EC2 instances.

AWS EC2 & ECS: Deployed multiple EC2 instances using Docker images; created an ECS cluster for task management.

Load Balancing & Scaling: Designed for horizontal scaling with AWS Load Balancer; traffic distributed across multiple server replicas with health checks.

Automation: EC2 instances configured to start the server automatically on boot using systemd and shell scripts.

# Skills Demonstrated

Cloud deployment and management (AWS EC2, ECS, VPCs)

Docker containerization and image management

TCP/IP networking and Java socket programming

Load balancing, scaling, and automated service management

Technical documentation and evidence collection (screenshots, step-by-step setup)
