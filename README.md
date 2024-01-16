This folder contains the deployment manifests for Manam APP.


Environments:
1) development
2) production


#System Artitechture:
![](https://raw.githubusercontent.com/shalons-devops/aasets/main/Manam-arch.png)

**This project covers two environments: development (dev) and production (prod).
**

### Overview:
This project uses Kubernetes (K8s) to deploy a Dockerized Node.js backend and a Next.js frontend. The backend is set up in a microk8s cluster with a single replica, exposed through a Cluster IP service, and linked to an Ingress controller. The Ingress is connected to the domain **manam.72designstudio.com**. The backend communicates with a **MongoDB** server for data.

The Next.js frontend is hosted outside the cluster.


### Technologies Used:

| Frontend  | Backend   | Database | Containerization and Orchestration |
| ------------ | ------------ | ------------ |
|   Next.js|  Node.js | MongoDB | Docker, Kubernetes(microk8s) |


### Accessing the Application

[    Frontend: manam.app](https://www.manam.app "    Frontend: manam.app")   
[Backend API: manam.72designstudio.com](https://manam.72designstudio.com "Backend API: manam.72designstudio.com")


**PLEASE REFER TO THE README.MD FILE IN THE DEVELOPMENT SECTION FOR COMPREHENSIVE INFORMATION, DEPLOYMENT STEPS, AND TROUBLESHOOTING GUIDELINES**

