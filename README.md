This folder contains the deployment manifests for Pledge APP.


Environments:
1) dev
2) prod


#System Artitechture:
![](https://raw.githubusercontent.com/shalons-devops/aasets/main/Pledge-arch.png)



### Overview:
- This project  utilizes Kubernetes to deploy a shared Dockerized Node.js backend and a React Native Android app frontend in two environments: **development (dev) and production (prod).**

- The backend is configured within a **microk8s cluster**, featuring a single replica, exposed through a **Cluster IP service**, and connected to an Ingress controller.

- The Ingress is associated with the domain** pledge.72designstudio.com.**

- The backend communicates with a **MongoDB** server to fetch data.

- The **React Native Android app** is designed to seamlessly interact with the shared backend and is accessible externally, hosted outside the cluster.


### Technologies Used:


| Frontend  | Backend   | Database | Containerization and Orchestration |
| ------------ | ------------ | ------------ |
|   React Native|  Node.js | MongoDB | Docker, Kubernetes(microk8s) |



### Accessing the Application

  
[Backend API:  pledge.72designstudio.com](https://pledge.72designstudio.com "Backend API: pledge.72designstudio.com")

**PLEASE REFER TO THE README.MD FILE IN THE DEVELOPMENT SECTION FOR COMPREHENSIVE INFORMATION, DEPLOYMENT STEPS, AND TROUBLESHOOTING GUIDELINES**
