📧 AI Email Generator

An AI-powered email generation web application built with Spring Boot (Backend) and React + Vite (Frontend).
This project demonstrates full-stack development, REST API integration, and AI service consumption, making it a great showcase for recruiters and companies looking for skilled Java + React developers.

✨ Features

✅ Generate professional emails instantly using AI
✅ Clean and responsive frontend built with React + Tailwind CSS
✅ Robust backend built with Spring Boot
✅ RESTful API integration between frontend and backend
✅ Error handling & response validation
✅ CORS enabled for cross-origin communication
✅ Ready for deployment on Render / Vercel / Netlify

🛠️ Tech Stack

Frontend:

React (with Vite) ⚡

Tailwind CSS 🎨

Axios for API calls

Backend:

Java + Spring Boot 💻

REST API

Jackson (ObjectMapper, JsonNode) for JSON handling

Other Tools:

Git & GitHub

Postman (for API testing)

IntelliJ IDEA / VS Code

🚀 Project Architecture
Frontend (React + Vite)  --->  REST API calls  --->  Backend (Spring Boot) ---> AI Service

📂 Project Structure
/ai-email-generator
   ├── backend/  (Spring Boot REST API)
   ├── frontend/ (React + Vite client)

⚡ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-email-generator.git
cd ai-email-generator

2️⃣ Run Backend (Spring Boot)
cd backend
./mvnw spring-boot:run


Backend will start at 👉 http://localhost:8080

3️⃣ Run Frontend (React + Vite)
cd frontend
npm install
npm run dev


Frontend will start at 👉 http://localhost:5173

🌍 API Endpoints
Generate Email

POST /api/email/generate
Request Body:

{
  "prompt": "Write a formal email for job application"
}


Response:

"Dear Hiring Manager, ... "



🎥 Demo (Screenshots / GIFs)
![image alt](https://github.com/Tanishq1596/Email-Generator-using-AI/blob/main/Screenshot%202025-08-22%20205951.png?raw=true)
![image alt](https://github.com/Tanishq1596/Email-Generator-using-AI/blob/main/Screenshot%202025-08-22%20204541.png?raw=true)
![image alt](https://github.com/Tanishq1596/Email-Generator-using-AI/blob/main/Screenshot%202025-08-22%20204956.png?raw=true)
![image alt](https://github.com/Tanishq1596/Email-Generator-using-AI/blob/main/Screenshot%202025-08-22%20204806.png?raw=true)

💡 Why This Project?

This project is a strong demonstration of:

Full-stack application development

Java + Spring Boot backend skills

React + modern frontend skills

RESTful API integration

Ability to deploy & host applications

It’s perfect for recruiters to quickly understand my hands-on expertise with real-world project architecture.

📌 Future Improvements

Add user authentication (JWT)

Save email history to a database (MySQL/PostgreSQL)

Export generated email as PDF

Multi-language support

🤝 Connect With Me

LinkedIn: [[Your LinkedIn Link](https://www.linkedin.com/in/tanishq-jain-b64107280/)]
Email: tanishqjain7996@gmail.com
