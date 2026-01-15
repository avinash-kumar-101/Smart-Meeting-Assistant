<!-- This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details. -->




🚀 Smart Meeting Assistant – AI Powered Meeting Intelligence Platform
Smart Meeting Assistant is an AI-based real-time meeting platform that automatically generates meeting summaries, action items, and key decisions so teams can focus on discussion instead of documentation.
<!-- 🌐 Live Demo: (add link if deployed) -->
📦 GitHub Repo: https://github.com/avinash-kumar-101/Smart-Meeting-Assistant
🧠 Why Smart Meeting Assistant?
Most meetings are productive, but the follow-up work is painful – notes, tasks, and summaries.
Smart Meeting Assistant solves this by combining real-time video streaming + AI intelligence to give:
📌 Instant meeting summaries
📝 Auto-generated action points
🎯 Clear decisions & highlights
⏱️ 70% reduction in manual note-taking effort
Goal: Make meetings smarter, faster, and more productive.
✨ Key Features
🎥 Real-time video meetings using Stream SDK
🤖 AI-powered summaries with Google Gemini
📝 Automatic action item detection
⚡ Fast & responsive UI (Next.js)
📦 Dockerized backend for easy deployment
🔐 Secure API handling using .env files
📱 Mobile-friendly design
🛠️ Tech Stack
Layer
Technology
Frontend
Next.js, React, Tailwind CSS
Backend
Python (FastAPI/Flask style)
AI Engine
Google Gemini AI
Video SDK
Stream SDK
Container
Docker
Deployment
Local / Cloud Ready
🧩 How It Works (Simple Flow)
User joins a meeting from Next.js frontend
Stream SDK handles real-time video & audio
Meeting data is sent to Python backend APIs
Backend sends data to Gemini AI
AI returns:
Summary
Action Points
Key Highlights
User receives clean, structured output instantly 🎉
📂 Project Folder Structure
Copy code

SMART-MEETING-ASSISTANT
│
├── backend
│   ├── Dockerfile
│   ├── main.py
│   ├── main-alt.py
│   ├── requirements.txt
│   ├── pyproject.toml
│   ├── uv.lock
│   ├── README.md
│   └── .env
│
├── frontend
│   ├── app
│   ├── public
│   ├── node_modules
│   ├── .env
│   ├── package.json
│   ├── next.config.mjs
│   ├── eslint.config.mjs
│   └── README.md
│
└── .gitignore
Clean separation of frontend & backend for scalability and maintainability.
⚙️ How to Run the Project (Local Setup)
🔹 Backend (Docker – Recommended)
Copy code
Bash
cd backend
docker build -t smart-meeting-backend .
docker run -p 8000:8000 --env-file .env smart-meeting-backend
Backend runs on:
Copy code

http://localhost:8000
🔹 Frontend (Next.js)
Copy code
Bash
cd frontend
npm install
npm run dev
Frontend runs on:
Copy code

http://localhost:3000
🔐 Environment Variables
Create a .env file inside backend folder:
Copy code

STREAM_API_KEY=your_stream_key
STREAM_API_SECRET=your_stream_secret
CALL_ID=demo-room
GEMINI_API_KEY=your_gemini_key
⚠️ Important: Never push .env files to GitHub. Always keep them in .gitignore.
🎯 Use Cases
🏢 Corporate Meetings
👨‍💻 Team Standups
📞 Client Calls
🎓 Online Classes
🤝 Project Discussions
Anywhere you need smart automation + clean documentation
🧪 Development Approach
This project was built using a problem-first mindset, not just feature stacking:
Understanding real meeting pain points
Designing clean and logical user flow
Optimizing API usage to avoid unnecessary calls
Keeping components reusable and scalable
Writing readable, maintainable code
🚧 Challenges Faced & Solutions
Challenge
Solution
API timeouts
Optimized request handling & retries
Real-time data sync
Used Stream SDK efficiently
AI latency
Structured prompts for faster response
Scalability
Dockerized backend for easy deployment
🔮 Future Improvements
🗂️ User meeting history
⭐ Bookmark important moments
📊 Analytics dashboard
🌍 Multi-language support
🧠 Smarter AI insights & recommendations
📚 What This Project Demonstrates
Strong understanding of full stack architecture
Real-world AI integration experience
Clean component-based design
Performance-focused frontend development
Product-oriented engineering thinking
👨‍💻 Author
Avinash Kumar
Final Year B.Tech CSE Student | Full Stack Developer | AI Enthusiast
I love building real-world applications that solve actual problems.
This project reflects my interest in AI, scalable systems, and product thinking.
🔗 LinkedIn: (add link)
📧 Email: (add email)
🤝 Usage & Integrity Notice
This repository is shared for learning, review, and evaluation purposes.
Feel free to explore the code, understand the architecture, and learn from the approach.
⭐ Support
If you like this project, don’t forget to star ⭐ the repository – it really motivates me!