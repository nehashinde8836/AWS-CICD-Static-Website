

---

# AWS CI/CD Static Website Deployment 🚀

## 1️⃣ Project Title

**AWS CI/CD Pipeline for Automated Static Website Deployment**

---

## 2️⃣ Project Overview

This project demonstrates the implementation of a **fully automated CI/CD (Continuous Integration and Continuous Deployment) pipeline** using **AWS DevOps services**.
The pipeline automatically deploys a static website to **Amazon S3** whenever changes are pushed to the source code repository.

The goal of this project is to eliminate manual deployment and ensure **fast, reliable, and consistent website updates**.

---

## 3️⃣ Problem Statement

In traditional static website hosting:

* Developers must **manually upload files** to the server after every change.
* This process is **time-consuming and error-prone**.
* There is **no automation**, so frequent updates become difficult.
* Small mistakes (wrong files, missing CSS, incorrect paths) can break the website.
* There is **no standard DevOps workflow** to track deployments.

Hence, a system was required where:

* Code changes are automatically detected.
* Deployment happens without manual intervention.
* The live website always reflects the latest code.

---

## 4️⃣ Solution Approach

To solve these problems, we implemented a **CI/CD pipeline using AWS services**:

* **Source Code Management:** GitHub / AWS CodeCommit
* **CI/CD Automation:** AWS CodePipeline
* **Build & Validation:** AWS CodeBuild
* **Hosting:** Amazon S3 Static Website Hosting

With this approach:

* Any code change triggers the pipeline automatically.
* The updated website is deployed to S3.
* The live URL reflects the changes instantly.

---

## 5️⃣ What We Implemented

### ✔ Components Used

* **GitHub / CodeCommit** – Source code repository
* **AWS CodePipeline** – Orchestrates CI/CD workflow
* **AWS CodeBuild** – Builds and validates code
* **Amazon S3** – Hosts the static website
* **HTML & CSS** – Frontend website files

---

## 6️⃣ CI/CD Workflow

```
Developer Pushes Code
        ↓
Source Stage (GitHub / CodeCommit)
        ↓
Build Stage (AWS CodeBuild)
        ↓
Deploy Stage (AWS CodePipeline)
        ↓
Amazon S3 (Static Website Hosting)
```

---


## 9️⃣ Final Outcome

* CI/CD pipeline works successfully.
* Any change pushed to the repository is **automatically deployed**.
* Website updates reflect instantly on the **S3 static website URL**.
* Manual deployment is completely eliminated.

---

## 🔟 Key Learnings

* Understanding CI/CD concepts in real-world DevOps
* Working with AWS CodePipeline and CodeBuild
* Hosting static websites on AWS S3
* Debugging cloud deployment issues
* Importance of automation in DevOps

---


---

## 1️⃣2️⃣ Conclusion

This project successfully demonstrates a **real-world DevOps CI/CD workflow** using AWS.
It shows how automation improves deployment speed, reduces errors, and ensures reliable delivery of applications.

---

## 1️⃣3️⃣ Author

**Neha Shinde**
GitHub: [https://github.com/nehashinde8836](https://github.com/nehashinde8836)

---

### 💡 Pro Tip (For GitHub Stars ⭐)

Add **topics** in GitHub:

```
AWS, DevOps, CI-CD, CodePipeline, CodeBuild, S3, Static-Website
```

---



Just tell me 👍
