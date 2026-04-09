# MySQL Lab

This project demonstrates a containerized MySQL environment managed via Portainer, providing a high-visibility orchestration interface for real-time monitoring and lifecycle management of system services.

By leveraging Docker Compose, the infrastructure is entirely stateless and reproducible, allowing for seamless deployment across different environments (WSL, Linux, or Cloud).

## Features
- **MySQL 8.0**: Database engine running in a Docker container.
- **Portainer**: Lightweight management UI for monitoring container status and network ports.
- **Persistent Storage**: Configured with Docker volumes to ensure data persists across restarts.

## Setup
1. Clone the repo: `git clone git@github.com:bangz-me/MySQL-Lab.git`
2. Create a `.env` file in the root directory.
3. Add your credentials: `MYSQL_ROOT_PASSWORD=your_secret_here`
4. Run the environment: `docker-compose up -d`
5. Access the dashboard: `https://localhost:9443`

## Professional Skills Demonstrated
- Infrastructure as Code (Docker Compose)
- System Monitoring & Orchestration
- Git/GitHub Version Control Best Practices
