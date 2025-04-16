# AWS Project 2: Load Balanced Architecture with Advanced Request Routing

## 📌 Overview
In this project, I deployed a load-balanced web application using Amazon EC2 and an Application Load Balancer (ALB). The project includes a **path-based** routing to direct traffic to different EC2 instances based on the request.

This is part of a hands-on learning series inspired by [Neil Davis's AWS projects](https://digitalcloud.training).

---

## 🧰 Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- Listener Rules
- Security Groups

---

## ⚙️ What I Did
- Launched 2 EC2 instances with unique content
- Created an ALB and configured target groups
- Set up **path-based routing** (e.g., `/red`, `/blue`)
- Tested and validated routing behavior via browser

---

## 🖼️ Screenshots
| Load Balancer Dashboard | Listener Rules | Test Results |
|-------------------------|----------------|--------------|
| ![Load Balancer]<img width="1200" alt="alb" src="https://github.com/user-attachments/assets/af979001-cea5-4715-b516-19d9b29fb0c6" /> | ![Listener Rules]<img width="1172" alt="listener" src="https://github.com/user-attachments/assets/9ed44b2f-659f-45c7-baec-1e6f31327855" /> | ![Test 1]<img width="1055" alt="red" src="https://github.com/user-attachments/assets/9ccfe69a-d5c6-48f6-bf94-9133233771a2" /> ![Test 2]<img width="1058" alt="blue" src="https://github.com/user-attachments/assets/2c1e5332-5dad-457e-afe8-c903064a9d96" /> |


---

## ✅ Outcome
- Successfully demonstrated request routing using ALB
- Reinforced my understanding of EC2, load balancers, and routing rules
- Gained more comfort working in the AWS Management Console

---
