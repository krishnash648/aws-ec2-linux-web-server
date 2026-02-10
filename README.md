# AWS EC2 Linux Web Server with Nginx

This project demonstrates deploying and managing a Linux-based web server on **AWS EC2** using **Nginx**.  
It covers instance provisioning, secure access, Linux server configuration, and live web hosting.

---

## 🔗 Live Demo

👉 **EC2 Web Server (Production):**  
  http://13.203.227.127

👉 **GitHub Pages (Static Preview):**  
  https://krishnash648.github.io/aws-ec2-linux-web-server/

---

## 🧱 Architecture Overview

User Browser  
→ Internet  
→ AWS EC2 (t3.micro)  
→ Amazon Linux 2023  
→ Nginx Web Server  
→ Custom HTML Page

---

## 🛠️ Technologies Used

- AWS EC2 (t3.micro)
- Amazon Linux 2023
- Nginx
- SSH (key-based authentication)
- Git & GitHub
- GitHub Pages (documentation hosting)

---

## 🔐 Security Configuration

- SSH access (port 22) restricted via key pair
- HTTP access (port 80) enabled via Security Group
- Default VPC networking
- No hardcoded credentials
- UTF-8 encoding ensured for web content

---

## 🚀 What I Did (Step-by-Step)

1. Launched an EC2 instance using Amazon Linux 2023
2. Created and attached an SSH key pair
3. Configured Security Groups for SSH and HTTP
4. Connected to the instance via SSH
5. Installed and enabled Nginx
6. Verified Nginx service status
7. Deployed a custom HTML page
8. Fixed UTF-8 encoding issues
9. Verified public access using EC2 public IP
10. Uploaded project files to GitHub with documentation

---

## 🖥️ Key Linux Commands Used

```bash
ssh -i ec2-linux-key.pem ec2-user@<public-ip>
sudo dnf update -y
sudo dnf install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
systemctl status nginx
sudo nano /usr/share/nginx/html/index.html
```

---

## 📁 Project Files

- `index.html` → Custom web page served by Nginx
- `README.md` → Project documentation

---

## 📸 Proof of Work

- Live website accessible via public IP
- SSH access confirmed
- Nginx service running and enabled on boot
- GitHub Pages deployment active

---

## 📌 Why This Project Matters

This project proves hands-on skills in:

- Cloud infrastructure basics
- Linux server administration
- Web server deployment
- Secure remote access
- Real-world troubleshooting
- Professional documentation

---

## 👤 Author

**Krishna Sharma**  
Cloud & Infrastructure Enthusiast
