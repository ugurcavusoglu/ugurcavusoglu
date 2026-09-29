<div align="center">

# Uğur Mert Çavuşoğlu

**On-Device ML · Computer Vision · Mobile**

Computer Engineering @ Izmir Institute of Technology · Izmir, Turkey

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ugurmertcavusoglu-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ugurmertcavusoglu)
[![Email](https://img.shields.io/badge/Email-cavusogluugurmert%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:cavusogluugurmert@gmail.com)

</div>

---

### About me

I build machine learning models that run in real time on phones, and the Android and iOS code around them. I have built models in PyTorch and exported them to Core ML for the Apple Neural Engine, fine-tuned language models with LoRA and DPO, and built and shipped a campus app on my own that is live on the App Store and Google Play.

- 🧠 **On-device inference**: PyTorch models exported to Core ML and ONNX, running in real time on iOS and Android
- 👁️ **Computer vision**: segmentation, matting and image/video processing pipelines
- 🎯 **Model fine-tuning**: LoRA, SFT and DPO with Hugging Face TRL and PEFT
- 📱 **Mobile engineering**: Kotlin (OpenGL ES, MediaCodec), Swift (Metal, AVFoundation), React Native

---

### 💼 Experience

**Machine Learning Engineer Intern, Device Lab · HubX** · *Jul 2026 – Sep 2026*

- Built the Android (Kotlin) and iOS (Swift) libraries for a real-time photorealistic avatar, running at 30 fps on device
- Designed and built an on-device facial-expression model from scratch in PyTorch, with its training pipeline and Core ML export; it runs in real time on the Apple Neural Engine
- Built image and video processing pipelines with segmentation and matting models (SAM 3, ViTMatte), and fine-tuned a lip-sync model

---

### 🌟 Featured project: İYTE Mobil

<div align="center">

**A campus platform for Izmir Institute of Technology students, built solo and live on both app stores**

[![App Store](https://img.shields.io/badge/App_Store-Download-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/tr/app/i-yte-mobile/id6761460550)
[![Google Play](https://img.shields.io/badge/Google_Play-Download-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.iytemobil.app)
[![Website](https://img.shields.io/badge/iytemobil.com-Visit-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://iytemobil.com)

| 📱 69 mobile screens | 🔌 424 REST endpoints | 🗄️ 60 database models | 🧩 34 backend modules |
|:---:|:---:|:---:|:---:|

</div>

```
                    ┌──────────────────────────────┐
                    │   React Native Mobile App    │  ← iOS + Android (Expo)
                    │     69 screens · FCM push    │
                    └───────────────┬──────────────┘
                                    │
   ┌──────────────┐   ┌─────────────▼──────────────┐   ┌──────────────────┐
   │ Admin Panel  │──▶│      NestJS REST API       │◀──│  Python Scrapers │
   │    React     │   │ 424 endpoints · 34 modules │   │      Docker      │
   └──────────────┘   │  JWT · CSRF · Socket.IO    │   └──────────────────┘
                      └──┬────────┬────────┬───────┘
   ┌──────────────┐      │        │        │
   │   Website    │──────┘        │        │
   │   Next.js    │         ┌─────▼──┐ ┌───▼───┐ ┌───────┐
   └──────────────┘         │Postgres│ │MongoDB│ │ Redis │
                            │ Prisma │ │ Chat  │ │BullMQ │
                            └────────┘ └───────┘ └───────┘
```

- **Mobile app:** social feed, real-time chat, clubs and events, carpooling, cafeteria menus, bus times, push notifications
- **Backend:** NestJS + TypeScript, PostgreSQL (Prisma), MongoDB, Redis/BullMQ queues, Socket.IO, JWT + CSRF auth
- **Also:** React admin panel, Dockerized Python scrapers, Next.js website ([source](https://github.com/ugurcavusoglu/iytemobil_website))

---

### 🧪 Other projects

| Project | What it is |
|:--|:--|
| **Multi-agent software delivery system** *(private for now)* | An orchestrator on Claude Code routes GitHub issues to role agents that open pull requests, which merge only after agent review and green CI; fail-closed hook guards block destructive commands and secret exposure |
| [**Alignment-via-DPO**](https://github.com/ugurcavusoglu/Alignment-via-DPO) | Aligning TinyLlama-1.1B with SFT and DPO using LoRA on the HH-RLHF preference data |
| [**NLP_Midterm**](https://github.com/ugurcavusoglu/NLP_Midterm) | Classical, recurrent and transformer models compared on five NLP tasks, including BERT fine-tuning |
| [**phixora**](https://github.com/ugurcavusoglu/phixora) | Web image editor with AI super-resolution, denoising and background removal |
| [**smartjuice-app**](https://github.com/ugurcavusoglu/smartjuice-app) | Flutter app for a smart juice maker, with a custom physics animation |

---

### 🛠️ Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Core ML](https://img.shields.io/badge/Core_ML-000000?style=flat-square&logo=apple&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Metal](https://img.shields.io/badge/Metal-000000?style=flat-square&logo=apple&logoColor=white)
![OpenGL ES](https://img.shields.io/badge/OpenGL_ES-5586A4?style=flat-square&logo=opengl&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>
