:

🚀 AI Resume Analyzer & Job Matcher

An AI-powered web app built with Next.js, Supabase, and NLP that analyzes resumes and compares them with job descriptions to calculate a match score.

✨ Features

📂 Upload resume (PDF/DOCX)

📝 Paste job description

🤖 AI calculates match percentage using TF-IDF & Cosine Similarity

🔍 Highlights missing keywords & skills

📊 Interactive dashboard with analytics

🔐 User authentication via Supabase

🛠️ Tech Stack

Frontend: Next.js 14, React, TailwindCSS, Shadcn/UI

Backend: Supabase (Auth + Database)

NLP: Python/JS-based TF-IDF similarity

Deployment: Vercel

🚀 Getting Started
# Install dependencies
npm install

# Start development server
npm run dev


App will be live at: http://localhost:3000

🔑 Environment Variables

Create a .env.local file in the root folder and add:

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key

📜 License

MIT License
