# Hair Salon Appointment Scheduler Project

## 🧾 Project Overview

**Client:** AnyCompany Web Consultancy  
**App Purpose:** Allows customers to book appointments and select hair salon services online.

A senior developer initially created the app but was moved to another project. My job was to complete development, testing, and deployment into a cloud-based staging environment.

---

## 🚀 Key Accomplishments

### 1. Application Development
- Reviewed and understood the existing Django codebase
- Made UI and backend improvements
- Implemented new functionality and fixed bugs

### 2. Unit Testing
- Wrote and executed unit tests using `unittest` and `coverage`
- Used mocked data and timezones to simulate and verify business logic
- Ensured database, booking logic, and announcement retrieval were covered

### 3. Continuous Integration (CI)
- Set up a CI pipeline using **AWS CodeBuild** and **AWS CodePipeline**
- Automated:
  - Dependency installation
  - Running unit tests
  - Generating coverage reports

### 4. Containerization
- Built a Docker container for the application
- Tagged and pushed images to **Amazon ECR (Elastic Container Registry)**

### 5. Deployment on Amazon EKS
- Used **Amazon Elastic Kubernetes Service (EKS)** to manage and deploy containerized workloads
- Applied Kubernetes manifests to create deployments and services
- Verified app functionality via `kubectl` and AWS Load Balancer DNS

### 6. Load Balancing and Scalability
- Installed the **AWS Load Balancer Controller**
- Tagged public subnets for subnet auto-discovery
- Used an **Application Load Balancer (ALB)** for distributing traffic
- Ensured the app could scale across availability zones

### 7. Continuous Delivery (CD)
- Extended the pipeline to:
  - Deploy containers automatically to the EKS cluster
  - Trigger redeployments on code updates or image changes

---

## 🛠 Technologies Used

- **Frontend & Backend:** Python, Django
- **CI/CD:** AWS CodePipeline, CodeBuild
- **Containerization:** Docker, Amazon ECR
- **Orchestration:** Kubernetes, Amazon EKS
- **Load Balancing:** AWS ALB, AWS Load Balancer Controller
- **Testing:** unittest, coverage, pylint
- **Infrastructure:** AWS Cloud9, IAM, VPC, Subnets, RDS (PostgreSQL), Route 53

### 6. Added Load Balancing
- Installed the AWS Load Balancer Controller
- Tagged public subnets so the controller could auto-discover them
- Set up an Application Load Balancer (ALB) to handle incoming traffic

### 7. Automated Deployment (CD)
- Updated the CI/CD pipeline to automatically deploy new containers to EKS
- Enabled automatic redeployments whenever code was pushed or the container image was updated

## Tools and Services Used

- **Languages & Frameworks:** Python, Django
- **Testing:** unittest, coverage, pylint
- **CI/CD:** AWS CodeBuild, AWS CodePipeline
- **Containers:** Docker, Amazon ECR
- **Orchestration:** Kubernetes, Amazon EKS
- **Load Balancing:** Application Load Balancer (ALB)
- **Infrastructure:** AWS Cloud9, IAM, VPC, RDS (PostgreSQL), Route 53

## What I Learned

This project gave me hands-on experience building a full CI/CD pipeline, working with Kubernetes, and deploying real apps on AWS. It challenged me to solve problems, automate tasks, and think like a DevOps engineer. It also showed me how different cloud services work together in a real development workflow.

## About Me

LinkedIn: https://www.linkedin.com/in/ovnevets/

