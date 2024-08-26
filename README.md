# Multi-Tier-Web-Application-Deployment---Local-Machine

## Overview
This project demonstrates the setup of a multi-tier web application, integrating various services to create a robust and scalable system.

## Architecture
- **MySQL (Database Service)**: Provides data storage and management.
- **Memcached (Database Caching Service)**: Speeds up data retrieval by caching queries.
- **RabbitMQ (Message Broker/Queue Service)**: Facilitates communication between services via message queuing.
- **Tomcat (Application Service)**: Hosts the web application and manages business logic.
- **Nginx (Web Service)**: Acts as a reverse proxy and load balancer, directing traffic to the appropriate services.

## Setup Instructions

### Prerequisites
- Local installations of MySQL, Memcached, RabbitMQ, Tomcat, and Nginx (Manual Provisioning)
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
- Vagrant, Vagrant plugins, VirtualBox, Git Bash

### Steps
1. **Clone the repository**:
    ```bash
    git clone -b main https://github.com/tobytoday/vprofile-project.git
    cd into vagrant/Manual_provisioning
    vagrant up # Bring Virtual Machines up 
    ```
2. **Configure environment variables** for database connections, message queue settings, rabbitMQ setup, tomcat, code build and deploy etc.
3. **Start the services** start them manually:
4. **Access the application** via NGINX IP has can be found in `cat /etc/hosts` or on while logged in to web01 machine `ip show address`.

## Technologies Used
- MySQL
- Memcached
- RabbitMQ
- Apache Tomcat
- Nginx
- Maven

## Reference 
https://www.udemy.com/course-dashboard-redirect/?course_id=3710504

## License
[MIT License](LICENSE)

## Contributing
Feel free to open issues or submit pull requests.

## Contact
For any inquiries, please reach out on [[LinkedIn](https://www.linkedin.com/in/oluwatobi-oni-22582159/)].

