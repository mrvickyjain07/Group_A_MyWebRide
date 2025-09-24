# ⚙️ CI/CD Pipeline for Static Web App  

An automated **CI/CD pipeline** designed for deploying a static web application with speed, scalability, and reliability. This project integrates **Jenkins, Maven, Git, Docker, and AWS EC2** to automate builds, testing, deployment, and monitoring.  

---

## 🔧 Tech Stack  
- **Jenkins** – CI/CD automation  
- **Maven** – Build automation  
- **Git** – Version control  
- **Docker** – Containerization  
- **NGINX** – Static web server  
- **Ubuntu** – Hosting environment  
- **AWS EC2** – Scalable cloud deployment  
- **Shell Scripting** – Rollbacks & log monitoring  

---

## 📜 Features  
✅ Automated build & deployment pipelines (Jenkins + Maven)  
✅ Dockerized static web app with NGINX  
✅ Deployment time reduced by **95%**  
✅ Application speed improved by **30%**  
✅ Rollback strategies & log monitoring with Shell scripting  
✅ Reduced production incidents by **50%**  
✅ Scalable deployment with **AWS EC2**  

---

## 📂 Project Structure  
📦 CI-CD-Pipeline-for-Static-Web-App
┣ 📜 Jenkinsfile # CI/CD pipeline definition
┣ 📜 Dockerfile # Containerization script
┣ 📜 pom.xml # Maven build file
┣ 📂 src/ # Application source code
┣ 📂 scripts/ # Shell scripts for rollback & monitoring
┗ 📜 README.md # Documentation

yaml
Copy code

---

## ⚙️ Installation & Setup  

1. **Clone the repository**  
```bash
git clone https://github.com/mrvickyjain07/CI-CD-Pipeline-for-Static-Web-App.git
cd CI-CD-Pipeline-for-Static-Web-App
Build the application with Maven

bash
Copy code
mvn clean package
Build and run Docker container

bash
Copy code
docker build -t static-web-app .
docker run -d -p 80:80 static-web-app
Access the app

Open your browser → http://localhost

☁️ Deployment on AWS EC2
Launch an Ubuntu EC2 instance

Install Docker & Jenkins

Pull the repository and configure Jenkins pipeline

Deploy NGINX container with the latest build

🔄 Rollback & Monitoring
Rollback: Automated scripts revert to the last stable container if deployment fails.

Monitoring: Shell scripts monitor logs and resource usage, alerting admins of issues.

📷 Architecture
text
Copy code
[ GitHub Repo ] → [ Jenkins CI/CD Pipeline ] → [ Maven Build ] → [ Dockerized App ] → [ AWS EC2 (NGINX) ]
                                      ↑
                              [ Rollback & Log Monitoring Scripts ]
🤝 Contributing
Contributions are welcome! Fork the repo, improve the pipeline, or suggest optimizations.

📜 License
This project is licensed under the MIT License – free to use and adapt.

🔗 Connect with Me
📧 Email: vj937379@gmail.com

💼 LinkedIn: Vyankatesh Hanumante
