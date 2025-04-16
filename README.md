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
| ![Load Balancer](screenshots/lb-dashboard.png) | ![Listener Rules](screenshots/listener-rules.png) | ![Test 1](screenshots/test1.png) ![Test 2](screenshots/test2.png) |
<img width="1172" alt="Screenshot 2025-04-15 at 9 00 19 PM" src="https://github.com/user-attachments/assets/dabfd7e4-7225-4259-86e1-20548de56b48" />
<img width="1172" alt="Screenshot 2025-04-15 at 8 57 04 PM" src="https://github.com/user-attachments/assets/117a1b3b-d788-4f16-9e6b-cffc1a04a8ed" />
<img width="1200" alt="Screenshot 2025-04-15 at 8 56 29 PM" src="https://github.com/user-attachments/assets/65455617-f291-46b7-9da7-9ec0480e840a" />
<img width="1055" alt="Screenshot 2025-04-15 at 8 55 46 PM" src="https://github.com/user-attachments/assets/d985f1ef-0110-47c9-9be6-b52d66437049" />
<img width="1058" alt="Screenshot 2025-04-15 at 8 55 32 PM" src="https://github.com/user-attachments/assets/a25367ad-d46c-4c6f-9e1b-5e72015d1d6c" />
---

## ✅ Outcome
- Successfully demonstrated request routing using ALB
- Reinforced my understanding of EC2, load balancers, and routing rules
- Gained more comfort working in the AWS Management Console

---
