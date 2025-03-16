# AI Career Coach - Full Stack Application

## 🚀 Overview

AI Career Coach is a full-stack web application built using **React 19, Next.js 15, Tailwind CSS, NeonDB, Prisma, Clerk Authentication, Inngest, Gemini API, and Shadcn UI**. This project serves as an intelligent career guide, helping users with resume evaluation, job suggestions, skill assessments, and AI-powered career advice.

This project is an excellent addition to your resume, showcasing your skills in full-stack development, authentication, database management, and AI integration.

## ✨ Features

- **User Authentication**: Secure login and signup using Clerk.
- **AI-Powered Career Guidance**: Utilizes Gemini API for intelligent career recommendations.
- **Job Suggestions**: Fetches and recommends job listings based on user skills and interests.
- **Resume Analysis**: AI-driven insights on how to improve resumes.
- **Skill Assessment**: Evaluates users' technical skills and suggests improvement areas.
- **Task Scheduling & Automation**: Powered by Inngest for efficient task management.
- **Modern UI**: Built using Shadcn UI and Tailwind CSS for a sleek and responsive interface.

## 🛠 Tech Stack

- **Frontend**: React 19, Next.js 15, Tailwind CSS
- **Backend**: Next.js API routes, Prisma ORM
- **Database**: NeonDB (PostgreSQL)
- **Authentication**: Clerk
- **AI Services**: Gemini API
- **Task Scheduling**: Inngest
- **UI Components**: Shadcn UI

## 📂 Project Structure

```
📦 ai-career-coach
├── 📂 src
│   ├── 📂 components    # Reusable UI components
│   ├── 📂 pages         # Next.js pages
│   ├── 📂 api          # Backend API routes
│   ├── 📂 utils        # Helper functions
│   ├── 📂 styles       # Global styles with Tailwind CSS
├── 📜 package.json     # Dependencies and scripts
├── 📜 prisma/schema.prisma  # Database schema
├── 📜 .env             # Environment variables
```

## 🏗️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/ai-career-coach.git
cd ai-career-coach
```

### 2️⃣ Install dependencies

```bash
yarn install  # or npm install
```

### 3️⃣ Set up environment variables

Create a `.env` file and configure the following variables:

```env
DATABASE_URL="your-neondb_url"
NEXT_PUBLIC_CLERK_FRONTEND_API="your-clerk-api-key"
CLERK_API_KEY="your-clerk-secret-key"
GEMINI_API_KEY="your-gemini-api-key"
INNGEST_API_KEY="your-inngest-api-key"
```

### 4️⃣ Migrate the database

```bash
npx prisma migrate dev --name init
```

### 5️⃣ Start the development server

```bash
yarn dev  # or npm run dev
```

The app will be running at `http://localhost:3000`

## 🎯 Future Enhancements

- Add AI-driven interview preparation.
- Implement user dashboards with career growth analytics.
- Integrate more job APIs for broader job listings.
- Support multiple languages for global accessibility.

## 🤝 Contributing

Contributions are welcome! If you’d like to improve this project, feel free to fork the repository and submit a pull request.

## 📜 License

This project is licensed under the **MIT License**.

---

🚀 **Star this repo** if you find it helpful! Happy coding! 😃

Abhishek Kumar

