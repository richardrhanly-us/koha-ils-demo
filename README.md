# koha-ils-demo

Self-hosted Koha Integrated Library System (ILS) deployed in a Dockerized Ubuntu server environment.

---

## Overview

This project demonstrates the deployment and configuration of a production-style Koha ILS environment using Linux and containerization.

Koha is a widely used open-source library management system that supports cataloging, circulation, patron management, and OPAC (public catalog access). This project simulates a real-world library system deployment while showcasing system administration and backend infrastructure skills.

---

## Key Skills Demonstrated

- Linux server setup (Ubuntu)
- Docker & Docker Compose deployment
- Web application hosting and configuration
- Database-backed system management
- Library systems (ILS) domain knowledge

---

## System Architecture

User Browser  
→ Koha Web Interface (Docker container)  
→ Koha Application Layer  
→ Database (MariaDB/MySQL)

---

## Features

- Containerized Koha ILS deployment
- Staff interface (library administration tools)
- OPAC (public-facing catalog)
- Web-based system configuration
- Isolated development environment using Docker

---

## Tech Stack

- Ubuntu Server
- Docker / Docker Compose
- Koha ILS
- MariaDB (Koha backend database)
- Linux CLI tools

---

## Setup Summary

1. Provision Ubuntu server (local VM or cloud droplet)
2. Install Docker and Docker Compose
3. Clone repository
4. Configure environment variables
5. Launch Koha using Docker Compose
6. Access Koha web installer via browser
7. Complete Koha initial setup (database, admin user, preferences)

---

## Demo Workflows

- Log into Koha staff interface
- Search catalog via OPAC
- Configure system preferences
- Navigate cataloging and circulation modules
- Manage basic library settings

---

## Screenshots

(Add screenshots here)

- Login screen
- Staff dashboard
- OPAC search
- Administration panel

---

## What This Project Shows

This project demonstrates the ability to:

- Build and manage Linux-based server environments
- Deploy and configure containerized applications
- Work with real-world enterprise-style systems
- Translate domain-specific tools (library systems) into technical implementations

---

## Future Improvements

- Multi-branch library configuration
- Sample MARC record dataset
- Patron and circulation simulation
- Reverse proxy (NGINX) setup
- SSL/HTTPS configuration

---

## Author

Richard Hanly  
Digital Services Specialist | Software Development Student
