🚀 AI Career Mentor
Turning career confusion into confidence with a personalized AI-powered interview coach.

An AI-powered platform designed to help students prepare for job interviews by providing personalized mock interviews and actionable feedback.

🎯 The Problem
Every year, millions of students graduate with technical skills but face a significant challenge: career confusion and interview anxiety. They often lack the confidence to present their abilities effectively in a high-pressure environment. There's a critical absence of personalized guidance to help them identify and improve their weaknesses. This "guidance gap" results in many talented students missing out on deserving opportunities.

✨ Our Solution
The AI Career Mentor is an intelligent platform that acts as a 24/7 personal career coach for every student. Our platform provides a safe, risk-free environment where students can practice for real-world interviews and receive instant, actionable feedback on their performance, helping them build the confidence they need to succeed.

🔥 Key Features
📝 Resume-Based Analysis: The AI analyzes a student's resume and target job role to generate a highly relevant, customized interview.

🎙️ Realistic Mock Interviews: A clean and intuitive interface that simulates a real remote interview experience, helping students get comfortable with the format.

🧠 Instant AI-Powered Feedback: Immediately after the interview, the AI provides a detailed analysis of each answer, an overall performance score, and concrete suggestions for improvement.

🔒 Secure & Publicly Accessible: All user data for creators is fully secure. Interview links are publicly accessible, allowing any candidate to take an interview without needing to sign up or log in.

👤 User-Friendly Dashboard: Authenticated users have a personal dashboard to create, track, and manage all of their mock interviews.

🛠️ Tech Stack
This platform was built using a modern, scalable, and high-performance tech stack:

Frontend: Next.js (React) & Tailwind CSS

Backend & Database: Supabase (Authentication, PostgreSQL, Storage)

AI Framework: LangChain (for orchestrating AI operations and prompts)

Core AI Model: Groq API (for blazing-fast text generation and analysis)

Deployment: Vercel

⚙️ Setup and Installation
To run this project on your local machine, please follow these steps:

1. Clone the repository:

git clone [https://github.com/coderirfannn/AI-Career.git](https://github.com/coderirfannn/AI-Career.git)
cd ai-career-mentor

2. Install dependencies:

npm install
# or
yarn install

3. Set up environment variables:
Create a .env.local file in the root directory and add your Supabase and Groq API keys. You can use the .env.example file as a template.

# Supabase
NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY

# Groq AI
GROQ_API_KEY=YOUR_GROQ_API_KEY

4. Run the development server:

npm run dev
