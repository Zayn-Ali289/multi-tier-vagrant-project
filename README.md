# Multi-Tier Vagrant Project

## Overview
This project demonstrates a multi-tier DevOps infrastructure setup using Vagrant and VirtualBox.

## Technologies Used
- Vagrant
- VirtualBox
- NGINX
- Apache Tomcat
- MariaDB
- RabbitMQ
- Memcached
- Linux Shell Scripting
  ## Component Explanation

### NGINX
Used as a reverse proxy and load balancer to handle incoming client traffic and forward requests to the Tomcat application server.

### Apache Tomcat
Used to host and run the Java-based web application.

### MariaDB
Used as the backend relational database for storing application data.

### RabbitMQ
Used as a message broker for asynchronous communication between services.

### Memcached
Used for caching to improve application performance and reduce database load.

## Architecture
- web01 → NGINX reverse proxy/load balancer
- app01 → Apache Tomcat hosting Java application
- db01 → MariaDB database server
- rmq01 → RabbitMQ messaging server
- mc01 → Memcached caching server

## Features
- Automated VM provisioning
- Private networking
- Multi-tier architecture
- Shell-based automation
- Java application deployment

## Commands

### Start VMs
```bash
vagrant up
```

### Check VM Status
```bash
vagrant status
```

### SSH into VM
```bash
vagrant ssh web01
```

## Author
Zayn Ali
