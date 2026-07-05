# Hi, I'm Ali Bagdatli 👋

Full-Stack & Mobile Developer | React Native · Expo · Node.js · DevOps  
📍 Germany &nbsp;·&nbsp; 💼 [Upwork](https://www.upwork.com/freelancers/~01823d02b62880312c?mp_source=share) &nbsp;·&nbsp; ✉️ alibagdat@hotmail.com

---

## 🚀 Featured Projects

---

### 📺 Oxi+ Platform — Full IPTV Ecosystem

A complete, production-grade IPTV platform built from scratch: cross-platform player apps, a reseller management panel, and a robust API backend.

---

#### <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16"/> Oxi+ Player App  
**Repository:** [`oxi-player-plus`](https://github.com/AliBag-de/oxi-player-plus) &nbsp;·&nbsp; [`oxiplus`](https://github.com/AliBag-de/oxiplus)

Cross-platform IPTV client built on the **React Native TV fork** (`react-native-tvos`). Runs on **Android TV**, **Apple TV**, **iOS**, **Android** and **Web** from a single codebase.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native (TV fork — `react-native-tvos`)
- <img src="https://img.icons8.com/color/48/000000/expo.png" width="16" height="16" alt="Expo"/> Expo SDK 55 · EAS Build · Expo Router (file-based routing)
- <img src="https://img.icons8.com/color/48/000000/typescript.png" width="16" height="16" alt="TypeScript"/> TypeScript · NativeWind (Tailwind CSS)
- Zustand (state) · expo-video (background playback) · expo-sqlite (local DB)
- Firebase Remote Config · QR Code activation · YouTube Iframe · React TV Space Navigation
- Package ID: `plus.oxi.app`

---

#### 🌐 Oxi+ Web  
**Repository:** [`oxi.plus_web`](https://github.com/AliBag-de/oxi.plus_web)

Landing page and web platform for the Oxi+ ecosystem. Deployed on **Vercel**.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/nextjs.png" width="16" height="16" alt="Next.js"/> Next.js (App Router) · TypeScript · Tailwind CSS

---

#### ⚙️ Oxi+ Backend API  
**Repository:** [`oxi-player-plusr-backend`](https://github.com/AliBag-de/oxi-player-plusr-backend)

High-performance REST API powering the Oxi+ Player. Handles device licensing, playlist management, media metadata and payments.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/nodejs.png" width="16" height="16" alt="Node.js"/> Fastify v5 (high-performance Node.js framework) · TypeScript
- Prisma v7 (WASM query engine) · PostgreSQL · Redis
- TMDB API integration · Fanart.tv proxy (ClearArt/Logo metadata)
- Stripe (payments) · Twilio (SMS) · Nodemailer
- <img src="https://img.icons8.com/color/48/000000/docker.png" width="16" height="16" alt="Docker"/> Docker (multi-stage build) · Vitest (unit tests)
- API Key auth · Rate Limiting (100 req/min global, 5 req/min activation)
- Endpoints: device registration & activation · M3U/Xtream playlist management · TMDB metadata · media requests

---

#### 🖥️ Oxi Panel — IPTV Reseller Dashboard  
**Repository:** [`oxi-panel`](https://github.com/AliBag-de/oxi-panel)

A reseller management dashboard for XUI.ONE IPTV panels. Acts as a secure bridge between a Next.js frontend and the XUI.ONE reseller API — the frontend never calls the XUI API directly. Real-time updates via Socket.io.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/nextjs.png" width="16" height="16" alt="Next.js"/> Next.js (frontend) · Express.js (backend) · TypeScript
- **Dual-Database:** MariaDB (XUI.ONE read-only source) + PostgreSQL (app data: lines, magic links, customers)
- Prisma (dual client) · Socket.io (real-time) · TanStack Query · Zustand
- JWT + Magic Link authentication · Rate limiting (200 req/min API, 20 req/min auth)
- <img src="https://img.icons8.com/color/48/000000/docker.png" width="16" height="16" alt="Docker"/> Docker Compose (frontend :89 · backend internal) · PHP Xtream/Reseller API bridge
- OpenAPI spec (`openapi.yaml`)

---

### 🏢 Leapoly — Full Stack B2B Platform  
**Repository:** [`leapoly-v2`](https://github.com/AliBag-de/leapoly-v2)

Monorepo full-stack B2B platform with a dedicated backend and frontend.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native · <img src="https://img.icons8.com/color/48/000000/expo.png" width="16" height="16" alt="Expo"/> Expo
- <img src="https://img.icons8.com/color/48/000000/nextjs.png" width="16" height="16" alt="Next.js"/> Next.js &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/mongodb.png" width="16" height="16" alt="MongoDB"/> MongoDB
- <img src="https://icon.icepanel.io/Technology/svg/Traefik-Proxy.svg" width="16" height="16" alt="Traefik"/> Traefik &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/docker.png" width="16" height="16" alt="Docker"/> Docker &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/express-js.png" width="16" height="16" alt="Express.js"/> Express.js

🔗 [Project Architecture](https://github.com/AliBag-de/leapoly-v2)

---

### <img src="https://play-lh.googleusercontent.com/RCpdQQ-wBapemEJLJ1FS0AHd7BlJmeKhQx9fZssUb0THsHOE33YdRkA529m17C-Otg=w480-h960-rw" width="16" height="16" alt="Decalizer"/> Decalizer — 3D Decal Attachment App  
**Repository:** [`satari-clone-project`](https://github.com/AliBag-de/satari-clone-project)

Augmented-reality style 3D decal placement app with real-time Three.js rendering inside a React Native / Expo shell.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/expo.png" width="16" height="16" alt="Expo"/> Expo
- <img src="https://canada1.discourse-cdn.com/flex035/uploads/threejs/original/2X/e/e4f86d2200d2d35c30f7b1494e96b9595ebc2751.png" width="16" height="16" alt="Three.js"/> Three.js (3D rendering)

🔗 [Android — Google Play](https://play.google.com/store/apps/details?id=net.ioxtech.decalizer)

---

### 🛒 EasyShopGo — Fullstack Marketplace  

Consumer-facing mobile marketplace with a Node.js backend.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/nodejs.png" width="16" height="16" alt="Node.js"/> Node.js

🔗 [Android — Google Play](https://play.google.com/store/apps/details?id=de.ioxtech.easyshopgo)

---

### <img src="https://play-lh.googleusercontent.com/1glkP2pCW43iM0bwE43axlSQOByw6VvxTFbfafHz6CTXCsb4Wr4my9Nud-oN2WnQXg=w480-h960-rw" width="16" height="16" alt="LightsOutGo"/> LightsOutGo — Puzzle Game  

Lights-Out puzzle game for Android, published on Google Play.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/expo.png" width="16" height="16" alt="Expo"/> Expo

🔗 [Android — Google Play](https://play.google.com/store/apps/details?id=de.lightsoutgo.iox&hl=en)

---

### 📱 Google Maps — Custom Navigation  
**Repository:** [`expo-maps`](https://github.com/AliBag-de/expo-maps)

Custom turn-by-turn navigation prototype using Google Maps SDK in a React Native / Expo app.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/expo.png" width="16" height="16" alt="Expo"/> Expo
- <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Google_Maps_icon_%282015-2020%29.svg" width="16" height="16" alt="Google Maps"/> Google Maps SDK

🔗 [Expo Build](https://expo.dev/accounts/alibagdat/projects/route-tester/builds/bce30e8c-2b85-48b6-aa94-ef651c986ea7)

---

### 🌐 Stream Manager / Restreamer  
**Repository:** [`restreamer.v2`](https://github.com/AliBag-de/restreamer.v2)

Web-based live stream management and restreaming system.

**🛠️ Technologies:**
- <img src="https://cdn.worldvectorlogo.com/logos/react-1.svg" width="16" height="16" alt="React"/> React.js &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/python.png" width="16" height="16" alt="Python"/> Python (Flask) &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/nodejs.png" width="16" height="16" alt="Node.js"/> Node.js
- <img src="https://img.icons8.com/color/48/000000/docker.png" width="16" height="16" alt="Docker"/> Docker

---

### 🖥️ 3D Portfolio — ioxtech.de  
**Repository:** [`port-web-3d-ioxtech.de`](https://github.com/AliBag-de/port-web-3d-ioxtech.de)

3D interactive portfolio website built with Next.js and Three.js.

**🛠️ Technologies:**
- <img src="https://img.icons8.com/color/48/000000/nextjs.png" width="16" height="16" alt="Next.js"/> Next.js &nbsp;·&nbsp; <img src="https://canada1.discourse-cdn.com/flex035/uploads/threejs/original/2X/e/e4f86d2200d2d35c30f7b1494e96b9595ebc2751.png" width="16" height="16" alt="Three.js"/> Three.js &nbsp;·&nbsp; Tailwind CSS · TypeScript

---

## 🛠️ Technical Stack

**Mobile & Frontend:**
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="16" height="16" alt="React Native"/> React Native / Expo &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/nextjs.png" width="16" height="16" alt="Next.js"/> Next.js &nbsp;·&nbsp; <img src="https://cdn.worldvectorlogo.com/logos/react-1.svg" width="16" height="16" alt="React"/> React.js
- <img src="https://img.icons8.com/color/48/000000/typescript.png" width="16" height="16" alt="TypeScript"/> TypeScript &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/javascript.png" width="16" height="16" alt="JavaScript"/> JavaScript
- <img src="https://canada1.discourse-cdn.com/flex035/uploads/threejs/original/2X/e/e4f86d2200d2d35c30f7b1494e96b9595ebc2751.png" width="16" height="16" alt="Three.js"/> Three.js

**Backend:**
- <img src="https://img.icons8.com/color/48/000000/nodejs.png" width="16" height="16" alt="Node.js"/> Node.js (Fastify v5 · Express.js) &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/python.png" width="16" height="16" alt="Python"/> Python (Flask)
- Prisma ORM &nbsp;·&nbsp; <img src="https://img.icons8.com/color/48/000000/mongodb.png" width="16" height="16" alt="MongoDB"/> MongoDB &nbsp;·&nbsp; PostgreSQL &nbsp;·&nbsp; MariaDB &nbsp;·&nbsp; Redis

**DevOps:**
- <img src="https://img.icons8.com/color/48/000000/docker.png" width="16" height="16" alt="Docker"/> Docker / Docker Compose &nbsp;·&nbsp; <img src="https://icon.icepanel.io/Technology/svg/Traefik-Proxy.svg" width="16" height="16" alt="Traefik"/> Traefik (reverse proxy)
- <img src="https://img.icons8.com/color/48/000000/ubuntu.png" width="16" height="16" alt="Ubuntu"/> Ubuntu Server (self-hosted) &nbsp;·&nbsp; Vercel &nbsp;·&nbsp; EAS (Expo Application Services)
- CI/CD Pipelines &nbsp;·&nbsp; Multi-stage Docker builds

---

<img src="https://play-lh.googleusercontent.com/PgAl0V1pWvER7X9ViFrBaT9Pxye4pRH5Nr9JlD5RbKjNX0bcMRp007dQhd17b0Y28Rwv=w480-h960-rw" width="32" height="32" alt="Upwork"/> [UPWORK Profile](https://www.upwork.com/freelancers/~01823d02b62880312c?mp_source=share)

✉️ alibagdat@hotmail.com
