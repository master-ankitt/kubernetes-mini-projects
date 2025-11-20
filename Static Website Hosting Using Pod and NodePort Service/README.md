🟩 Static Website Hosting on Kubernetes (Pod + NodePort Service)

This mini-project demonstrates how to host a static website using an Apache HTTPD server inside a Kubernetes Pod, and expose it externally using a NodePort Service.
It is simple, beginner-friendly, and perfect for learning basic Kubernetes networking.

📘 Project Description

In this project:

A custom Apache HTTP server hosts a simple static webpage.

The application runs inside a Kubernetes Pod.

A NodePort Service exposes the application outside the cluster.

Labels and selectors are used to link the Pod and Service.

Basic troubleshooting is performed using curl, logs, and exec.

This project helps in understanding the fundamentals of Pods, Services, labels, selectors, ports, and minimal Kubernetes networking.

🧩 Key Components Used

Pod

NodePort Service

Labels & Selectors

Port Mapping

Basic Troubleshooting (curl, logs, exec)

📁 Project Structure
Static Website Hosting Using Pod and NodePort Service/
│
├── Dockerfile
├── index.html
├── pod.yaml
└── service.yaml
