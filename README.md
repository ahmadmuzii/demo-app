<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:3f3f46,100:f05032&height=180&section=header&text=Git%20Workflow%20Demo&fontSize=46&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=DevOps%20Assignment%203&descSize=17&descAlignY=60" width="100%" alt="Git Workflow Demo"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>
</p>

## 🧠 What This Is

A deliberately minimal two-tier app (Express backend + HTML/CSS/JS frontend) created for **DevOps Assignment 3**. The point is the **version-control workflow**, not the app: initialising a repo, structuring frontend/backend folders, ignoring `node_modules`, and building a feature through small, descriptive commits.

```mermaid
gitGraph
    commit id: "Add backend server"
    commit id: "Add project files"
    commit id: "Update login script"
    commit id: "Add login feature"
```

**My role:** individual assignment.

> ➡️ The full deployment version of this app — with an automated **AWS CodePipeline → CodeBuild → CodeDeploy** pipeline to EC2 and S3 — lives in **[PulseFit-DevOps](https://github.com/ahmadmuzii/PulseFit-DevOps)**.

## 🚀 Run

```bash
cd backend && npm install && node server.js   # → http://localhost:3000
```

Then open `frontend/index.html` in a browser.
