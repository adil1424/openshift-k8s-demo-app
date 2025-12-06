# OpenShift / Kubernetes Demo Application

This repository contains a simple containerized application that can be deployed on **Kubernetes** or **Red Hat OpenShift**.

It includes:
- Deployment
- Service
- Route (OpenShift)
- PersistentVolumeClaim (PVC)
- Dockerfile
- Sample Python application

This repo demonstrates core cloud-native deployment workflows and is suitable for interviews and portfolio showcase.

---

## 📁 Repository Structure

openshift-k8s-demo-app/
│── app/
│ └── app.py
│
│── Dockerfile
│── deployment.yaml
│── service.yaml
│── route.yaml
│── pvc.yaml
│── README.md


---

## 🚀 Deployment Instructions
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml


### OpenShift:
oc apply -f deployment.yaml
oc apply -f service.yaml
oc apply -f route.yaml

---

## 👤 Author  
Adil — Linux, Kubernetes, and Platform Engineer


### Kubernetes:

