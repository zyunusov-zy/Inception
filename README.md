# Inception

## Overview
**Inception** is a containerized **multi-service deployment project** using **Docker and Docker Compose**. The project sets up a complete environment with **Nginx, MariaDB, WordPress, and Redis**, orchestrated using Docker Compose, following **42 School** guidelines.

## Features
### ✅ Completed Features:
- **Fully containerized setup** using Docker
- **Nginx** as a reverse proxy
- **MariaDB** as the database
- **WordPress** with a dynamic website setup
- **Redis** for caching
- **SSL/TLS encryption** for secure connections
- **Custom Docker network** for service isolation

## Tech Stack
- **Containerization:** Docker, Docker Compose
- **Web Server:** Nginx
- **Database:** MariaDB
- **CMS:** WordPress
- **Caching:** Redis

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/zyunusov-zy/Inception.git
   cd Inception
   ```
2. Build and start the services:
   ```sh
   docker-compose up --build -d
   ```
3. Access WordPress at `https://localhost` (or configured domain).
4. Stop and remove containers when needed:
   ```sh
   docker-compose down
   ```

## Deployment
This project is designed for **self-hosted deployments** using **Docker**. It ensures an isolated, reproducible, and secure environment.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

---
🚀 **Project Completed! Deploy your own containerized environment effortlessly!**

