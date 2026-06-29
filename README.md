# 👋 Hi, I'm Vytla Anjani Padma Sri

I'm a Software Engineer passionate about building scalable, user-focused applications and solving real-world problems through technology. I enjoy developing reliable backend systems, building full-stack applications, and continuously learning new technologies to create impactful software.

---
  
## 💼 Experience
  
**SDE Intern @ Amazon**
- **DEX Control Plane - Client Authorization & Dynamic Test Selection**
  - Designed and implemented client authorization for a serverless control plane enabling secure access for clients by creating a shared IAM role with trust policies in AWS CDK, extracting caller identity from ARNs at the Lambda layer, validating session to program mappings, and adding authorization Choice states in Step Functions that fail unauthorized requests before workflow execution.
  - Implemented Dynamic Test Selection feature replacing hardcoded integration tests with program specific test routing by creating test templates across 3 regions (NA, EU, FE), registering them in the test executor to return program specific tests based on the workflow input.
  
- **Latency Guardrail Tool**
  - Implemented a POC of Latency Governance report for PEPPA SKYDEN monitoring 30+ tenants across PIP, SIP, PIP Document and SIP Document APIs, computing Latency, Week-over-Week diff, Month-over-Month diff, Contribution %, Baseline Diff and Baseline Date metrics by querying CloudWatch data across AWS regions.
- **Additional Contributions**
  - Implemented per-client API metrics tracking by building a custom interceptor that captures client identity from AAA CloudAuth URNs and emits success/failure metrics per caller, providing granular visibility into client-specific API behavior for monitoring and debugging.
  - Implemented immutable patch stage version by adding a freeze mechanism that locks G2S2 stage versions immediately after creation, eliminating calls to mutable stage versions that were causing availability drops in production.
  - Reconciled a drifted CI/CD pipeline with its Infrastructure-as-Code source by auditing manual customizations across 7 production stages, backporting all manual pipeline changes into the LPT package without losing existing configurations and adding deployment safeguards to restore pipeline-as-code governance.
      
---
  
## 🛠️ Tech Stack
  
  | Categories | Technologies |
  |----------|-------------|
  | Languages | Python, C, C++, Java, JavaScript, TypeScript, Go |  
  | Backend | Flask, Node.js, Express.js |
  | Frontend | React.js, HTML, CSS, FullCalendar, Chart.js |
  | Cloud & DevOps | AWS (Lambda, IAM, CDK, Step Functions, CloudWatch, API Gateway), CI/CD Pipelines |
  | Databases | MongoDB, MySQL, SQLite |
  | Tools | Git, OpenCV, NumPy, Dlib, Pygame |
  
---
  
## 📂 Projects
  
  | Project Name| Description | Tech |
  |---------|-------------|------|
  | [PeakPath](https://github.com/34anjani/PeakPath) | AI-powered study planner with StudyBot, Pomodoro timer, and calendar sync | Flask, SQLite, LLaMA/Groq |
  | [CryptoTrack](https://github.com/34anjani/CryptoTrack) | Real-time crypto tracker with price alerts and interactive charts | React, Node.js, MongoDB |
  | [FSQDE](https://github.com/34anjani/FSQDE-Image-Encryption) | Multi-layer image encryption with security metrics dashboard | Flask, NumPy, MySQL |
  | [SirenSight](https://github.com/34anjani/SirenSight) | AI-based eye closure detection and drowsiness alert system | Python, OpenCV, Dlib |
  | [RoomNest](https://github.com/34anjani/RoomNest) | Hostel accommodation management with role-based auth | C++, File I/O |
  
---

## 📫 Connect With Me

   
  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vytla-anjani-padma-sri-3209a8254)
  [![Gmail](https://img.shields.io/badge/-Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:padmasrivytla@gmail.com)
  

---
  
⭐ Thanks for visiting my profile! Feel free to explore my repositories and drop a star if you find something useful!
