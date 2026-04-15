# fitscale-devops
#ScreenShots:
<img width="1407" height="887" alt="image" src="https://github.com/user-attachments/assets/6257080a-b15e-49e0-84e6-68713ad9ab5f" />
<img width="1482" height="820" alt="image" src="https://github.com/user-attachments/assets/827b3ad5-837d-4cbd-9792-462fc695557f" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d82ced39-9cbf-4eb0-91b8-5fa46e707b4b" />
<img width="1910" height="916" alt="image" src="https://github.com/user-attachments/assets/85882567-a3f8-4c25-a9a7-cdd232d4a6fa" />

## 👨‍💻 Team Members| Name | Role ||------|------|| **Shubhankar Tiwari** | DevOps Engineer / Backend || **Arjun Setia** | CI/CD & Git Workflow |---## 📌 Project OverviewFitScale DevOps Project is a **production-style backend application** built using **Node.js & Express**, containerized with **Docker**, and automated with a **CI pipeline using GitHub Actions**.This project simulates a **real-world DevOps workflow**, including:- Code collaboration- Branching strategy- Containerization- Continuous Integration (CI)---## 🧱 Architecture Diagram
Developer → GitHub (dev branch)
↓
GitHub Actions (CI)
↓
Build & Run Node App
↓
Docker Container
↓
Runs on Port 5000
---## 🛠️ Tech Stack| Category | Tools ||----------|------|| Backend | Node.js, Express || Version Control | Git, GitHub || Containerization | Docker || CI/CD | GitHub Actions |---## ⚙️ Features- ✅ REST API using Express  - ✅ Dockerized backend service  - ✅ CI pipeline with GitHub Actions  - ✅ Multi-branch Git workflow  - ✅ Merge conflict resolution  - ✅ Automated build on push  ---## 🐳 Docker Setup### 🔹 Build Image```bashdocker build -t backend-app ./backend
🔹 Run Container
docker run -p 5000:5000 backend-app
👉 Access app at:
http://localhost:5000

🔄 CI Pipeline (GitHub Actions)
Trigger:


On push to:


dev


main




Workflow Steps:


Checkout repository


Setup Node.js


Install dependencies


Run backend server



🌿 Git Workflow Strategy
feature/* → dev → main


main → Production


dev → Integration


feature/* → Development



🚧 Challenges & Solutions
❌ Issues Faced:


Merge conflicts in backend files


CI pipeline not triggering


Wrong workflow file placement


Git push rejection errors


Node_modules accidentally pushed


✅ Solutions:


Manual conflict resolution


Correct .github/workflows/ci.yml structure


Proper Git pull → commit → push sequence


Debugging CI logs


Understanding Git internals

📈 Learning Outcomes


Deep understanding of DevOps lifecycle


Hands-on with Docker & CI/CD pipelines


Git branching & collaboration strategies


Debugging real-world production issues



🚀 Future Enhancements


🔹 Add frontend (React)


🔹 Deploy on cloud (AWS / Render)


🔹 Add automated testing stage


🔹 Implement full CI/CD (build + deploy)


🔹 Use Docker Compose



📸 Project Preview

Backend running on port 5000 🚀


📌 Conclusion
This project demonstrates a complete DevOps pipeline from development to automation using industry-standard tools.
It reflects real-world engineering practices and problem-solving under actual development conditions.
