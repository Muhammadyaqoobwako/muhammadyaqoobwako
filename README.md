<!-- ===================== PROFILE BANNER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0f2c,100:0f172a&height=220&section=header&text=Muhammad%20Yaqoob&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<h3 align="center">Full Stack Developer • Backend & AI Focused</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&center=true&vCenter=true&width=650&lines=Software+Engineering+Student+(7th+Semester);Building+Scalable+Backend+Systems;AI-Powered+Web+Applications;MERN+Stack+Developer" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/muhammadyaqoob0">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:muhammadyaqoobwako@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Muhammadyaqoobwako">
    <img src="https://img.shields.io/badge/GitHub-000?style=flat&logo=github&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

I’m a **Full Stack Developer** and **Software Engineering student (7th Semester)** at  
**Mohammad Ali Jinnah University, Karachi**.

I specialize in **backend development**, **REST APIs**, and **AI-powered applications**,  
with a focus on **clean architecture, scalability, and production readiness**.

---

## 🚀 Featured Projects (Animated Cards)

<p align="center">
  <a href="https://interview-prep-frontend-five.vercel.app">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Muhammadyaqoobwako&repo=interview-prep-ai&theme=github_dark" />
  </a>
  <a href="https://github.com/Muhammadyaqoobwako">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Muhammadyaqoobwako&repo=lapbazaar&theme=github_dark" />
  </a>
</p>

### 🧠 INTERVIEW PREP AI
- AI-powered interview preparation platform using **Google Gemini AI**
- Built with **React, Node.js, Express, MongoDB**
- Secure authentication with **JWT**
- Deployed on **Vercel & Railway**

---

## 🛠 Tech Stack

**Frontend:** React · Vite · CSS · Framer Motion  
**Backend:** Node.js · Express · REST APIs · JWT  
**Database:** MongoDB · SQL Server  
**Tools & Cloud:** Git · GitHub · Postman · Docker · Vercel · Railway  
**Languages:** JavaScript · C++ · C# · Java · Python (Basics)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=muhammadyaqoobwako&show_icons=true&theme=github_dark" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadyaqoobwako&layout=compact&theme=github_dark" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=muhammadyaqoobwako&theme=github-dark"/>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Muhammadyaqoobwako/Muhammadyaqoobwako/output/github-contribution-grid-snake.svg" />
</p>

---

## 📫 Contact

- 📧 Email: **muhammadyaqoobwako@gmail.com**  
- 🔗 LinkedIn: https://linkedin.com/in/muhammadyaqoob0  

⭐ Open to **internships, junior roles & collaboration**

---

<!-- ===================== PORTFOLIO HERO SECTION ===================== -->
```jsx
import React from "react";
import { motion } from "framer-motion";

export default function Hero() {
  return (
    <section className="min-h-screen flex items-center justify-center bg-[#0f172a] text-white">
      <div className="text-center max-w-3xl px-6">
        <motion.h1
          initial={{ opacity: 0, y: 30 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.8 }}
          className="text-4xl md:text-6xl font-bold"
        >
          Muhammad Yaqoob
        </motion.h1>

        <motion.p
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          transition={{ delay: 0.3 }}
          className="mt-4 text-lg text-gray-300"
        >
          Full Stack Developer • Backend & AI Focused
        </motion.p>

        <motion.div
          initial={{ opacity: 0, y: 20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.6 }}
          className="mt-8 flex justify-center gap-4"
        >
          <a href="#projects" className="px-6 py-3 bg-blue-600 rounded-lg">
            View Projects
          </a>
          <a href="#contact" className="px-6 py-3 border border-gray-400 rounded-lg">
            Contact Me
          </a>
        </motion.div>
      </div>
    </section>
  );
}
