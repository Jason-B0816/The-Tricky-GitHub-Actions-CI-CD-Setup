# 🚀 The Tricky GitHub Actions CI/CD Setup

A full-stack application demonstrating how to integrate a robust **CI/CD pipeline using GitHub Actions**, Cypress testing, and Render deployments. This project ensures **quality control** and **automatic deployment** every time code changes flow through the `develop` and `main` branches.

---

## 📚 Table of Contents
- [📝 Description](#-description)
- [🛠️ Technology Used](#-technology-used)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [📸 Screenshot](#-screenshot)
- [🔗 Links](#-links)
- [🪪 License](#-license)
- [📬 Contact](#-contact)

---

## 📝 Description

This app simulates a professional developer workflow with:
- Pull requests triggering **Cypress component tests**
- Merging into `main` triggering **automatic deployment** to Render
- A backend using MongoDB and frontend using modern tools

---

## 🛠️ Technology Used

- ⚙️ **Node.js**
- 🧪 **Cypress**
- 🧰 **Express**
- 🗃️ **MongoDB (via Atlas)**
- 🌐 **Render**
- 📦 **GitHub Actions**
- 🖼️ **React** (if applicable)

---

## ⚙️ Installation

**1. Clone the repository:**
   ```
   bash
   git clone git@github.com:Jason-B0816/The-Tricky-GitHub-Actions-CI-CD-Setup.git
   ```
   **2. Navigate to the project directory:**
   ```
   cd The-Tricky-GitHub-Actions-CI-CD-Setup
   ```
   **3. Install dependencies:**
```
bash
npm install
```
**4. Set up your .env file:
```
env
MONGO_URI="your_mongo_uri
PORT=3001
```
---
🚀 Usage

**Run the development server:**
```
bash
npm run dev
```
**Run Cypress Component tests**
```
bash 
npx cypress open
```
**Push to develop to run tests.**
**Merge to main to trigger deploy on Render.**

---
## 📸Screenshot
![Screenshot Github Actions](./client/public/Screenshot%20Github%20Actions.png)

---
## 🔗Links 
* GitHub Repository: https://github.com/Jason-B0816/The-Tricky-GitHub-Actions-CI-CD-Setup

* Render Deployment: https://the-tricky-github-actions-ci-cd-setup.onrender.com

* GitHub Actions Docs: https://github.com/Jason-B0816/The-Tricky-GitHub-Actions-CI-CD-Setup/actions

* Render Deploy Hooks: https://api.render.com/deploy/srv-d0g44hadbo4c73b0g7pg?key=zZjPWcz-hhc

---
## 📝License 
This project is license under Apache License 

---
## 📬Contact 
Have questions or feedback? Reach out!

* GitHub Username: Jason-B0816

* GitHub: https://github.com/Jason-B0816

* Email: jbrooks200800@gmail.com
---