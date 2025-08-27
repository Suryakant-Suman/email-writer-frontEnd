# 📧 Email Reply Generator (Frontend)

This is the **frontend** of the Email Reply Generator application.  
It allows users to **generate AI-powered email replies** by entering the original email content and selecting a desired tone (e.g., Formal, Friendly, Professional, Casual).  

The frontend is built with **React + Vite** and styled using **Material UI (MUI)**. It communicates with a **Spring Boot backend** via REST API.

---

## 🚀 Features

- ✨ Enter original email content  
- 🎨 Choose tone of the reply (Formal, Friendly, Professional, Casual)  
- ⚡ Generate AI-powered replies instantly  
- 📋 Copy generated reply to clipboard  
- 🔄 Handles loading states and errors gracefully  

---

## 🛠️ Tech Stack

- **Frontend Framework**: React + Vite  
- **UI Library**: Material UI (MUI)  
- **HTTP Client**: Axios  
- **Backend API**: Spring Boot (running on `http://localhost:8080`)  

---

## 📂 Project Structure

<img width="523" height="286" alt="image" src="https://github.com/user-attachments/assets/c47107ee-3793-4589-971f-d859f4eaf63c" />

---


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Suryakant-Suman/email-writer-frontEnd.git
cd email-writer-frontEnd
```
---
## 2️⃣ Install dependencies
```bash
npm install
```

---
## 3️⃣ Run the development server
```
npm run dev
```
Now open http://localhost:5173 in your browser.
---
## 🔗 API Integration
The frontend calls the backend API at:
```
POST http://localhost:8080/api/email/generate
```
---

## Request Body:
```

{
  "emailContent": "Your original email text here",
  "tone": "Formal"
}
```

## Response (Example):
```
"Dear Sir, Thank you for reaching out..."
```
---

## 📸 Screenshots
Main Interface

<img width="1135" height="498" alt="image" src="https://github.com/user-attachments/assets/3ad1433d-a859-4097-aec1-487bb94d5ad7" />


<img width="1222" height="725" alt="image" src="https://github.com/user-attachments/assets/f565e56c-40db-49b4-bfe4-7cc3fd4f766e" />


<img width="1368" height="571" alt="image" src="https://github.com/user-attachments/assets/89640d35-63f2-4859-9ef9-472e50398e57" />


<img width="1175" height="789" alt="image" src="https://github.com/user-attachments/assets/5dc26391-735b-4d40-b616-5744c908d6c0" />


---
## 📌 Future Improvements

🌐 Add authentication

🎯 Support more tones

📱 Improve responsive design

☁️ Deploy to cloud (Netlify/Vercel + Render/Heroku)

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

---

## 👩‍💻 Author  

**Suryakant Suman**  

🔗 [GitHub](https://github.com/Suryakant-Suman) | [LinkedIn](https://www.linkedin.com/in/suryakantsuman/)



