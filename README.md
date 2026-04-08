# Sonarqube_docker_setup
Automated Code Quality Environment with SonarQube &amp; Docker

# Automated Code Quality Environment
An automated code quality analysis environment developed using 
SonarQube, Docker, and PostgreSQL. This project demonstrates 
the deployment of a fully containerized DevOps toolchain for 
continuous code inspection.

# AI-Powered Code Quality Analysis
A robust and scalable code quality environment built with 
**Docker Compose**, enabling automated static code analysis 
through **SonarQube** backed by a **PostgreSQL** database.

## Key Features
* **Containerized Deployment:** Fully dockerized setup using 
  Docker Compose for easy and reproducible deployment.
* **Code Quality Analysis:** Detects bugs, vulnerabilities, 
  and code smells automatically.
* **Web Dashboard:** Interactive SonarQube dashboard for 
  visualizing code quality metrics.
* **Persistent Database:** PostgreSQL container ensures 
  reliable data storage for analysis results.

## Tech Stack
* **Docker & Docker Compose**: Container orchestration and 
  service management.
* **SonarQube Community Edition**: Static code analysis and 
  quality gate enforcement.
* **PostgreSQL**: Relational database for storing SonarQube 
  data and configurations.
* **Ubuntu 22.04 (WSL2)**: Linux environment for hosting 
  the containerized services.

## How to Use
1. **Clone** the repository to your local machine.
2. **Start** the containers using Docker Compose.
3. **Access** the SonarQube dashboard via browser.
4. **Analyze** your code projects for quality issues.

## Installation (Local Setup)
Follow these steps to run the environment on your machine:

1. Clone the repository:
```bash
   git clone https://github.com/Ravishka14/sonarqube_docker_setup.git
```

2. Navigate to the project directory:
```bash
   cd sonarqube_docker_setup
```

3. Apply required kernel parameters (Linux):
```bash
   sudo sysctl -w vm.max_map_count=262144
   sudo sysctl -w fs.file-max=65536
```

4. Start the containers:
```bash
   docker-compose up -d
```

5. Access SonarQube:
```
   URL: http://localhost:9000
   Default credentials will be prompted on first login.
   It is recommended to change the password immediately 
   after first access.
```
