# Student AI Hub 🎓

Student AI Hub is a full-stack AI-powered productivity platform designed to help students enhance learning, coding, and productivity using AI-driven tools.  
The platform integrates multiple AI services to provide tools such as code generation, debugging, resume analysis, roadmap generation, and content summarization within a unified interface.

It demonstrates full-stack application development, API integration, and multi-model AI orchestration using modern web technologies.

---

## 🌐 Live Demo

https://frontend-k5qm.onrender.com/

---

## 🚀 Features

The platform provides multiple AI-powered tools in one interface:

- 🤖 **AI Chatbot** – General-purpose AI assistant for questions and explanations  
- 🗺️ **Roadmap Generator** – Generates personalized learning roadmaps for technologies or skills  
- 📹 **Video Summarizer** – Creates concise summaries of YouTube educational videos  
- 📄 **Text Summarizer** – Summarizes long articles or study notes  
- 💻 **Code Generator** – Generates code snippets for multiple languages and frameworks  
- 🐛 **Code Debugger** – Detects issues in code and suggests fixes  
- 📄 **Resume Analyzer** – Evaluates resumes and provides improvement suggestions  
- ✅ **To-Do List** – Task management system for productivity  
- ⏱️ **Student Timer** – Focus timer for structured study sessions

---

## 👨‍💻 My Role

**Frontend Developer (with Backend Integrations)**

Responsibilities:

- Developed responsive user interfaces using React and Tailwind CSS  
- Integrated frontend components with backend REST APIs  
- Implemented dynamic AI model selection for multiple AI tools  
- Worked with backend endpoints connected to PostgreSQL  
- Ensured consistent UI/UX across multiple AI-powered modules

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Framer Motion
- Material UI
- Aceternity UI
- Zustand (state management)
- React Router DOM
- Axios

### Backend
- Node.js
- Express.js
- PostgreSQL
- JWT Authentication
- Bcrypt

### AI Integrations
- OpenAI API
- Google Gemini
- Cerebras Cloud
- Ollama (LLaMA models)
- OpenRouter

### Other Tools
- Puppeteer
- YouTube Transcript API
- Nodemailer

---

## 🏗️ System Architecture

Frontend (React) → Backend API (Express.js) → AI Services / PostgreSQL

Workflow:

1. User interacts with the React frontend  
2. Frontend sends requests to backend REST APIs  
3. Backend processes requests and communicates with AI services  
4. AI-generated responses are processed and returned to the frontend  
5. Certain features store or retrieve data from PostgreSQL

---

## ⚙️ Installation & Setup

### Prerequisites

- Node.js (v16 or above)
- PostgreSQL installed and running

---

### 1. Clone the Repository

```bash
git clone <repository-url>
cd student-ai-hub
```

---

### 2. Backend Setup

Navigate to backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the backend directory:

```env
PORT=3000
DATABASE_URL=postgresql://user:password@localhost:5432/student_ai_hub
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_key
GEMINI_API_KEY=your_gemini_key
CEREBRAS_API_KEY=your_cerebras_key
OPENROUTER_API_KEY=your_openrouter_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
```

Start backend server:

```bash
npm run dev
```

---

### 3. Frontend Setup

Navigate to frontend directory:

```bash
cd ../frontend
```

Install dependencies:

```bash
npm install
```

Create `.env` file if required:

```env
VITE_API_URL=http://localhost:3000
```

Run development server:

```bash
npm run dev
```

---

## 📁 Project Structure

```
student-ai-hub
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── services
│
├── backend
│   ├── routes
│   ├── controllers
│   ├── models
│   └── services
│
└── README.md
```

---

## 🚀 Future Improvements

- AI model benchmarking and performance comparison  
- Personalized learning analytics for students  
- Improved authentication and user management  
- Mobile-friendly UI improvements

---

## 🤝 Contributing

Contributions are welcome.  
Feel free to fork the repository and submit pull requests for improvements.