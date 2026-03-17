# DevOps CI/CD Pipeline Project

This project demonstrates an end-to-end DevOps CI/CD pipeline using modern DevOps tools and AWS cloud services.

## Technologies Used

- Docker
- Terraform
- Ansible
- Kubernetes
- AWS EC2
- GitHub

## Project Structure

app/
Dockerfile
index.html

terraform/
Infrastructure provisioning scripts

ansible/
Configuration management

k8s/
Kubernetes deployment files

## Workflow

1. Application containerized using Docker
2. Infrastructure created using Terraform
3. Configuration automated using Ansible
4. Application deployed using Kubernetes
5. Code stored and version controlled with GitHub

## Deployment Result

The application was containerized using Docker and deployed on an AWS EC2 instance.

Steps performed:

1. Created Docker image using Dockerfile
2. Ran container using Nginx
3. Deployed container on AWS EC2
4. Verified application using public IP address

Example access:

http://<EC2-PUBLIC-IP>

Example:

http://3.27.200.19

kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
kubectl get pods
kubectl get svc