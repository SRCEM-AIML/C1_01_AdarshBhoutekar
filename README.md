# C1_01_AdarshBhoutekar# Django Docker Project 🚀

## 📌 Project Overview
This project is a simple **Django web application** that runs inside a **Docker container** and includes a **Jenkins pipeline** for automated deployment. It consists of **two Django apps (`app1`, `app2`)** and serves static pages without a database.

---

## 🛠️ Features
✅ Multi-App Django Project (`app1`, `app2`)  
✅ No database (static pages only)  
✅ Fully Dockerized with a `Dockerfile`  
✅ CI/CD Pipeline with Jenkins  
✅ Docker image pushed to **Docker Hub**  

---

## 📂 Folder Structure
DjangoDockerProject/ │── Assignment/ # Main Django Project │ ├── settings.py │ ├── urls.py │ ├── wsgi.py │ ├── asgi.py │ ├── init.py │ ├── manage.py │ │── app1/ # First Django App │── app2/ # Second Django App │── Dockerfile # Docker Configuration │── Jenkinsfile # CI/CD Pipeline Configuration │── README.md # Documentation │── .gitignore # Ignore unnecessary files

yaml
Copy
Edit

---

## 🚀 How to Run the Project Locally
### 🔹 **Step 1: Clone the Repository**
```sh
git clone https://github.com/AdarshBhoutekar/DjangoDockerProject.git
cd DjangoDockerProject
🔹 Step 2: Build and Run with Docker
sh
Copy
Edit
docker build -t assignment_project .
docker run -p 8000:8000 assignment_project
🔹 Step 3: Access the Web App
Open your browser and go to:

cpp
Copy
Edit
http://127.0.0.1:8000/
🐳 Docker Hub Repository
You can pull the Docker image from Docker Hub using:

sh
Copy
Edit
docker pull adarshhh1/assignment_project
🔗 Docker Hub Repository Link:
👉 https://hub.docker.com/repository/docker/adarshhh1/assignment_project

⚡ Jenkins Pipeline (CI/CD)
This project includes a Jenkinsfile that automates:

Cloning the GitHub repository

Building the Docker image

Pushing the image to Docker Hub

📝 Technologies Used
Python 3.10

Django

Docker

Jenkins

Git & GitHub

📌 Author
👨‍💻 Adarsh Bhoutekar
📌 GitHub: AdarshBhoutekar
📌 Docker Hub: adarshhh1

🎉 Project Completed! 🚀
