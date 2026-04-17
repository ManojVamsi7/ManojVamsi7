from pathlib import Path

readme = r"""# Hi, I'm Manoj Vamsi 👋

I'm an **AI/ML graduate** and **software developer** who enjoys building practical products across **web development, AI-powered tools, and data-driven applications**.

## About me

- 🌱 I like building projects that combine **clean UI**, **useful functionality**, and **real-world problem solving**
- 🤖 Interested in **AI/ML**, **full-stack development**, and **developer-focused products**
- 🚀 I enjoy turning ideas into deployable applications and polished user experiences

## Tech stack

**Languages**
- Python
- JavaScript
- TypeScript
- HTML
- CSS

**Frameworks & Tools**
- React
- Next.js
- Flask
- Tailwind CSS
- Firebase
- SQLite
- Git
- Vercel
- Render

## Featured projects

### [ResumeAI](https://github.com/ManojVamsi7/ResumeAi)
AI-powered resume analyzer that gives ATS-style feedback, skill gap insights, and improvement suggestions using **Flask**, **Groq / Llama 3.3**, **Firebase**, and **PDF parsing**.

### [NASA APOD Explorer](https://github.com/ManojVamsi7/NASA-APOD-Explorer)
A modern **Next.js + TypeScript** application to explore NASA's Astronomy Picture of the Day archive with date navigation, gallery browsing, caching, and a responsive UI.

### [Portfolio Website](https://github.com/ManojVamsi7/portfolio)
My personal portfolio built with **Next.js**, **React**, **TypeScript**, **Tailwind CSS**, and **Framer Motion** to showcase projects, skills, and experience.

### [CRM CLI Application](https://github.com/ManojVamsi7/Qbits-Internship-assessment)
A command-line CRM tool for lead management, payouts, and visualization using **Python**, **SQLite**, **Pandas**, and **Plotly**.

### [Weather App](https://github.com/ManojVamsi7/Weather-report)
A responsive weather application built with **HTML**, **CSS**, and **JavaScript** with city search and current-location support.

## Other projects

- [Drought-Prediction-](https://github.com/ManojVamsi7/Drought-Prediction-)
- [OGimageGenerator](https://github.com/ManojVamsi7/OGimageGenerator)
- [Zenith-Flow](https://github.com/ManojVamsi7/Zenith-Flow)
- [Training_portal](https://github.com/ManojVamsi7/Training_portal)
- [reminder-system](https://github.com/ManojVamsi7/reminder-system)
- [email_verification](https://github.com/ManojVamsi7/email_verification)
- [Weather Dashboard](https://github.com/ManojVamsi7/-Weather-Dahboard)
- [top-tracks-spotify.io](https://github.com/ManojVamsi7/top-tracks-spotify.io)
- [car_price](https://github.com/ManojVamsi7/car_price)

## What I'm working on

- Building AI-assisted applications
- Improving full-stack product development skills
- Creating polished, deployable portfolio projects
- Exploring data-driven solutions for real-world problems

## Connect with me

- GitHub: [@ManojVamsi7](https://github.com/ManojVamsi7)
- Portfolio: [manojvamsid.vercel.app](https://manojvamsid.vercel.app/)

---

_Thanks for visiting my profile._
"""

path = Path("/mnt/data/README_profile.md")
path.write_text(readme, encoding="utf-8")
print(f"Saved to {path}")
