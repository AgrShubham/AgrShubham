<div align="center">

# Shubham Agrawal

<p align="center">
  <a href="https://shubham-agrawal-portfolio.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&width=680&lines=Software+Development+Engineer+(SDE-1);Full-Stack+Next.js+%E2%80%A2+React+Native+%2F+Expo+%E2%80%A2+TypeScript;Low-Latency+UDP+Systems+%26+Win32+OS+APIs;Runner-up+%E2%80%94+Udaan+2024+CSI+National+Exhibition" alt="Typing SVG" />
  </a>
</p>

**Indore, India** • B.Tech CSE '25 (IES, IPS Academy) • Open to Relocation & Remote

<p align="center">
  <a href="https://shubham-agrawal-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Live_Site-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/shubham-agrawal-dev"><img src="https://img.shields.io/badge/LinkedIn-shubham--agrawal--dev-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/AgrShubham"><img src="https://img.shields.io/badge/LeetCode-AgrShubham-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:shubhamagrawal.code@gmail.com"><img src="https://img.shields.io/badge/Email-shubhamagrawal.code%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://hub.xerj.org/contributors/AgrShubham"><img src="https://hub.xerj.org/contributors/AgrShubham/badge.svg" alt="XERJ Corpus Hub contributor"/></a>
</p>

</div>

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <h4>🏢 Enterprise Full-Stack</h4>
      <sub><b>Next.js 14, Expo, PostgreSQL &amp; Prisma</b><br/>Atomic concurrency, HMAC-SHA256 security, integer-paise FinOps &amp; live SSE telemetry.</sub>
    </td>
    <td width="33%" align="center" valign="top">
      <h4>⚡ Low-Latency Systems</h4>
      <sub><b>&lt;1ms UDP + Win32 SendInput</b><br/>Driverless wireless input streaming over Port 5002 bypassing TCP head-of-line blocking.</sub>
    </td>
    <td width="33%" align="center" valign="top">
      <h4>🛍️ Production Web &amp; Honors</h4>
      <sub><b>React 19, TypeScript 5.8 &amp; CSI Udaan '24</b><br/>Commercial <b>Shree Mewa</b> boutique &amp; <b>2nd Position</b> nationally at CSI Udaan 2024.</sub>
    </td>
  </tr>
</table>

---

## 🛠️ Featured Engineering Projects

### 1. [KioskDrop Enterprise](https://kioskdrop-enterprise.vercel.app/) — Smart-Locker ITAM, FinOps & Mobile Platform
> *Autonomous corporate AV hardware triage, 12-bay IoT smart-locker simulator, zero-trust BadUSB defense & Indian Customs FinOps across **Next.js 14** and **React Native / Expo SDK 58**.*

[![Live Demo](https://img.shields.io/badge/Live_Demo-Vercel-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://kioskdrop-enterprise.vercel.app/)
[![Web & API Repo](https://img.shields.io/badge/Web_%26_API-kioskdrop--enterprise-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AgrShubham/kioskdrop-enterprise)
[![Mobile Repo](https://img.shields.io/badge/Mobile_App-kioskdrop--mobile-0284c7?style=flat-square&logo=expo&logoColor=white)](https://github.com/AgrShubham/kioskdrop-mobile)
[![Android APK](https://img.shields.io/badge/Android_APK-v1.0.0-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/AgrShubham/kioskdrop-mobile/releases/download/v1.0.0/kioskdrop-enterprise.apk)
![Tests Passing](https://img.shields.io/badge/Tests-39_Vitest_%2B_24_Jest-10b981?style=flat-square)

```mermaid
flowchart LR
    A["📱 QR / Expo App<br/>(Bearer + SecureStore)"] -->|"Atomic updateMany = 1<br/>(20-Worker Tested)"| B["⚙️ Next.js 14 API<br/>(HMAC PIN + SSE Bus)"]
    B -->|"Solenoid &amp; VID/PID<br/>(423 Lockout / 409 BadUSB)"| C["🔐 IoT Smart Locker<br/>(12 Bays / Floor)"]
    B -->|"SHA-256 CustodyLog<br/>+ 44.40% Paise Duty"| D["📊 Admin Command<br/>(FinOps &amp; ERP)"]
```

- **Race-Safe Reservations & Live Telemetry:** Conditional `prisma.lockerCompartment.updateMany` (`count === 1`) verified under a **20-worker parallel race test**; live `/api/telemetry/stream` SSE sync across web dashboards and Android (`react-native-sse` + Zod).
- **Zero-Trust Hardware & Audit Security:** Salted HMAC-SHA256 OTP comparison (`crypto.timingSafeEqual`), 5-fail lockout (`HTTP 423`), foreign VID/PID BadUSB quarantine (`HTTP 409`), and immutable SHA-256 hash-chained `CustodyLog`.
- **Indian Customs Duty & FinOps ERP:** Zero-drift integer-paise duty calculator (`44.40%` BCD/SWS/IGST), RBAC Zaggle/Happay card reconciliation (`SAP`, `Oracle`, `Zoho` adapters), ServiceNow/Zendesk webhook replay, and **39/39 Vitest + 24/24 Jest** passing tests.

---

### 2. [Remote Trackpad & Gamepad Pro](https://github.com/AgrShubham/Remote-trackpad-app) — Sub-Millisecond Wireless Peripheral
> *Driverless UDP peripheral ecosystem turning an Android phone into a precision PC trackpad, 3-layout console gamepad & mechanical keyboard.*

[![Repository](https://img.shields.io/badge/GitHub-Remote--trackpad--app-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AgrShubham/Remote-trackpad-app)
[![Windows Server](https://img.shields.io/badge/Windows_Server-v1.0.0_EXE-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/AgrShubham/Remote-trackpad-app/releases/download/v1.0.0/RemoteMouseServer.exe)
[![Android App](https://img.shields.io/badge/Android_App-v1.0.0_APK-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/AgrShubham/Remote-trackpad-app/releases/download/v1.0.0/app-release.apk)
![UDP Latency](https://img.shields.io/badge/UDP_Latency-%3C1ms-10b981?style=flat-square)
![Win32](https://img.shields.io/badge/OS_API-Win32_SendInput-0284c7?style=flat-square)

<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/trackpad_preview.jpeg" width="100%" alt="Precision Glass Trackpad" /></a><br/>
      <b>Precision Trackpad</b><br/><sub>0.1px deadband &amp; ballistics</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/gamepad_arc_preview.jpeg" width="100%" alt="Arc Console Gamepad" /></a><br/>
      <b>Console Gamepad</b><br/><sub>Arc, Xbox &amp; PlayStation layouts</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/keyboard_landscape_preview.jpeg" width="100%" alt="Mechanical Keyboard" /></a><br/>
      <b>Mechanical Keyboard</b><br/><sub>3D bevel keycaps &amp; LED states</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/media_remote_preview.jpeg" width="100%" alt="Hifi Media Remote" /></a><br/>
      <b>Hifi Media Deck</b><br/><sub>Touch scrubber &amp; video controls</sub>
    </td>
  </tr>
</table>

- **Sub-Millisecond UDP Pipeline:** Streams cursor vectors via **Port 5002** UDP datagrams directly into Windows `user32.dll` `SendInput` (`<1ms` execution), eliminating TCP head-of-line blocking alongside **Port 5001** Wi-Fi radar auto-discovery.
- **Kinetic Ballistics & Driverless Daemon:** Smooth velocity curve `v_smooth = v_raw * (1.0 + min(2.5, v_raw * 0.6))` with `0.1px` deadband filtering, running inside a 27.5MB standalone Windows tray server with zero kernel drivers (`Python 3.11 • React Native • TypeScript • Win32 API`).

---

### 3. [Shree Mewa](https://shree-mewa.vercel.app) — Commercial Boutique & Gifting Platform
> *Production e-commerce platform replacing high-ticket checkout drop-off with a state-driven WhatsApp Concierge pipeline.*

[![Live Boutique](https://img.shields.io/badge/Live_Boutique-shree--mewa.vercel.app-2ea44f?style=flat-square&logo=vercel&logoColor=white)](https://shree-mewa.vercel.app)
[![Repository](https://img.shields.io/badge/GitHub-ShreeMewa-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AgrShubham/ShreeMewa)
![React 19](https://img.shields.io/badge/React-19.0-61dafb?style=flat-square&logo=react&logoColor=black)
![TypeScript 5.8](https://img.shields.io/badge/TypeScript-5.8-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind v4](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite 6](https://img.shields.io/badge/Vite-6-646cff?style=flat-square&logo=vite&logoColor=white)

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://shree-mewa.vercel.app"><img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/royal-wooden-chest.jpg" width="100%" alt="Royal Keepsake Chest" /></a><br/>
      <b>Royal Keepsake Chest</b><br/><sub>Teakwood heirloom suite</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://shree-mewa.vercel.app"><img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/imperial-velvet-box.jpg" width="100%" alt="Imperial Velvet Suite" /></a><br/>
      <b>Imperial Velvet Suite</b><br/><sub>24K gold foil rigid gift box</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://shree-mewa.vercel.app"><img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/trousseau-hamper.jpg" width="100%" alt="Shubh Vivah Hamper" /></a><br/>
      <b>Shubh Vivah Hamper</b><br/><sub>Handcrafted bridal platter</sub>
    </td>
  </tr>
</table>

- **WhatsApp Concierge & Lookbook Engine:** Eliminated cart abandonment on bespoke orders (`₹25,000+`) by encoding pack weights, delivery tiers, and notes directly into WhatsApp inquiry links; added offline `@media print` PDF lookbook exports, `React.lazy` splitting, and Schema.org JSON-LD SEO.

---

### 4. More Engineering Builds

| Project | Key Engineering Highlights | Stack & Links |
| :--- | :--- | :--- |
| **💳 [MiniLedger](https://github.com/AgrShubham/MiniLedger)** | Fintech loan ledger API & Expo mobile app built with integer minor-unit storage (`amountMinor`) + SQL aggregates, date-only `@db.Date` overdue invariant, atomic `updateMany` returning `409 ALREADY_REPAID`, HMAC-SHA256 OTP + JWT (`SecureStore`), UUID-sanitized Multer receipts & Jest/Supertest suite. | `Node 20` · `Express` · `PostgreSQL 16` · `Prisma` · `Expo` · `TanStack Query` · `Zod`<br/>[**Repository ↗**](https://github.com/AgrShubham/MiniLedger) |
| **🌐 [Remote Trackpad Web](https://github.com/AgrShubham/Remote_trackpad_web)** | Zero-install browser trackpad, dual-layout gamepad & TKL keyboard; twin-oscillator **Web Audio API** (`1750Hz` snap + `220Hz` clack) bypassing iOS Safari vibration restriction, plus `requestAnimationFrame` delta batching cutting WebSocket traffic by **40%** at 60fps. | `Python` · `Flask` · `Socket.IO` · `Web Audio API` · `Pynput`<br/>[**Repository ↗**](https://github.com/AgrShubham/Remote_trackpad_web) |
| **✨ [Interactive Portfolio](https://shubham-agrawal-portfolio.vercel.app/)** | Dual-mode engineering portfolio featuring a custom 60fps HTML5 Canvas coordinate grid with spring-damped spotlight & click shockwaves, integrated ATS PDF modal, and automated headless Puppeteer verification across 6 viewports (`0px` overflow). | `React 19` · `TypeScript 5.8` · `Tailwind CSS v4` · `Vite 6`<br/>[**Live Site ↗**](https://shubham-agrawal-portfolio.vercel.app/) · [**Source ↗**](https://github.com/AgrShubham/shubham-agrawal-portfolio) |

---

## 💻 Technical Skills & Stack

<table>
  <tr>
    <td width="20%"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
    </td>
  </tr>
  <tr>
    <td><b>Frontend &amp; Mobile</b></td>
    <td>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
      <img src="https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native"/>
      <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
      <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="TanStack Query"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend &amp; Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs"/>
      <img src="https://img.shields.io/badge/SSE_%26_WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="SSE and WebSockets"/>
      <img src="https://img.shields.io/badge/UDP_Sockets-4B5563?style=flat-square" alt="UDP Sockets"/>
      <img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Win32 API"/>
    </td>
  </tr>
  <tr>
    <td><b>Data, Testing &amp; Cloud</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
      <img src="https://img.shields.io/badge/Vitest_%26_Jest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest and Jest"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
  </tr>
</table>

---

## 📊 Developer Activity & Problem Solving

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <a href="https://github.com/AgrShubham">
          <img src="https://streak-stats.demolab.com/?user=AgrShubham&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="100%" />
        </a>
      </td>
      <td width="50%" align="center">
        <a href="https://leetcode.com/AgrShubham">
          <img src="https://leetcard.jacoblin.cool/AgrShubham?theme=dark&font=Inter" alt="LeetCode Stats" width="100%" />
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 💼 Experience, Education & Verified Credentials

- **Frontend Web Development Intern — Amnesea** *(May 2023 – Jul 2023)*: Built 15+ modular React & Tailwind CSS components, integrated RESTful APIs with error boundaries, and reduced initial page-load latency by **~35%** (audited via Google Lighthouse).
- **B.Tech in Computer Science & Engineering** *(2021 – 2025)* — IES, IPS Academy, Indore • 🏆 **2nd Position (Runner-up)**, *Udaan 2024 CSI National Project Exhibition*.
- **Verified Certifications:** [AWS Academy Cloud Foundations](https://www.credly.com/go/1mNIxVxM) • [AWS Academy Machine Learning Foundations](https://www.credly.com/go/olUPF91W) • **React.js Essential Training** & **Learning Git and GitHub** *(LinkedIn Learning)*.

<div align="center">
  <sub>© Shubham Agrawal • <a href="https://shubham-agrawal-portfolio.vercel.app/">Portfolio</a> • <a href="https://linkedin.com/in/shubham-agrawal-dev">LinkedIn</a> • <a href="mailto:shubhamagrawal.code@gmail.com">shubhamagrawal.code@gmail.com</a></sub>
</div>
