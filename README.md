# Infrapilot – The Future of Infrapilot

## 🚀 Overview

A dynamic landing page built to showcase my cloud infrastructure and DevOps skills to potential investors and employers. This project goes beyond a static HTML page by deploying on a production-grade server, implementing HTTPS security, and using modern deployment tools.

---

## 🌐 Live Site

👉 [https://infrapilot.xyz](https://infrapilot.xyz)

---

## 👨🏽‍💻 About Me

**Charity Audu**  
**Lead Cloud Engineer**

Cloud & DevOps enthusiast with hands-on experience in AWS, Nginx, server automation, and secure deployments. I hold an MSc in Software Engineering and enjoy solving real-world problems with scalable infrastructure.

---

## 🧱 Tech Stack

- **AWS EC2** – Server provisioning
- **Ubuntu 22.04** – Base operating system
- **Nginx** – Web server + reverse proxy
- **Certbot (Let’s Encrypt)** – Free SSL certificate
- **HTML/CSS + Tailwind** – UI
- **Git + GitHub** – Version control & deployment

---

## ⚙️ Deployment Steps

### 1. **Provisioning Server**
- AWS EC2 instance created
- Ubuntu 22.04 installed
- Security groups opened for ports 22 (SSH), 80 (HTTP), 443 (HTTPS)

### 2. **Web Server Setup**
- Installed Nginx:
  ```bash
  sudo apt update
  sudo apt install nginx
