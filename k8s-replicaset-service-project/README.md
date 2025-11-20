# 🚀 K8s of using ReplicaSet and Service ( NodePort )  for live dashboard project 


---

## 📌 Project Overview

**K8s** is a simple but visually appealing web app deployed on Kubernetes using:

* ✅ ReplicaSet for high availability
* ✅ Service (NodePort) for external access
* ✅ Custom HTML UI for attractive presentation

---

## 🧠 Concept Used

| Component  | Purpose                                          |
| ---------- | ------------------------------------------------ |
| ReplicaSet | Maintains 3 identical pods for high availability |
| Service    | Exposes the application to the browser           |
| Curl       | Used to test the app from terminal               |

---

## 📂 Project Structure

```
k8s-replicaset-service-project/
│
├── live-rs.yaml
├── live-service.yaml
├── index.html
└── Dockerfile
├── style.css
├── app.js
└── README.md

---

## 🧱 Architecture Flow

User (Browser / curl)
↓
NodePort Service
↓
ReplicaSet
↓
Multiple Apache Pods

---


## 🌐 Application Preview

When accessed via browser:

```
http://<NODE-IP>:32000
```
You will see a dashboard page displaying: as shown in 

### ⭐ If you like this project, give it a star on GitHub!
