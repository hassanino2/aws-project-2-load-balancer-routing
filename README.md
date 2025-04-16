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

---

## ✅ Outcome
- Successfully demonstrated request routing using ALB
- Reinforced my understanding of EC2, load balancers, and routing rules
- Gained more comfort working in the AWS Management Console

---
