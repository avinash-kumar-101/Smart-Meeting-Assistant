# 🚀 Smart Meeting Assistant – AI Powered Meeting Intelligence Platform

Smart Meeting Assistant is an AI-based real-time meeting platform that automatically generates meeting summaries, action items, and key decisions so teams can focus on discussion instead of documentation.

Live Demo: (add link if deployed)  
GitHub Repo: (current repo link)

---

## 🧠 Why Smart Meeting Assistant?

Most meetings are productive, but the follow-up work is painful – notes, tasks, and summaries.  
Smart Meeting Assistant solves this by combining real-time video streaming with AI intelligence to deliver:

- Instant meeting summaries  
- Auto-generated action points  
- Clear decisions and highlights  
- Up to 70% reduction in manual note-taking effort  

**Goal:** Make meetings smarter, faster, and more productive.

---

## ✨ Key Features

- Real-time video meetings using Stream SDK  
- AI-powered summaries with Google Gemini  
- Automatic action item detection  
- Fast and responsive UI built with Next.js  
- Dockerized backend for easy deployment  
- Secure API handling using environment variables  
- Mobile-friendly design  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS  
- **Backend:** Python (FastAPI/Flask style)  
- **AI Engine:** Google Gemini AI  
- **Video SDK:** Stream SDK  
- **Containerization:** Docker  
- **Deployment:** Local / Cloud Ready  

---

## 🧩 How It Works (Simple Flow)

1. User joins a meeting from the Next.js frontend  
2. Stream SDK handles real-time video and audio  
3. Meeting data is sent to Python backend APIs  
4. Backend sends data to Gemini AI  
5. AI returns summary, action points, and highlights  
6. User receives clean, structured output instantly  

---

## ⚙️ How to Run the Project (Local Setup)

### Backend (Docker – Recommended)

```bash
cd backend
docker build -t smart-meeting-backend .
docker run -p 8000:8000 --env-file .env smart-meeting-backend
```

Backend runs on:  
http://localhost:8000

---

### Frontend (Next.js)

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:  
http://localhost:3000

---

## 🔐 Environment Variables

Create a `.env` file inside the backend folder:

```env
STREAM_API_KEY=your_stream_key
STREAM_API_SECRET=your_stream_secret
CALL_ID=demo-room
GEMINI_API_KEY=your_gemini_key
```

⚠️ **Important:** Never push `.env` files to GitHub. Always keep them in `.gitignore`.

---

## 🎯 Use Cases

- Corporate Meetings  
- Team Standups  
- Client Calls  
- Online Classes  
- Project Discussions  

Anywhere you need smart automation and clean documentation.

---

## 🧪 Development Approach

This project was built using a problem-first mindset, not just feature stacking:

- Understanding real meeting pain points  
- Designing clean and logical user flows  
- Optimizing API usage to avoid unnecessary calls  
- Keeping components reusable and scalable  
- Writing readable and maintainable code  

---

## 🚧 Challenges & Solutions

| Challenge      | Solution                         |
|---------------|----------------------------------|
| API timeouts   | Optimized request handling       |
| Real-time sync | Efficient Stream SDK usage       |
| AI latency     | Structured prompts               |
| Scalability    | Dockerized backend               |

---

## 🔮 Future Improvements

- User meeting history  
- Bookmark important moments  
- Analytics dashboard  
- Multi-language support  
- Smarter AI insights and recommendations  

---

## 📚 What This Project Demonstrates

- Strong understanding of full stack architecture  
- Real-world AI integration experience  
- Clean component-based design  
- Performance-focused frontend development  
- Product-oriented engineering thinking  

---

## 👨‍💻 Author

**Avinash Kumar**  
Final Year B.Tech CSE Student | Full Stack Developer | AI Enthusiast  

I love building real-world applications that solve actual problems.  
This project reflects my interest in AI, scalable systems, and product thinking.

LinkedIn: (add link)  
Email: (add email)

---

## 🤝 Usage & Integrity Notice

This repository is shared for learning, review, and evaluation purposes.  
Feel free to explore the code, understand the architecture, and learn from the approach.

---

## ⭐ Support

If you like this project, don’t forget to star ⭐ the repository – it really motivates me!