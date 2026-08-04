### 👋 Hi, my name is Dmytro

🔭 Fullstack Web Developer, TS, JS, Next.js, Node.js

---

### 📫 Contacts:

[![Telegram](https://img.shields.io/badge/TELEGRAM-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/dima_mtv)
[![Gmail](https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dimadobrovolski@gmail.com)
[![CV](https://img.shields.io/badge/CV%20→%20RESUME-4285F4?style=for-the-badge&logo=vercel&logoColor=white)](https://resume-drab-three-79.vercel.app/)

---

### 🔧 Technologies & Tools

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
<br>
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square)
![CSS Modules](https://img.shields.io/badge/CSS%20Modules-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
<br>
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

### 🚀 Pet projects

<br>

### 🌌 NebulaX — Real-time Chat App

[![FE](https://img.shields.io/badge/FE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/NebulaX_FE)
[![BE](https://img.shields.io/badge/BE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/NebulaX_BE)
[![Live](https://img.shields.io/badge/LIVE%20DEMO-4285F4?style=flat-square&logo=vercel&logoColor=white)](https://nebulax-snowy.vercel.app/)

Real-time chat platform with public rooms, built on WebSockets (Socket.io) and Redis Pub/Sub for message fan-out across server instances. Chat history is paginated with TanStack Query's `useInfiniteQuery` and stays in sync with live socket events; auth uses JWT (httpOnly cookies) with Zustand for UI state. Includes a custom design system (IconBadge, IconButton, CardBadge) with CSS Modules and a persisted theme, styled around a cosmic/aurora "Liquid Glass" look. Backend: Express + TypeScript, Zod-validated REST endpoints, Swagger docs, Docker Compose for local services.

Test account: `test.acc@test.com` / `12345678`

<p>
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/nebulaX/rooms-list-dark.png" width="270" />
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/nebulaX/chat-room.png" width="270" />
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/nebulaX/room-card-hover.png" width="270" />
</p>

<br>

---

<br>

### 🩺 MediFlow — Full Stack CRM

[![FE](https://img.shields.io/badge/FE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/MediFlow_FE)
[![BE](https://img.shields.io/badge/BE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/MediFlow_BE)
[![Live](https://img.shields.io/badge/LIVE%20DEMO-4285F4?style=flat-square&logo=vercel&logoColor=white)](https://mediflowfe.vercel.app)

Full-stack doctor and appointment management system built end-to-end from schema to UI. Appointment slots are generated per-doctor from working hours and existing bookings, with filtering and search state stored in the URL for shareable views. JWT auth protects role-specific routes; an AI-powered (Gemini API) pipeline seeds realistic demo data for doctors, clinics, and appointments. Backend uses raw `pg` (no ORM) to deepen SQL understanding.

Test account: `demo@mediflow.com` / `Demo1234`

<p>
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/mediflow/dashboard.png" width="270" />
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/mediflow/doctors.png" width="270" />
  <img src="https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/mediflow/schedule-modal.png" width="270" />
</p>

<br>

---

<br>

### 🛍️ WarmHeart 2.0 — E-commerce

[![FE](https://img.shields.io/badge/FE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/WarmHeart_FE)
[![BE](https://img.shields.io/badge/BE-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/metwoOSha/WarmHeart_BE)
[![Live](https://img.shields.io/badge/LIVE%20DEMO-4285F4?style=flat-square&logo=vercel&logoColor=white)](https://warm-heart.vercel.app/)

Full-stack e-commerce storefront with JWT auth, a persistent server-synced cart, and paginated, filterable product listings. MVC backend (Express + Prisma) with a normalized PostgreSQL schema, deployed on Vercel with Neon serverless Postgres.

![WarmHeart home page](https://raw.githubusercontent.com/metwoOSha/metwoOSha/main/docs/warm-heart/home.png)

---

⭐ From [metwoOSha](https://github.com/metwoOSha)
