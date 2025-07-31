# 🤖 Virtual AI Assistant

A voice-controlled virtual AI assistant built using *Gemini AI* and *MERN Stack*, designed to make your web interactions faster and smarter! 🌐🎙

---

🎥 Demo
👉 👉  [click here](virtual-assistant-1-0dim.onrender.com/)


## ✨ Features

- 🎤 *Real-Time Voice Recognition*  
  Speak to J.A.R.V.I.S and it will understand and act!

- 🔎 *Voice Commands*  
  Open or search Google, YouTube, Instagram, Facebook, and more using simple voice instructions.

- 🧑‍🎨 *Customizable Avatar & Assistant Name*  
  Personalize your AI assistant with your own name and image using Cloudinary & Multer.

- 🔒 *Secure Login System*  
  Authenticated using JWT tokens and password encryption via bcrypt.js.

---

## 🛠 Tech Stack

- *Frontend:* React.js ⚛  
- *Backend:* Node.js + Express.js 🚀  
- *Database:* MongoDB 🍃  
- *Authentication:* JWT + bcrypt.js 🔐  
- *Voice Engine:* Web Speech API 🗣  
- *AI:* Gemini AI 🧠  
- *Image Upload:* Cloudinary + Multer 📤

---

## 🚀 How to Run Locally

1. *Clone the Repository*
   ```bash
   git clone https://github.com/yourusername/Virtual_Assistant.git
   cd Virtual_Assistant
   
2. Install Dependencies

npm install   # For backend
cd client
npm install   # For frontend

3. Setup Environment Variables
Create .env files for both frontend and backend. Add your keys (Mongo URI, JWT secret, Cloudinary keys, etc.).

4. Start the Project
# Run backend
npm start
# In a new terminal, run frontend
cd client
npm start
