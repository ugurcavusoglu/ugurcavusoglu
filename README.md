# Uğur Mert Çavuşoğlu

**On-device ML · Computer Vision · Mobile**

Computer Engineering student at Izmir Institute of Technology (B.S., expected Jun 2027) · Izmir, Turkey

I build machine learning models that run in real time on phones, and the Android and iOS code around them. I have built models in PyTorch and exported them to Core ML for the Apple Neural Engine, fine-tuned language models with LoRA and DPO, and built and shipped a campus app on my own that is live on the App Store and Google Play.

## What I work on

- **On-device inference**: PyTorch models exported to Core ML and ONNX, running in real time on iOS and Android
- **Computer vision**: segmentation, matting and image/video processing pipelines
- **Model fine-tuning**: LoRA, SFT and DPO with Hugging Face TRL and PEFT
- **Mobile engineering**: Kotlin (OpenGL ES, MediaCodec), Swift (Metal, AVFoundation), React Native

## Experience

**Machine Learning Engineer Intern, Device Lab · HubX** (Jul 2026 – Sep 2026)

- Built the Android (Kotlin) and iOS (Swift) libraries for a real-time photorealistic avatar, running at 30 fps on device
- Designed and built an on-device facial-expression model from scratch in PyTorch, with its training pipeline and Core ML export; it runs in real time on the Apple Neural Engine
- Built image and video processing pipelines with segmentation and matting models (SAM 3, ViTMatte), and fine-tuned a lip-sync model

## Featured project: IYTE Mobil

A campus platform for Izmir Institute of Technology students, which I founded and built solo (Dec 2025 – Jul 2026).

[App Store](https://apps.apple.com/tr/app/i-yte-mobile/id6761460550) · [Google Play](https://play.google.com/store/apps/details?id=com.iytemobil.app) · [iytemobil.com](https://iytemobil.com) · [Website source](https://github.com/ugurcavusoglu/iytemobil_website)

- **Mobile app** (React Native, Expo): 69 screens with a social feed, real-time chat, clubs and events, carpooling, cafeteria menus, bus times and Firebase push notifications
- **API** (NestJS, TypeScript): 424 REST endpoints across 34 modules, 60 Prisma models on PostgreSQL, plus MongoDB, Redis/BullMQ queues, a Socket.IO gateway and JWT + CSRF auth
- **Also**: a React admin panel, Dockerized Python scrapers and a Next.js website
- 8 iOS releases in about 10 weeks

```
React Native app      React admin      Next.js        Python
 (iOS + Android)         panel          website       scrapers
        \                  |               |             /
         +------- NestJS REST API + Socket.IO gateway --+
                  /              |               \
           PostgreSQL         MongoDB        Redis / BullMQ
            (Prisma)          (chat)           (queues)
```

## Other projects

- **Multi-agent software delivery system** (private for now): an orchestrator on Claude Code routes GitHub issues to role agents, which open pull requests that merge only after agent review and green CI. Hook scripts block destructive commands, secret exposure and edits to guardrail files, and fail closed.
- **Course projects** (Izmir Institute of Technology):
  - [Alignment-via-DPO](https://github.com/ugurcavusoglu/Alignment-via-DPO): aligning TinyLlama-1.1B with SFT and DPO using LoRA on the HH-RLHF preference data
  - [NLP_Midterm](https://github.com/ugurcavusoglu/NLP_Midterm): classical, recurrent and transformer models compared on five NLP tasks, including DistilBERT sentiment analysis and BERT named entity recognition
  - [smartjuice-app](https://github.com/ugurcavusoglu/smartjuice-app): Flutter app for a smart juice maker, with a custom physics animation and device-state flow
- [phixora](https://github.com/ugurcavusoglu/phixora): web image editor with AI super-resolution, denoising and background removal (React, NestJS, Prisma, PostgreSQL)

## Tech stack

| Area | Tools |
|:--|:--|
| Languages | Python, TypeScript, Kotlin, Swift, JavaScript, GLSL |
| ML & vision | PyTorch, Hugging Face Transformers, TRL / PEFT (LoRA), Core ML, ONNX, OpenCV, MediaPipe, scikit-learn |
| Mobile | Android (OpenGL ES 3.0, MediaCodec), iOS (Metal, AVFoundation), React Native, Expo, Firebase |
| Backend & web | NestJS, PostgreSQL, Prisma, MongoDB, Redis, Socket.IO, React, Next.js |
| Tools | Git, Docker, GitHub Actions, Claude Code, Azure DevOps, GitLab |

## Contact

[cavusogluugurmert@gmail.com](mailto:cavusogluugurmert@gmail.com) · [LinkedIn](https://linkedin.com/in/ugurmertcavusoglu)
