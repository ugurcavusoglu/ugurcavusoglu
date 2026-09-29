# Hi there, I'm Ugur Mert Cavusoglu! 👋

<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=3F51B5&center=true&vCenter=true&width=600&lines=AI%2FML+Engineer;Computer+Vision+%26+Deep+Learning;Full-Stack+%26+Mobile+Developer;Shipping+Products%2C+Not+Just+Demos)
  
</div>

## 🚀 About Me

Computer Engineering student building intelligent systems and shipping real products. I work across the stack — from PyTorch computer-vision pipelines to production backends serving live mobile apps.

- 📱 Built and shipped **İYTE Mobile** — a full campus platform live on the **App Store** and **Google Play**
- 🔬 Deep into **Computer Vision** — segmentation, matting, tracking, and real-time on-device inference
- 🧠 Working with **PyTorch**, **OpenCV**, **MediaPipe**, and **transformer fine-tuning (DPO/alignment)**
- 🏗️ Comfortable owning a system end-to-end: API design, database, mobile client, deployment, security
- 📚 Currently exploring **Generative AI**, **model optimization**, and **MLOps**

---

## 🌟 Featured Project — İYTE Mobile

<div align="center">

### 📱 A complete campus life platform, built solo and shipped to production

[![App Store](https://img.shields.io/badge/App_Store-Download-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/tr/app/i-yte-mobile/id6761460550)
[![Google Play](https://img.shields.io/badge/Google_Play-Download-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.iytemobil.app)
[![Website](https://img.shields.io/badge/iytemobil.com-Visit-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://iytemobil.com)

</div>

> Backend, mobile app, admin panel, scrapers, website, infrastructure and deployment.
> A 6-repository system serving İzmir Institute of Technology students, live on both app stores.

<div align="center">

| 📊 Scale | |
|:---|:---|
| **Solo** build, live on both stores | **8** iOS releases in ~10 weeks |
| **424** REST API endpoints | **60** database models |
| **34** backend modules | **69** mobile screens |

</div>

### 🏛️ System Architecture

```
                    ┌──────────────────────────────┐
                    │   React Native Mobile App    │  ← iOS + Android (Expo/EAS)
                    │      69 screens · FCM push   │
                    └───────────────┬──────────────┘
                                    │
   ┌──────────────┐   ┌─────────────▼──────────────┐   ┌──────────────────┐
   │ Admin Panel  │──▶│      NestJS REST API       │◀──│  Python Scrapers │
   │ React + Vite │   │  424 endpoints · 34 modules │   │  Async · Docker  │
   └──────────────┘   │   JWT · CSRF · Socket.IO    │   └──────────────────┘
                      └──┬────────┬────────┬─────┬──┘
   ┌──────────────┐      │        │        │     │
   │   Website    │──────┘        │        │     │
   │   Next.js    │               │        │     │
   └──────────────┘         ┌─────▼──┐ ┌───▼───┐ ┌▼──────┐
                            │Postgres│ │MongoDB│ │ Redis │
                            │ Prisma │ │ Chat  │ │ Cache │
                            └────────┘ └───────┘ └───────┘

        🛡️  Nginx reverse proxy · Suricata IDS · Wazuh SIEM · Rate limiting
```

### ⚙️ What's Inside

<table>
  <tr>
    <td width="50%" valign="top">

**📱 Mobile App** — React Native + Expo, TypeScript
- Social feed: posts, likes, comments, polls, confessions
- Real-time chat over Socket.IO
- Clubs, events & RSVP system
- Carpool matching between students
- Campus food menus & restaurant campaigns
- Bus schedules & transport info
- Department documents & job listings
- Gamification: badges & leaderboards
- Push notifications via Firebase FCM
- Guest mode for browsing without an account

  </td>
    <td width="50%" valign="top">

**⚡ Backend API** — NestJS, TypeScript
- 424 endpoints across 34 feature modules
- Dual database: PostgreSQL (Prisma) + MongoDB (chat)
- Redis caching & job queues
- JWT auth with CSRF protection
- Socket.IO real-time gateway
- Swagger/OpenAPI documentation
- Winston structured logging & audit trails

**🛡️ Infrastructure & Security**
- Nginx reverse proxy with per-IP rate limiting
- Suricata IDS — SQLi, XSS & port-scan detection
- Wazuh SIEM for centralized monitoring
- Helmet.js security headers, CORS policies
- Dockerized deployment on Ubuntu

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

**🖥️ Admin Panel** — React 18 + Vite
- User management, moderation & bans
- Club approval workflow
- Event and content management
- Report handling & analytics dashboard
- Zustand + TanStack Query + Radix UI

  </td>
    <td width="50%" valign="top">

**🐍 Data Scrapers** — Python 3.11
- Async scraping with httpx + BeautifulSoup
- Scheduled jobs via APScheduler
- Bus schedules, KYK & cafeteria menus
- Containerized, runs autonomously

**🌐 Website** — [Next.js](https://github.com/ugurcavusoglu/iytemobil_website) *(public repo)*
- Bilingual (TR/EN) landing site
- Integrated club application flow

  </td>
  </tr>
</table>

### 🧰 Tech Stack Used

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![React Native](https://img.shields.io/badge/-React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/-Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## 💼 Other Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">🎨 Phixora</h3>
      <p align="center">
        <a href="https://github.com/ugurcavusoglu/phixora">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=ugurcavusoglu&repo=phixora&theme=tokyonight" />
        </a>
      </p>
      <p align="center">AI image editing platform — super-resolution, denoising & background removal.<br/>React + NestJS + Prisma + PostgreSQL</p>
    </td>
    <td width="50%">
      <h3 align="center">🥤 SmartJuice</h3>
      <p align="center">
        <a href="https://github.com/ugurcavusoglu/smartjuice-app">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=ugurcavusoglu&repo=smartjuice-app&theme=tokyonight" />
        </a>
      </p>
      <p align="center">Flutter app for a smart juice device — custom physics engine for fruit collision animation, vitamin tracking, BLE device states.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">📝 NLP Model Benchmark</h3>
      <p align="center">
        <a href="https://github.com/ugurcavusoglu/NLP_Midterm">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=ugurcavusoglu&repo=NLP_Midterm&theme=tokyonight" />
        </a>
      </p>
      <p align="center">Classical, recurrent and transformer models compared on five NLP tasks, including BERT fine-tuning for sentiment and NER.</p>
    </td>
    <td width="50%">
      <h3 align="center">🎯 LLM Alignment with DPO</h3>
      <p align="center">
        <a href="https://github.com/ugurcavusoglu/Alignment-via-DPO">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=ugurcavusoglu&repo=Alignment-via-DPO&theme=tokyonight" />
        </a>
      </p>
      <p align="center">Aligning TinyLlama-1.1B with SFT and DPO using LoRA on HH-RLHF preference data. CENG467.</p>
    </td>
  </tr>
</table>

### 🔒 Selected Private Work

Projects I can't open-source, but happy to talk about:

- **🎭 Real-time avatar at HubX (ML Engineer Intern)** — Android (Kotlin) and iOS (Swift) libraries for a real-time photorealistic avatar, an on-device facial-expression model built from scratch in PyTorch and exported to Core ML, lip-sync model fine-tuning, and image/video processing pipelines with segmentation and matting models.
- **🤖 Multi-Agent Software Delivery System** — An orchestrator on Claude Code routes GitHub issues to role agents that open pull requests, merged only after agent review and green CI, with fail-closed guard hooks.
- **🔥 Hybrid Fire Detection** — YCbCr + RGB color-space analysis with morphological post-processing, based on Celik et al.
- **👁️ Retinal Blood Vessel Extraction** — Hybrid supervised + unsupervised approach using Gabor filters, Top-Hat / Bit-Plane Slicing features, FCM clustering and decision trees. Evaluated on DRIVE, STARE and CHASE_DB1.
- **👥 Automated People Counting** — Full reproduction of a crowd-density estimation paper: foreground extraction and feature-based counting at mass sites with OpenCV.
- **⚽ Moving Object Detection & Tracking** — Background subtraction + contour analysis, logging positions frame-by-frame and plotting trajectories.
- **💭 Sentiment Radar** — Full-stack Turkish sentiment analysis platform. React + FastAPI + PostgreSQL + Hugging Face, containerized with Docker Compose.
- **🌡️ Legion Fan Control** — Open-source-style C# desktop app for Lenovo Legion laptops: fan curves, thermal modes and live CPU/GPU monitoring.
- **📊 ML Experiment Tracker** — MLOps-style experiment tracking system for organizing training runs and metrics.

---

## 🛠️ Tech Stack

### 🧠 AI / ML & Computer Vision
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 💻 Backend & Databases
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

### 📱 Frontend & Mobile
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/-React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🔧 DevOps & Tools
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📊 GitHub Statistics

<div align="center">
  
  ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ugurcavusoglu&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
  
  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ugurcavusoglu&layout=compact&theme=tokyonight&hide_border=true&count_private=true)
  
  ![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ugurcavusoglu&theme=tokyonight&hide_border=true)

</div>

---

## 🎯 What I'm Focused On

- 🚀 Growing **İYTE Mobile** — new features, performance, and scaling for more users
- 🔬 Real-time **computer vision on mobile** — on-device inference, model optimization, quantization
- 🧠 **Generative AI** — diffusion models, video synthesis, and controllable generation
- ⚙️ **MLOps** — taking models from notebook to production properly

---

## 📫 Let's Connect!

<div align="center">
  
  [![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cavusogluugurmert@gmail.com)
  [![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ugurcavusoglu)
  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ugurmertcavusoglu)
  
</div>

---

<div align="center">
  
  ### 💡 "The only way to do great work is to love what you do." - Steve Jobs
  
  ![Profile Views](https://komarev.com/ghpvc/?username=ugurcavusoglu&color=blueviolet&style=for-the-badge)
  
  ⭐️ From [ugurcavusoglu](https://github.com/ugurcavusoglu) with ❤️
  
</div>
