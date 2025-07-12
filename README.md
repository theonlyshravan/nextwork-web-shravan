# ☁️ Legendary AWS CI/CD DevOps Pipeline – NextWork Web Project

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![CodePipeline](https://img.shields.io/badge/CodePipeline-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![CodeBuild](https://img.shields.io/badge/CodeBuild-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![CodeDeploy](https://img.shields.io/badge/CodeDeploy-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-Tools-blueviolet?style=for-the-badge)

---

## 🚀 What is This Project?

This project demonstrates a complete CI/CD pipeline using **AWS services** integrated with **GitHub**, showcasing automation of building, testing, and deploying a web app on an EC2 instance using shell scripts and DevOps best practices.

---

## 🧾 Project Summary

- **Project Title**: Legendary AWS DevOps CI/CD Pipeline  
- **Author**: [Shravan Kumar Satapathy](https://www.linkedin.com/in/theonlyshravan)  
- **Stack**: AWS CodePipeline, CodeBuild, CodeDeploy, EC2, S3, GitHub, IAM.

---

## 🛠️ Tools & Technologies Used

- **AWS Services**: CodePipeline, CodeBuild, CodeDeploy, EC2, S3, IAM  
- **Version Control**: Git & GitHub  
- **Languages**: Shell scripting, HTML/JSP (demo app)  
- **CI/CD Concepts**: Webhooks, Artifacts, Auto Rollbacks, Execution Modes

---

## 🔄 Pipeline Stages

1. **Source**  
   GitHub repo is linked using webhook triggers to watch for commits on `main`.

2. **Build**  
   CodeBuild compiles and packages source code from GitHub into build artifacts.

3. **Deploy**  
   CodeDeploy deploys the artifacts to an EC2 instance with rollback enabled.

---

## 📁 Documentation

All implementation details are available in the `/docs` folder:

- [CI/CD Architecture Overview](docs/legendary-aws-devops-cicd.pdf)  
- [GitHub Integration Guide](docs/legendary-aws-devops-github.pdf)  
- [CodePipeline Setup](docs/legendary-aws-devops-codepipeline-updated.pdf)  
- [CodeBuild Details](docs/legendary-aws-devops-codebuild-updated.pdf)  
- [CodeDeploy Flow](docs/legendary-aws-devops-codedeploy-updated.pdf)  
- [CodeArtifact Configuration](docs/legendary-aws-devops-codeartifact-updated.pdf)

---

## 📦 Key Features

- ✅ Trigger on push to GitHub `main` branch  
- 🧪 Automatic artifact creation using CodeBuild  
- 🚀 EC2 deployment using CodeDeploy  
- 🔐 IAM-secured pipeline with rollback mechanisms  
- 🧰 Modular, maintainable, and production-ready flow

---

## 📌 How to Use This Project

1. Fork or clone this repository  
2. Set up AWS CodePipeline with this repo as the source  
3. Configure `buildspec.yml` and `appspec.yml` in root  
4. Launch an EC2 instance with correct IAM roles  
5. Observe full CI/CD workflow in action on code push

---

## 👨‍💻 Author

**Shravan Kumar Satapathy**  
![Badge](https://img.shields.io/badge/Role-Cloud%20%26%20DevOps%20Enthusiast-blue?style=flat-square)  
![Postman](https://img.shields.io/badge/Postman-Student%20Expert-orange?style=flat-square)  
![GCP](https://img.shields.io/badge/Google%20Cloud-GenAI%20Certified-lightgrey?style=flat-square)  
![Open to Work](https://img.shields.io/badge/Looking%20for-DevOps%20Internships-success?style=flat-square)

- 💡 Passionate about building scalable CI/CD workflows and cloud-native infrastructure  
- 🧾 Certifications in Postman API Fundamentals, Google Cloud GenAI & Vertex AI, AWS Forage Job Simulation  
- 🔍 Actively seeking DevOps & Cloud internship/trainee opportunities  
- 🌐 [GitHub](https://github.com/theonlyshravan)  
- 💼 [LinkedIn](https://www.linkedin.com/in/theonlyshravan)  
- 📬 Email: satapathyshravankumar@gmail.com  

---

## 💡 Future Improvements

- 📊 Add monitoring & alerting using **CloudWatch**  
- ☁️ Migrate to containerized workloads with **ECS** or **Elastic Beanstalk**  
- 🔐 Manage secrets with **AWS Secrets Manager**  
- 🧪 Add test coverage in CodeBuild (unit/integration)

---

## 📣 Like this Project?

If this repo helped you, consider giving it a ⭐ and sharing it with others!

---
