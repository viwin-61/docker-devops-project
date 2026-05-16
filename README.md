# 🚀 Docker & Docker Compose DevOps Project

## 📌 Project Overview

This project demonstrates hands-on experience with Docker and Docker Compose by building and managing multiple containers.

The project includes:

* Dockerfile creation
* Custom Docker image building
* Docker Compose YAML configuration
* Multi-container deployment
* Port mapping
* Shared volumes and networks
* Ubuntu container operations
* GitHub project management

---

# 🛠️ Technologies Used

* Docker
* Docker Compose
* NGINX
* Ubuntu
* HTML
* CSS
* Git
* GitHub

---

# 📂 Project Structure

```text
docker-devops-project
│
├── digital-team
│   ├── Dockerfile
│   └── index.html
│
├── journey
│   ├── Dockerfile
│   └── index.html
│
├── compose_task_folder
│   └── docker-compose.yml
│
├── screenshots
│   ├── digital-team-ui.png
│   ├── docker-ps.png
│   ├── compose-output.png
│   └── ubuntu-container.png
│
├── .gitignore
└── README.md
```

---

# 🐳 Docker Commands Used

## Build Docker Images

```bash
docker build -t digital-team:v1 .
docker build -t journey:v1 .
```

---

## Run Docker Containers

```bash
docker run -d -p 8081:80 --name digital-team-container digital-team:v1
```

```bash
docker run -d -p 8082:80 --name journey-container journey:v1
```

---

# ⚙️ Docker Compose Commands

## Start Containers

```bash
docker compose up -d
```

## Check Running Containers

```bash
docker compose ps
```

## View Logs

```bash
docker compose logs
```

## Stop Containers

```bash
docker compose stop
```

## Remove Containers

```bash
docker compose down
```

---

# 🌐 Application Access

| Application  | URL                                            |
| ------------ | ---------------------------------------------- |
| Digital Team | [http://localhost:8081](http://localhost:8081) |
| Journey      | [http://localhost:8082](http://localhost:8082) |

---

# 🧩 Docker Compose Features

✅ Multi-container deployment

✅ Shared Docker network

✅ Shared Docker volume

✅ Port mapping configuration

✅ Ubuntu container integration

✅ Container orchestration using Docker Compose

---

# 📸 Project Screenshots

## 🚀 Digital Team UI

Add your colorful website screenshot here.

---

## 🐳 Docker Containers Running

Add docker ps screenshot here.

---

## ⚙️ Docker Compose Output

Add docker compose screenshot here.

---

## 🐧 Ubuntu Container Operations

Add ubuntu container screenshot here.

---

# 📖 Learning Outcomes

Through this project, I learned:

* Docker image creation
* Dockerfile usage
* Container management
* Docker networking
* Docker volumes
* Docker Compose orchestration
* Multi-container deployment
* Linux container operations
* GitHub project management

---

# 🔥 Future Enhancements

* Push Docker images to Docker Hub
* Deploy using Kubernetes
* Add Jenkins CI/CD pipeline
* Deploy on AWS Cloud
* Add Monitoring & Logging tools

---

# 👨‍💻 Author

## Viwin

GitHub:

[https://github.com/viwin-61](https://github.com/viwin-61)

Project Repository:

[https://github.com/viwin-61/docker-devops-project](https://github.com/viwin-61/docker-devops-project)

