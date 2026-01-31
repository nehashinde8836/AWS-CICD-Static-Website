

---

```markdown
# AWS CI/CD Static Website 🚀

[![Stars](https://img.shields.io/github/stars/nehashinde8836/AWS-CICD-Static-Website?style=social)](https://github.com/nehashinde8836/AWS-CICD-Static-Website/stargazers)
[![Forks](https://img.shields.io/github/forks/nehashinde8836/AWS-CICD-Static-Website?style=social)](https://github.com/nehashinde8836/AWS-CICD-Static-Website/network/members)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

A fully automated **CI/CD pipeline** deploying a static website to **AWS S3** using **AWS CodePipeline** and **CodeBuild**. Every code change pushed to GitHub is automatically deployed to the live website without manual intervention.

---

## 🌐 Live Demo

[View Live Website](https://cicd-pipeline-cloud-frontend.s3.eu-north-1.amazonaws.com/)

---

## 🏗 Project Features

- Fully automated deployment pipeline  
- Static website hosted on **AWS S3**  
- **CI/CD pipeline** with CodePipeline & CodeBuild  
- Live updates reflected immediately on code push  
- Responsive design with HTML & CSS  

---

## 📸 Screenshots

**Home Page**
![Home Page](https://via.placeholder.com/800x400.png?text=Home+Page+Screenshot)

**Pipeline Flow**
![Pipeline](https://via.placeholder.com/800x400.png?text=Pipeline+Screenshot)

**Deployment Status**
![Deployment](https://via.placeholder.com/800x400.png?text=Deployment+Screenshot)

*(Replace placeholders with your actual screenshots)*

---

## 🏗 Architecture

```

GitHub (Source) → CodePipeline → CodeBuild → AWS S3 (Static Website)

````

1. **Source Stage:** Pulls code from GitHub repository  
2. **Build Stage:** Validates code (optional for static sites)  
3. **Deploy Stage:** Pushes HTML/CSS files to S3 bucket  

---

## 💻 Technologies Used

- **Frontend:** HTML, CSS  
- **AWS Services:** S3, CodePipeline, CodeBuild  
- **Version Control:** Git, GitHub  

---

## ⚡ How to Use / Deploy

1. Clone the repository:

```bash
git clone https://github.com/nehashinde8836/AWS-CICD-Static-Website.git
````

2. Push to your GitHub repository:

```bash
cd AWS-CICD-Static-Website
git add .
git commit -m "Initial commit"
git push origin main
```

3. Configure your own **AWS S3 bucket** and **CodePipeline** to deploy the website (optional if you want your own live demo).

---

## 🎯 Key Learnings

* Hosting static websites on **AWS S3**
* Implementing fully automated **CI/CD pipelines** using CodePipeline & CodeBuild
* Debugging deployment issues like:

  * CSS not loading due to S3 path or permissions
  * Browser caching problems
* Real-world DevOps workflow from code push to live deployment

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Connect

Feel free to ⭐ star, fork, or contribute!
Follow me on GitHub: [Neha Shinde](https://github.com/nehashinde8836)

```

---

### ✅ **Tips to maximize stars and views**

1. Replace all screenshot placeholders with actual images.  
2. Keep your **Live Demo link** working and visible.  
3. Use **GitHub topics**: `AWS`, `CI/CD`, `DevOps`, `Static-Website`, `CodePipeline`.  
4. Share the repo on **LinkedIn, Twitter, Reddit, or Dev.to** with a small project description and screenshot GIFs if possible.  
5. Keep the README **clean, structured, and visually appealing**.  

---


```
