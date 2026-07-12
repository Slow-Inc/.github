<div align="center">

# T4 Labs

**พัฒนาซอฟต์แวร์และระบบจัดการดิจิทัลสำหรับชุมชนออนไลน์**
*Software & digital management systems for online communities*

[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gcuBuXmCpr)
[![Website](https://img.shields.io/badge/Website-Visit-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://planet-eight-inky.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Slow--Inc-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Slow-Inc)

</div>

---

## เกี่ยวกับเรา

**T4 Labs** เป็นทีมนักพัฒนาที่สร้างซอฟต์แวร์ตั้งแต่เครื่องมือสำหรับชุมชนออนไลน์ไปจนถึงแพลตฟอร์มเว็บสเกลใหญ่ที่มี AI/ML pipeline ของตัวเอง ครอบคลุมทั้ง Discord Bot, FiveM Scripts & Resources, Website/Web Application และระบบ Machine Learning

**สิ่งที่เรามุ่งเน้น:**
- แพลตฟอร์มเว็บแบบ Full-Stack ที่ออกแบบให้สเกลได้ (Next.js/React + NestJS + microservices)
- ระบบจัดการที่ใช้งานง่ายและมีประสิทธิภาพ สำหรับชุมชน Roleplay และ Community Server
- FiveM Server Scripts และ Resources ที่ปรับแต่งได้ตามความต้องการ
- บริการที่รองรับการใช้งานระยะยาว พร้อม Support อย่างต่อเนื่อง

---

## ทีมพัฒนา

| สมาชิก | บทบาท |
|---|---|
| [Slowgers](https://github.com/Slowgers) | Lead Developer & System Architect |
| _InI4 | Vice Leader & Tester |
| [xenodev](https://github.com/xenodeve) | Full-Stack Developer & Bot Specialist |
| [akkanop-x](https://github.com/akkanop-x) | Full-Stack Developer & Cyber Security |
| [Thanathorn'Z](https://github.com/ThanathornZDev) | Backend Developer & Game Developer |
| [Paradise](https://github.com/CableMoMo2027) | Frontend Developer & Mobile Developer |

---

## โปรเจกต์เด่น

### 📖 MangaDock — แพลตฟอร์มอ่านมังงะพร้อมระบบแปลด้วย AI

โปรเจกต์ที่ซับซ้อนและสเกลใหญ่ที่สุดของทีม ([github.com/Slow-Inc/MangaDock](https://github.com/Slow-Inc/MangaDock)) — เว็บอ่านมังงะที่มี ML pipeline แปลภาพในตัวเอง แยกเป็น 3 services ที่ทำงานร่วมกัน พร้อม Docs portal ที่จำลอง data flow แบบ interactive

- **Frontend** — Next.js 16 + React 19, Supabase Auth, Tailwind CSS 4
- **Backend** — NestJS orchestration layer, multi-layer cache (Redis + on-disk L3), S3-compatible storage, Supabase (Auth + DB)
- **MIT (Manga Image Translator)** — Python/PyTorch microservice: YOLOv8 text detection, diffusion-based inpainting (Flux Klein GGUF), manga-ocr, DenseCRF mask refinement และ line-breaking ที่รองรับหลายภาษา (ไทย/จีน/ญี่ปุ่น)
- **Docs Portal** — เอกสารระบบแบบ interactive พร้อม live GitHub integration สำหรับ onboarding ทีม

**สเกล:** ~1,000 tracked files · โค้ด TypeScript/Python รวมกว่า 100,000 บรรทัด · ครอบคลุมทดสอบด้วย Playwright E2E

**Stack:** Next.js · React · NestJS · Supabase · Redis · PyTorch · FastAPI · Docker

---

### 🤖 Planet City Discord Bot

ระบบจัดการเซิร์ฟเวอร์ FiveM แบบครบวงจร พัฒนาด้วย Discord.js v14 รองรับตั้งแต่การรับสมัครสมาชิกไปจนถึงการดูแลชุมชนแบบอัตโนมัติ

- **Whitelist System** — จัดการคำขอเข้าร่วมเซิร์ฟเวอร์แบบอัตโนมัติ
- **QR Code Verification** — ตรวจสอบหลักฐานการบริจาคด้วย Tesseract.js OCR
- **Dynamic Forms** — สร้างและจัดการฟอร์มผ่าน Discord Interactions
- **Donation Tracking** — ระบบบริจาคพร้อมการตรวจสอบหลักฐานโปร่งใส
- **Rules & Support Desk** — แสดงกฎระเบียบและระบบติดต่อ/รายงานปัญหาในตัว
- **Audit Logging** — บันทึกกิจกรรมทั้งหมดด้วย Winston Logger

**Stack:** Node.js · TypeScript · Discord.js v14 · Tesseract.js · Sharp/Jimp · Winston · Axios

---

## บริการของเรา

### Discord Bot Development
พัฒนา Discord Bot ตามความต้องการ (TypeScript/JavaScript & Python) ครอบคลุมระบบ Moderation, Integration กับ API ภายนอก และ OCR/Image Processing

### FiveM Lua Development
พัฒนา Scripts และ Resources บนเฟรมเวิร์ก ESX สำหรับ Roleplay Server ครอบคลุม Vehicle Systems, Property Management, Job & Economy, Police/Government, Medical Systems, Phone & Communication รวมถึง Custom NUI และ Server Optimization

### Website & Web Application
พัฒนาเว็บไซต์และเว็บแอปพลิเคชันด้วย Next.js/React + TypeScript + TailwindCSS + NestJS ครอบคลุม CMS, Dashboard/Analytics, User Management, Discord Bot Integration และ Responsive Web Design

### AI/ML Engineering
พัฒนาระบบ Machine Learning สำหรับ production เช่น Computer Vision pipeline (object detection, image inpainting), OCR และ multilingual NLP — ดูตัวอย่างจริงใน [MangaDock](https://github.com/Slow-Inc/MangaDock)

### Game Server Management
เครื่องมือจัดการเซิร์ฟเวอร์เกม ตั้งแต่ Whitelist & Player Management, Server Monitoring, Community Management Tools ไปจนถึง Custom Plugin Development

---

## เทคโนโลยีที่เราใช้

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Discord.js](https://img.shields.io/badge/Discord.js-5865F2?style=flat-square&logo=discord&logoColor=white)
![Discord.py](https://img.shields.io/badge/Discord.py-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![ESX](https://img.shields.io/badge/ESX-FF6B35?style=flat-square&logo=fivem&logoColor=white)

**Databases & Infrastructure**
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## ชุมชนและการติดต่อ

เข้าร่วมชุมชน **Planet City** เพื่อดูตัวอย่างการใช้งานจริง สอบถามบริการ หรือแจ้งปัญหา — มี Support ผ่าน Discord ตลอด 24/7

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gcuBuXmCpr)

| ช่องทาง | ลิงก์ |
|---|---|
| Discord Community | [discord.gg/gcuBuXmCpr](https://discord.gg/gcuBuXmCpr) |
| Website | [planet-eight-inky.vercel.app](https://planet-eight-inky.vercel.app/) |
| Documentation | [Planet City Tutorials](https://sites.google.com/view/planetcity/tutorials) |
| GitHub Organization | [github.com/Slow-Inc](https://github.com/Slow-Inc) |

---

<div align="center">

© 2024–2026 **Slow Inc**. All rights reserved.

</div>
