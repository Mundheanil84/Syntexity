# Syntexity - Real-Time Collaborative Code Editor

**Syntexity** is an advanced platform designed for seamless real-time collaborative coding. It provides a smooth and conflict-free environment with built-in code compilation, intelligent editor locking, and contribution analysis tools. The platform also features integrated chat, multi-language support, and customizable themes, making coding more productive, engaging, and enjoyable.

---

## 🌐 Live Demo

- 🔗 Access the app: [syntexity.vercel.app](https://syntexity.vercel.app/)

---

## 🚀 Tech Stack

**Frontend**
- React.js  
- CodeMirror  
- D3.js  
- Tailwind CSS  

**Backend**
- Node.js  
- Express.js  
- Socket.io  
- WebRTC  
- MongoDB  

---

## ✨ Features

- ✅ **Built-in Code Compilation** for multiple languages  
- ✅ **Editor Locking System** to avoid conflicts during collaboration  
- ✅ **Contribution Analysis** for detailed project insights  
- ✅ **File Upload & Download** support  
- ✅ **Real-Time Collaborative Code Editing** with in-app chat  
- ✅ **Multi-Language Syntax Highlighting**  
- ✅ **Multiple Editor Themes** for a personalized experience  

---

## ⚙️ Local Setup

Follow these steps to set up the project locally:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/syntexity.git
   cd syntexity
   
2. Install dependencies
   ```bash
   npm install

3. Set up environment variables
Create a .env file in the root directory and add the following:
REACT_APP_BACKEND_URL="http://localhost:5050"
REACT_APP_clientId="jdoodle client id"
REACT_APP_clientSecret="jdoodle client secret"
MONGO_URL="your mongodb uri"

4. Run the backend server
   ```bash
   npm run server

5. Run the frontend
   ```bash
   npm start
   
## 📌 Notes

Real-time collaboration is powered by Socket.io and WebRTC.

Code execution is handled through JDoodle API integration.

Contribution tracking helps manage team productivity and project insights.

Fully customizable and extendable for new features.



