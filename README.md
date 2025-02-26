
# React Auth Application

A simple authentication system built with React and React Router, deployed on Netlify and GitHub Pages.

## 🚀 Live Demo Links
- 🔗 Netlify: [ReactAuthApplication](https://reactauthapplication.netlify.app/)
- 🔗 GitHub Pages: [ReactAuth on GitHub Pages](https://jayjaisswal.github.io/ReactAuth/)

## 📷 Preview
![React Auth Login](./images/login.png)
![React Auth Signup](./images/signup.png)

## 📌 Features
- 🔑 User authentication (Login & Signup)
- 🛡️ Protected routes with React Router
- 🌐 Hosted on **Netlify & GitHub Pages**
- 🔥 Notifications with React Hot Toast
- 🎨 Styled with Tailwind CSS (or any styling used)

## 🛠️ Tech Stack
- ⚛️ React.js
- 📦 React Router
- 🔥 React Hot Toast
- 🎨 Tailwind CSS (or CSS Framework used)

## 📂 Installation & Setup

### **1️⃣ Clone the Repository**

git clone https://github.com/jayjaisswal/ReactAuth.git
cd ReactAuth
### 2️⃣ Install Dependencies
npm install
### 3️⃣ Run the Project Locally
npm start
### 4️⃣ Build the Project for Production

npm run build
🚀 Deployment
🔹 Deploy to GitHub Pages
Add "homepage" in package.json
"homepage": "https://jayjaisswal.github.io/ReactAuth"
Install GitHub Pages package
npm install gh-pages --save-dev
Add scripts in package.json
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build",
}
Deploy with:

npm run deploy
🔹 Deploy to Netlify
Build the project

npm run build
Upload to Netlify
Drag & drop the build/ folder into Netlify Deploys
Or use Netlify CLI:

netlify deploy --prod
🤝 Contributing
Feel free to fork this repo, make changes, and submit a pull request.

📜 License
This project is open-source under the MIT License.