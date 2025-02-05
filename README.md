# DevOps workflow for deploying a Spring Boot application 
__Using following steps:__
* __Spring Boot App:__ Develop the application using Java.
* __GitHub:__ Store and manage the source code.
* __Maven:__ Build and package the application.
* __Docker:__ Containerize the application.
* __Jenkins (CI/CD):__ Automate the build and deployment process through pipelines.
* __Kubernetes:__ Deploy and manage the containerized application.
* __EKS (AWS):__ Use Amazon's Elastic Kubernetes Service for orchestration and scaling.

## **follow below step on screenshot**
![Image](https://github.com/user-attachments/assets/cc241b98-e375-4c32-a2a8-35081bb8c0de)
<br><br>
![Image](https://github.com/user-attachments/assets/1ce0ac7c-2680-4602-bf4c-f5d7a4c5313a)

![Image](https://github.com/user-attachments/assets/54a62bf5-a30e-4851-94ce-23ee98c7e00c)

## now Jenkins is Ready😄
<br><br>
![Image](https://github.com/user-attachments/assets/c1239282-fbf6-4432-b072-94a520225d29)

## now launch k8s cluster on EKS
![Image](https://github.com/user-attachments/assets/d2b2c58b-33cd-48c0-bd88-b06c95bcad0a)

![Image](https://github.com/user-attachments/assets/e103e2d1-7ec0-4b21-8b19-3b1e316e4dc6)

## update EKS password on Jenkins Server
![Image](https://github.com/user-attachments/assets/40fb9731-fc75-41c8-bb8d-c4808d87c5b8)

![Image](https://github.com/user-attachments/assets/bceac4a2-2b93-481d-9031-64e2232e4bfc)

![image](https://github.com/user-attachments/assets/c800eff2-58e4-4e0f-9c8f-09cbe0c8229c)

## On Jenkins Server start build the Upstream and Downstream jobs
### Buildspring boot
![image](https://github.com/user-attachments/assets/c14c05ab-5eed-47d9-8bce-f35a442c0cea)

![image](https://github.com/user-attachments/assets/0fea39f3-bfd7-4e84-807e-3885cf6bf049)

![image](https://github.com/user-attachments/assets/a269a3be-d0d9-4aba-8b00-bab9cb74ca1c)

![image](https://github.com/user-attachments/assets/cbb0fe46-be1b-40da-8fac-b93f93f5b715)

### Testspring boot

![image](https://github.com/user-attachments/assets/fd0d5e58-7178-4979-82a9-0d76e98a9617)

### Deployspring boot
![image](https://github.com/user-attachments/assets/ba25de3e-b9a0-470d-a9b7-ffa600f092f6)

![image](https://github.com/user-attachments/assets/fecd64be-f1c4-4839-b722-85dd8285fad4)

![image](https://github.com/user-attachments/assets/e9cec81d-6839-40ad-be05-54e3f0959337)

![image](https://github.com/user-attachments/assets/8cef2eb7-3e33-4537-8cc1-ed29a0d8135a)

![image](https://github.com/user-attachments/assets/b9ba5868-9dd1-4d00-ab1d-3e1bd2c1db9b)

## add  build pipeline view plugin for better view

![image](https://github.com/user-attachments/assets/ae55bfc1-83db-46f7-a933-5b1cca43a87d)

![image](https://github.com/user-attachments/assets/2c04467e-a119-4467-873d-3db5abe44f17)

![image](https://github.com/user-attachments/assets/e88618e8-13c0-439b-b001-73c72bef2736)

## Now a Devloper upload a code on github the spring boot application deploying automatically

![image](https://github.com/user-attachments/assets/8064b78f-58f3-42d4-a662-f2a870afdf62)

![image](https://github.com/user-attachments/assets/ed070ab6-4a80-4b62-907e-ce8bce47a710)

![image](https://github.com/user-attachments/assets/412e160f-6fc9-43fa-b3c1-fac452fb9340)

## now the pipeline is started
![image](https://github.com/user-attachments/assets/92d56808-0c8e-4e5e-ae8c-485cee613785)

## the app is build and upload on docker hub
![image](https://github.com/user-attachments/assets/b180944d-5cac-4fd6-ad4c-70fff56ce1f9)

![image](https://github.com/user-attachments/assets/2534f976-9f65-45eb-80f1-c08dbe8c827c)

## now the build is complete
![image](https://github.com/user-attachments/assets/48e1b883-cc7e-47d5-ad73-634f0f8b8024)

## now get the ip address of the cluster 
![image](https://github.com/user-attachments/assets/6d6a2845-3aad-4cdf-9fc6-7425c95b0d3f)

## now the course web app page is launched successfully 
![image](https://github.com/user-attachments/assets/c78e5754-f674-4b1c-9069-d645175a1b5d)


