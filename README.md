# 2-Tier Flask Application on AWS

---

### **1. Project Overview**

A 2-tier web application (Flask + MySQL) is hosted on EC2 instance and containerized using Docker and Docker Compose. CI/CD pipeline is created using Jenkins to pull the deliverables from SCM and automate the build and deploy process.

---

### **Steps**

1. Launch EC2 instance and set necessary inbound rules (8080 for jenkins and 5000 for flask)
2. Install dependencies like git, docker, jenkins
3. Configure jenkins on the instance. It will be accessible via http://<public-ip>:8080
4. Build a pipeline with stages (clone github repo, docker containerization)
5. After successful build, web application will be accessible via http://<public-ip>:5000
   
---

<img width="940" height="392" alt="image" src="https://github.com/user-attachments/assets/9f76dd8e-3101-49ed-84e0-14402692c1ae" />

<img width="940" height="405" alt="image" src="https://github.com/user-attachments/assets/453e81b8-ff02-472b-a792-36f54336240c" />

<img width="1725" height="942" alt="image" src="https://github.com/user-attachments/assets/7a6096d1-250b-4ffa-8842-7067aa75db9f" />

