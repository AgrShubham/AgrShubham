<div align="center">

# Shubham Agrawal

<p align="center">
  <a href="https://shubham-agrawal-portfolio.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&width=680&lines=Software+Development+Engineer+(SDE);Full-Stack+Next.js+%E2%80%A2+React+Native+%2F+Expo+%E2%80%A2+TypeScript;Low-Latency+UDP+Systems+%26+Win32+OS+APIs;Runner-up+%E2%80%94+Udaan+2024+CSI+National+Exhibition" alt="Typing SVG" />
  </a>
</p>

Indore, India • B.Tech CSE '25 (IES, IPS Academy) • Open to Relocation / Remote

<p align="center">
  <a href="https://shubham-agrawal-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Live_Site-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/shubham-agrawal-dev"><img src="https://img.shields.io/badge/LinkedIn-shubham--agrawal--dev-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/AgrShubham"><img src="https://img.shields.io/badge/LeetCode-AgrShubham-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:shubhamagrawal.code@gmail.com"><img src="https://img.shields.io/badge/Email-shubhamagrawal.code%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/AgrShubham"><img src="https://img.shields.io/badge/GitHub-AgrShubham-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://hub.xerj.org/contributors/AgrShubham"><img src="https://hub.xerj.org/contributors/AgrShubham/badge.svg" alt="XERJ Corpus Hub contributor"/></a>
</p>

<sub><b>Interactive Dual-Mode Portfolio:</b> <a href="https://shubham-agrawal-portfolio.vercel.app/">shubham-agrawal-portfolio.vercel.app</a> (<a href="https://github.com/AgrShubham/shubham-agrawal-portfolio">Source</a>) — React 19, TypeScript 5.8, custom HTML5 Canvas grid &amp; 6-viewport Puppeteer audit (0px overflow).</sub>

</div>

<table>
  <tr>
    <td width="33%" align="center">
      <b>🏢 Enterprise Full-Stack &amp; Mobile</b><br/>
      <sub>Next.js 14, Expo / React Native, Prisma &amp; PostgreSQL with atomic concurrency, HMAC security, integer-paise math &amp; real-time SSE.</sub>
    </td>
    <td width="33%" align="center">
      <b>⚡ Low-Latency Systems</b><br/>
      <sub>Sub-millisecond UDP streaming (Port 5002) directly into Win32 <code>user32.dll</code> <code>SendInput</code>, bypassing TCP head-of-line blocking.</sub>
    </td>
    <td width="33%" align="center">
      <b>🛍️ Production Web &amp; Honors</b><br/>
      <sub>Built <b>Shree Mewa</b> (React 19 + Vite 6 + Tailwind v4) &amp; won <b>2nd Position</b> at Udaan 2024 CSI National Project Exhibition.</sub>
    </td>
  </tr>
</table>

---

## 🛠️ Featured Engineering Projects

### 1. [KioskDrop Enterprise](https://kioskdrop-enterprise.vercel.app/) — Smart-Locker ITAM, FinOps & Mobile Platform
> *End-to-end corporate AV hardware triage, 12-bay IoT smart-locker simulator, zero-trust BadUSB defense & Indian Customs FinOps across **Next.js 14** and **React Native / Expo**.*

<p align="center">
  <a href="https://kioskdrop-enterprise.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-Vercel-2ea44f?style=flat-square&logo=vercel&logoColor=white" alt="Live Demo"/></a>
  <a href="https://github.com/AgrShubham/kioskdrop-enterprise"><img src="https://img.shields.io/badge/Web_%26_API-kioskdrop--enterprise-181717?style=flat-square&logo=github&logoColor=white" alt="Web Repo"/></a>
  <a href="https://github.com/AgrShubham/kioskdrop-mobile"><img src="https://img.shields.io/badge/Mobile_App-kioskdrop--mobile-0284c7?style=flat-square&logo=expo&logoColor=white" alt="Mobile Repo"/></a>
  <a href="https://github.com/AgrShubham/kioskdrop-mobile/releases/download/v1.0.0/kioskdrop-enterprise.apk"><img src="https://img.shields.io/badge/Android_APK-v1.0.0-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Download Android APK"/></a>
  <img src="https://img.shields.io/badge/Tests-39_Vitest_%2B_24_Jest-10b981?style=flat-square" alt="63 Tests Passing"/>
  <img src="https://img.shields.io/badge/Security-HMAC--SHA256_%2B_TimingSafe-6366f1?style=flat-square" alt="HMAC Security"/>
</p>

```mermaid
flowchart LR
    A["📱 QR / Mobile App<br/>(Expo SDK 58 + Bearer)"] -->|"Triage &amp; Atomic Lock<br/>(updateMany = 1)"| B["⚙️ Next.js 14 API<br/>(HMAC PIN + SSE Bus)"]
    B -->|"Solenoid &amp; VID/PID<br/>(423 / 409 Guard)"| C["🔐 IoT Smart Locker<br/>(12 Bays + BadUSB)"]
    B -->|"SHA-256 Chain + 44.40% Duty<br/>(Integer Paise + ERP)"| D["📊 Admin Command<br/>(Prisma + FinOps)"]
```

- **Concurrency & Zero-Trust Security:** Atomic `prisma.lockerCompartment.updateMany` (`count === 1`) verified under a **20-worker parallel race test**; timing-safe HMAC-SHA256 OTP verification (`crypto.timingSafeEqual`), 5-fail lockout (`HTTP 423`), BadUSB foreign VID/PID quarantine (`HTTP 409`), and tamper-evident SHA-256 `CustodyLog` hash chaining.
- **FinOps, Customs Math & Telemetry:** Integer-paise Indian Customs Duty Engine (`44.40%` statutory BCD/SWS/IGST with zero float drift), RBAC Zaggle/Happay PO reconciliation (SAP/Oracle/Zoho adapters), ServiceNow/Zendesk webhook replay, and live SSE streaming (`/api/telemetry/stream`) across Web and Android (`react-native-sse`).
- **Verification & Stack:** **39/39** Vitest backend/API tests + **24/24** Jest/RNTL mobile tests passing • `Next.js 14` • `React Native / Expo SDK 58` • `TypeScript` • `Prisma` • `PostgreSQL / SQLite WAL` • `TanStack Query` • `Zustand` • `Zod` • `Docker`

---

### 2. [Remote Trackpad & Gamepad Pro](https://github.com/AgrShubham/Remote-trackpad-app) — Low-Latency Wireless Peripheral Ecosystem
> *Sub-millisecond UDP mouse/gamepad/keyboard engine bypassing TCP head-of-line blocking for Windows 10/11.*

<p align="center">
  <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://img.shields.io/badge/Repository-Remote--trackpad--app-181717?style=flat-square&logo=github&logoColor=white" alt="Repository"/></a>
  <a href="https://github.com/AgrShubham/Remote-trackpad-app/releases/download/v1.0.0/RemoteMouseServer.exe"><img src="https://img.shields.io/badge/Windows_Server-v1.0.0_EXE-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Download Windows Server"/></a>
  <a href="https://github.com/AgrShubham/Remote-trackpad-app/releases/download/v1.0.0/app-release.apk"><img src="https://img.shields.io/badge/Android_App-v1.0.0_APK-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Download Android APK"/></a>
  <img src="https://img.shields.io/badge/UDP_Latency-%3C1ms-10b981?style=flat-square" alt="<1ms Latency"/>
  <img src="https://img.shields.io/badge/OS_API-Win32_SendInput-0284c7?style=flat-square" alt="Win32 SendInput"/>
</p>

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

```mermaid
flowchart LR
    A["📱 Android Client<br/>(Touch &amp; Sensor Engine)"] -->|"⚡ UDP Port 5002 (&lt;1ms)<br/>Zero-Buffer Motion Vectors"| B["🖥️ Windows Tray Daemon<br/>(27MB Standalone Python)"]
    A -.->|"📡 Port 5001 Radar &amp; 5000 WS"| B
    B -->|"Win32 user32.dll<br/>SendInput()"| C["🎯 Driverless OS Input<br/>(Cursor, Gamepad &amp; Keys)"]
```

- **UDP Motion & Kinetic Ballistics:** Bypasses TCP congestion windows via asynchronous UDP datagrams (**Port 5002**) straight into Windows `user32.dll` `SendInput` (`<1ms` execution), shaped by `v_smooth = v_raw * (1.0 + min(2.5, v_raw * 0.6))` and a `0.1px` jitter deadband.
- **Zero-Driver Footprint & Stack:** 27MB standalone tray daemon requiring no kernel drivers or admin privileges • `Python 3.11` • `React Native` • `TypeScript` • `UDP Sockets` • `Win32 API` • `Android SDK`

---

### 3. [Shree Mewa](https://shree-mewa.vercel.app) — Commercial Luxury Boutique & Gifting Platform
> *Production e-commerce platform replacing high-ticket checkout drop-off with a state-driven WhatsApp Concierge pipeline.*

<p align="center">
  <a href="https://shree-mewa.vercel.app"><img src="https://img.shields.io/badge/Live_Boutique-shree--mewa.vercel.app-2ea44f?style=flat-square&logo=vercel&logoColor=white" alt="Live Boutique"/></a>
  <a href="https://github.com/AgrShubham/ShreeMewa"><img src="https://img.shields.io/badge/Repository-ShreeMewa-181717?style=flat-square&logo=github&logoColor=white" alt="Repository"/></a>
  <img src="https://img.shields.io/badge/React-19.0-61dafb?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
  <img src="https://img.shields.io/badge/TypeScript-5.8-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript 5.8"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS v4"/>
  <img src="https://img.shields.io/badge/Vite-6-646cff?style=flat-square&logo=vite&logoColor=white" alt="Vite 6"/>
</p>

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://shree-mewa.vercel.app"><img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/royal-wooden-chest.jpg" width="100%" alt="Royal Keepsake Chest" /></a><br/>
      <b>Royal Keepsake Chest</b><br/><sub>Teakwood heirloom gifting suite</sub>
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

- **Concierge Funnel & Offline Lookbook:** Eliminated bespoke order cart abandonment (`₹25,000+` hampers) by serializing pack weights, delivery tiers, and custom notes directly into WhatsApp; built a CSS `@media print` lookbook engine, route-level `React.lazy` splitting, and Schema.org JSON-LD SEO.

---

### 4. Fintech Mobile Ledger & Zero-Install Web Input

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>💳 <a href="https://github.com/AgrShubham/MiniLedger">MiniLedger</a> — Fintech Mobile App &amp; API</h4>
      <p>
        <img src="https://img.shields.io/badge/Node.js_20-Express-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node"/>
        <img src="https://img.shields.io/badge/PostgreSQL_16-Prisma-336791?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres"/>
        <img src="https://img.shields.io/badge/Expo-React_Native-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo"/>
      </p>
      <ul>
        <li><b>Financial Integrity:</b> Integer minor-unit storage (<code>amountMinor</code>) + SQL database aggregates eliminating IEEE-754 rounding drift; date-only <code>@db.Date</code> overdue invariant (<code>PENDING &amp;&amp; dueDate &lt; today</code>).</li>
        <li><b>Concurrency &amp; Auth:</b> Atomic <code>updateMany</code> repayment guard returning <code>409 ALREADY_REPAID</code>, HMAC-SHA256 rate-limited OTP + JWT (<code>expo-secure-store</code>), UUID-sanitized Multer receipts, and Jest + Supertest integration suite.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🌐 <a href="https://github.com/AgrShubham/Remote_trackpad_web">Remote Trackpad Web</a> — Browser Input Server</h4>
      <p>
        <img src="https://img.shields.io/badge/Python-Flask_%2B_Socket.IO-3776AB?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
        <img src="https://img.shields.io/badge/Audio-Web_Audio_API-E34F26?style=flat-square" alt="Web Audio"/>
      </p>
      <table>
        <tr>
          <td width="50%" align="center"><a href="https://github.com/AgrShubham/Remote_trackpad_web"><img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/Trackpad%20.png" width="100%" alt="Web Trackpad" /></a></td>
          <td width="50%" align="center"><a href="https://github.com/AgrShubham/Remote_trackpad_web"><img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/Keyboard%20control.png" width="100%" alt="Web Mechanical Keyboard" /></a></td>
        </tr>
      </table>
      <ul>
        <li><b>iOS Acoustic Synthesis:</b> Twin-oscillator <b>Web Audio API</b> clicks (<code>1750Hz</code> snap + <code>220Hz</code> clack) bypassing iOS Safari vibration blocks.</li>
        <li><b>60fps rAF Batching:</b> Batches delta vectors via <code>requestAnimationFrame</code>, cutting WebSocket bandwidth by <b>40%</b> over LAN.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 💻 Technical Skills & Stack

<table>
  <tr>
    <td width="21%"><b>Languages</b></td>
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
      <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square" alt="Zustand"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend &amp; Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
      <img src="https://img.shields.io/badge/RESTful_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs"/>
      <img src="https://img.shields.io/badge/SSE_%26_WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="SSE and WebSockets"/>
      <img src="https://img.shields.io/badge/UDP_Sockets-4B5563?style=flat-square" alt="UDP Sockets"/>
      <img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Win32 API"/>
    </td>
  </tr>
  <tr>
    <td><b>Databases &amp; QA</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/>
      <img src="https://img.shields.io/badge/SQLite_WAL-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
      <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod"/>
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"/>
      <img src="https://img.shields.io/badge/Jest_%26_Supertest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest"/>
    </td>
  </tr>
  <tr>
    <td><b>Cloud &amp; DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
  </tr>
</table>

---

## 📊 Developer Velocity & Problem Solving

<div align="center">
  <table border="0">
    <tr>
      <td width="46%" align="center">
        <a href="https://github.com/AgrShubham">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AgrShubham&theme=tokyonight" alt="GitHub Stats" width="100%" />
        </a>
      </td>
      <td width="54%" align="center">
        <a href="https://leetcode.com/AgrShubham">
          <img src="https://leetcard.jacoblin.cool/AgrShubham?theme=dark&font=Inter" alt="LeetCode Stats" width="100%" />
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 💼 Experience, Education & Verified Credentials

- **Frontend Web Development Intern — Amnesea (May 2023 – Jul 2023):** Built 15+ modular React & Tailwind CSS components, integrated RESTful APIs with error boundaries, and improved page-load performance by **~35%** (audited via Google Lighthouse).
- **Education & Honor:** **B.Tech in Computer Science & Engineering** (2021 – 2025), IES, IPS Academy, Indore • 🏆 **2nd Position (Runner-up)** — *Udaan 2024 CSI National Project Exhibition*.
- **Verified Certifications:** [AWS Academy Cloud Foundations](https://www.credly.com/go/1mNIxVxM) • [AWS Academy Machine Learning Foundations](https://www.credly.com/go/olUPF91W) • **React.js Essential Training** & **Learning Git and GitHub** (LinkedIn Learning).

<div align="center">
  <sub>© Shubham Agrawal • <a href="https://shubham-agrawal-portfolio.vercel.app/">Portfolio</a> • <a href="https://linkedin.com/in/shubham-agrawal-dev">LinkedIn</a> • <a href="mailto:shubhamagrawal.code@gmail.com">shubhamagrawal.code@gmail.com</a></sub>
</div>
