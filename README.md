# aws-cloud-devops-lab

A collection of hands-on AWS and DevOps tasks demonstrating infrastructure provisioning, cloud storage management, containerization, and version control.

This project showcases practical implementations using Amazon EC2, Amazon Machine Images (AMI), Amazon S3 Versioning, Docker, and Git.

---

# 🚀 Overview

This repository contains four independent tasks that cover common cloud and DevOps workflows.

## Tasks Included

- Provision an EC2 web server with Apache using User Data
- Create and deploy a reusable Amazon Machine Image (AMI)
- Manage object versions using Amazon S3 Versioning
- Build and manage Docker images
- Track and restore project history using Git

---

# 📂 Project Structure

```text
aws-cloud-devops-lab/
│
├── README.md
│
├── Task-1-EC2-Custom-AMI/
│
│   ├── user-data.txt
│   ├── index.html
│   ├── commands.txt
│   └── screenshots/
│
├── Task-2-S3-Versioning/
│ 
│   ├── exam_details.txt
│   ├── commands.txt
│   └── screenshots/
│
├── Task-3-Docker-Image/
│  
│   ├── Dockerfile
│   ├── docker_commands.txt
│   └── screenshots/
│
└── Task-4-Git-Version-Control/
   
    ├── git_commands.txt
    ├── exam_details.txt
    └── screenshots/
```

---

# 🛠 Tech Stack

- Amazon EC2
- Amazon Machine Image (AMI)
- Amazon S3
- Ubuntu Linux
- Apache HTTP Server
- Docker
- Git
- Linux Shell

---

# 📌 Task 1 — EC2 Web Server & Custom AMI

## Objective

Deploy an Ubuntu EC2 instance, configure Apache automatically using User Data, host a simple web page, create a custom AMI, and launch another instance from the generated image.

### Key Concepts

- EC2 Instance Provisioning
- Security Groups
- User Data
- Apache Web Server
- Amazon Machine Images (AMI)

### Workflow

```text
Launch EC2
      │
      ▼
Configure Security Group
      │
      ▼
Execute User Data
      │
      ▼
Install Apache
      │
      ▼
Deploy Web Page
      │
      ▼
Create Custom AMI
      │
      ▼
Launch New Instance
```

---

# 📌 Task 2 — Amazon S3 Versioning

## Objective

Create an S3 bucket with Versioning enabled, upload multiple revisions of a file, simulate object deletion, and restore previous versions.

### Key Concepts

- Amazon S3
- Bucket Versioning
- Object History
- Delete Markers
- Version Recovery

### Workflow

```text
Create Bucket
      │
      ▼
Enable Versioning
      │
      ▼
Upload Version 1
      │
      ▼
Upload Version 2
      │
      ▼
Upload Version 3
      │
      ▼
Delete Latest Version
      │
      ▼
Restore Previous Version
```

---

# 📌 Task 3 — Docker Image Management

## Objective

Create a Docker image from a Dockerfile, manage image tags, and verify image versions.

### Key Concepts

- Dockerfile
- Docker Build
- Image Tagging
- Image Management

### Workflow

```text
Dockerfile
     │
     ▼
docker build
     │
     ▼
Docker Image
     │
     ▼
Tag Image
     │
     ▼
Verify Images
     │
     ▼
Remove Tag
```

---

# 📌 Task 4 — Git Version Control

## Objective

Initialize a Git repository, create multiple commits, inspect commit history, and restore a previous project state.

### Key Concepts

- Repository Initialization
- Commit History
- Git Log
- Git Reset

### Workflow

```text
Working Directory
        │
        ▼
git add
        │
        ▼
git commit
        │
        ▼
Repository History
        │
        ▼
git log
        │
        ▼
git reset --hard
```

---

# 📈 Skills Demonstrated

- AWS Infrastructure Provisioning
- EC2 Deployment
- Apache Web Server Configuration
- Amazon Machine Images (AMI)
- Amazon S3 Object Versioning
- Docker Image Management
- Git Version Control
- Linux Command Line
- Cloud Resource Management
- DevOps Fundamentals

---

# 📷 Project Screenshots

Each task contains a dedicated `screenshots/` directory with the corresponding implementation and output images.

---

# 📄 License

This project is available under the MIT License.
