# Multitier-Architecture-With-Docker-On-RHEL8
This project demonstrates the deployment of a multi-tier architecture for a WordPress website using Docker containers. The architecture includes separate containers for the WordPress website and MySQL database, creating a scalable and modular environment.
Components:

WordPress Container:

Utilizes the official WordPress image from Docker Hub.
Configurable environment variables for customization.
Ensures isolated deployment and easy scaling.
MySQL Container:

Utilizes the official MySQL image from Docker Hub.
Provides a dedicated container for the database, enhancing security.
Allows customization of MySQL configurations.
Platform:

Deployed on a Red Hat Enterprise Linux 8 (RHEL 8) virtual machine.
Utilizes Docker to create isolated and reproducible environments.
Ensures compatibility with the latest RHEL 8 features.
