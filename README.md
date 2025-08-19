# 🚀 Learn-it : AI Powered Career Guide  

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat&logo=next.js)](https://nextjs.org/)  
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-blue?style=flat&logo=tailwind-css)](https://tailwindcss.com/)  
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat&logo=prisma)](https://www.prisma.io/)  
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=flat&logo=postgresql)](https://www.postgresql.org/)  
[![Clerk](https://img.shields.io/badge/Auth-Clerk-orange?style=flat&logo=clerk)](https://clerk.com/)  
[![Gemini AI](https://img.shields.io/badge/AI-Gemini-green?style=flat&logo=google)](https://ai.google/)  

> **Learn-it** is a full-stack AI-powered career guide platform that helps users with **resume building, interview preparation, and personalized career insights** using **Gemini AI**, modern web stack, and a beautiful UI.  

---

## ✨ Features  

- 🔐 **User Authentication**: Secure login & signup with **Clerk** (Google/email-based).  
- 📊 **Career Dashboard**: Interactive dashboard with **in-demand skills, salary trends, and market insights** (auto-updated via cron jobs).  
- 📝 **AI Resume Builder**: Generate **ATS-friendly resumes** using **Gemini AI**, fully customizable & downloadable.  
- 💼 **AI Cover Letter Generator**: Create tailored cover letters from job descriptions.  
- 🎤 **Mock Interview Simulator**: Role-specific interview questions with performance tracking & AI feedback.  
- 🌙 **Modern UI/UX**: Responsive design with **Next.js, Tailwind CSS, and Shadcn UI** (dark mode supported).  

---

## 🛠️ Tech Stack  

**Frontend:** Next.js, React, Tailwind CSS, Shadcn UI  
**Backend & Database:** Prisma ORM, PostgreSQL, Inngest (for background jobs)  
**Authentication:** Clerk  
**AI Integration:** Gemini AI (resume, cover letter, interview)  
**Other Tools:** Recharts (data visualization), Cron Jobs (weekly updates)  

---

## 🚀 Getting Started  

Follow these steps to run **Learn-it** locally:  

### 1️⃣ Clone the Repository  
```
bash
git clone https://github.com/your-username/learn-it.git
cd learn-it
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env.local` file in the root folder and add the following:

```env
DATABASE_URL=your_postgres_connection_url
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret
GEMINI_API_KEY=your_gemini_api_key
```

### 4️⃣ Run the Development Server

```bash
npm run dev
```

App will be live at **[http://localhost:3000](http://localhost:3000)** 🎉

---

## 🌟 Future Enhancements

* 📈 Personalized **career roadmap suggestions**.
* 🤖 More **AI-powered career tools** (mock group discussions, coding interviews).
* 📱 Mobile app integration with React Native.

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create your feature branch (`git checkout -b feature/awesome-feature`)
* Commit changes (`git commit -m 'Added awesome feature'`)
* Push branch (`git push origin feature/awesome-feature`)
* Open a Pull Request 🚀

---



