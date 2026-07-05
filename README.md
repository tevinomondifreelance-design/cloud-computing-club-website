<div align="center">

# ☁️ Cloud Computing Club Website

### Modern Static Website Hosted on AWS using Terraform & GitHub Actions

[![AWS](https://img.shields.io/badge/AWS-S3%20%7C%20CloudFront-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/Terraform-IaC-844FBA?logo=terraform&logoColor=white)](https://www.terraform.io/)
[![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**A responsive website for the Cloud Computing Club demonstrating modern frontend development, AWS cloud deployment, Infrastructure as Code, and CI/CD automation.**

🌐 **Live Website:** https://d2i2u7dk2xm8jy.cloudfront.net

</div>

---

# 📖 Overview

The **Cloud Computing Club Website** is a modern, responsive static website built to serve as the official online presence of a university cloud computing club.

Beyond being a club website, this project demonstrates practical cloud engineering skills including:

- Infrastructure as Code (Terraform)
- AWS Static Website Hosting
- Amazon CloudFront CDN
- GitHub Actions CI/CD
- Git Version Control
- Responsive Web Design

This project is designed as a portfolio piece that showcases cloud deployment best practices.

---

# ✨ Features

- Responsive design
- Mobile-friendly layout
- Modern landing page
- Cloud Computing Club branding
- Fast global delivery using CloudFront
- Infrastructure managed with Terraform
- Automated deployments using GitHub Actions
- Organized project structure
- Easy to extend with new pages and features

---

# 🛠 Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Cloud

- Amazon S3
- Amazon CloudFront
- AWS IAM

## Infrastructure

- Terraform

## DevOps

- Git
- GitHub
- GitHub Actions

---

# ☁️ AWS Architecture

```
                 Users
                    │
                    ▼
            Amazon CloudFront
          (Global CDN Distribution)
                    │
      Origin Access Control (OAC)
                    │
                    ▼
          Amazon S3 Static Website
                    │
                    ▼
           HTML • CSS • JavaScript
```

---

# 📂 Project Structure

```
cloud-computing-club-website/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── assets/
│   ├── css/
│   ├── icons/
│   ├── images/
│   └── js/
│
├── docs/
│   ├── architecture.md
│   ├── roadmap.md
│   ├── diagrams/
│   └── screenshots/
│
├── terraform/
│   ├── main.tf
│   ├── provider.tf
│   ├── variables.tf
│   ├── outputs.tf
│   ├── versions.tf
│   └── terraform.tfvars.example
│
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Deployment Workflow

```
Developer
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Actions
     │
     ▼
Amazon S3
     │
     ▼
CloudFront Distribution
     │
     ▼
Website Visitors
```

---

# 📸 Screenshots

## Home Page

> *(Add screenshot here)*

```
docs/screenshots/homepage.png
```

---

## Hero Section

> *(Add screenshot here)*

```
docs/screenshots/hero.png
```

---

## Projects

> *(Add screenshot here)*

```
docs/screenshots/projects.png
```

---

## Leadership

> *(Add screenshot here)*

```
docs/screenshots/team.png
```

---

# ⚙️ Infrastructure as Code

Infrastructure is fully provisioned using **Terraform**.

Resources include:

- Amazon S3 Bucket
- CloudFront Distribution
- IAM Configuration
- Bucket Policies
- Outputs
- Variables

---

# 🔄 Continuous Deployment

GitHub Actions automatically:

- Checks out the repository
- Configures AWS credentials
- Uploads website files to Amazon S3
- Invalidates the CloudFront cache
- Deploys the latest version automatically

---

# 🔐 Security

Current implementation includes:

- Infrastructure managed with Terraform
- AWS IAM user for deployment
- CloudFront CDN
- GitHub Secrets
- Private deployment credentials

### Planned Improvements

- Origin Access Control (OAC)
- Private S3 Bucket
- HTTPS using ACM
- Custom Domain
- AWS WAF

---

# 📈 Roadmap

## Completed

- Responsive Website
- AWS Deployment
- Terraform Infrastructure
- CloudFront CDN
- GitHub Repository
- Documentation

## Planned

- Events Page
- Club Gallery
- Resource Library
- Blog
- Member Directory
- Event Registration
- Newsletter
- Admin Portal
- Contact Form
- Analytics Dashboard

---

# 💼 Skills Demonstrated

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- GitHub Actions
- Terraform
- AWS S3
- Amazon CloudFront
- Infrastructure as Code
- CI/CD
- Static Website Hosting
- Cloud Architecture
- Technical Documentation

---

# 🤝 Contributing

Contributions are welcome.

Please read:

- CONTRIBUTING.md
- CODE_OF_CONDUCT.md

before opening a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

See the **LICENSE** file for details.

---

# 👨‍💻 Author

**Tevin Omondi**

Cloud Engineering | DevOps | AWS | Terraform

GitHub:
https://github.com/tevinomondifreelance-design

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a star!

Built with ❤️ using AWS, Terraform and GitHub Actions.

</div>