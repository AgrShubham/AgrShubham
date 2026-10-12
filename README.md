<div align="center">

# Shubham Agrawal

**Software Development Engineer (SDE)**  
*Low-Latency Systems • Networked Peripherals • Modern Web Applications*

India • [shubham-agrawal-portfolio.vercel.app](https://shubham-agrawal-portfolio.vercel.app/) • [shubhamagrawal.code@gmail.com](mailto:shubhamagrawal.code@gmail.com) • [+91 8825388041](tel:+918825388041)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-shubham--agrawal-000000?style=flat-square&logo=vercel&logoColor=white)](https://shubham-agrawal-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shubham--agrawal--dev-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/shubham-agrawal-dev)
[![LeetCode](https://img.shields.io/badge/LeetCode-AgrShubham-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/AgrShubham)
[![Email](https://img.shields.io/badge/Email-shubhamagrawal.code%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:shubhamagrawal.code@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-AgrShubham-181717?style=flat-square&logo=github)](https://github.com/AgrShubham)

</div>

---

## Engineering Overview

Software Development Engineer focused on low-latency systems, networked peripherals, and full-stack web applications. Experienced in engineering sub-millisecond network pipelines, commercial SPAs using React 19 and TypeScript, and scalable RESTful services.

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>⚡ Low-Latency Systems</h4>
      <p>Engineered asynchronous UDP datagram pipelines delivering motion deltas into Win32 OS APIs with <b>&lt;1ms execution latency</b>, bypassing TCP head-of-line blocking.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🛍️ Commercial Web Platforms</h4>
      <p>Architected and deployed <b>Shree Mewa</b> on React 19, TypeScript 5.8, Tailwind CSS v4, and Vite 6; solved cart abandonment with an automated concierge pipeline.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🏆 Academic Distinction</h4>
      <p><b>2nd Position (Runner-up)</b> — Udaan 2024 CSI (Computer Society of India) National Project Exhibition. B.Tech in CSE (Sep 2021 – May 2025).</p>
    </td>
  </tr>
</table>

---

## Featured Engineering Projects

### 1. Remote Trackpad & Gamepad Pro
**Turn Smartphone into PC Trackpad, Gamepad & Keyboard**

<table>
  <tr>
    <td width="54%" valign="middle" align="center">
      <a href="https://github.com/AgrShubham/Remote-trackpad-app">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/banner.jpg" alt="Remote Trackpad & Gamepad Pro Banner" width="100%" style="border-radius: 8px;" />
      </a>
      <br/><br/>
      <a href="https://github.com/AgrShubham/Remote-trackpad-app"><img src="https://img.shields.io/badge/Repository-Remote--Trackpad--App-181717?style=flat-square&logo=github" alt="Repository"/></a>
      <a href="https://github.com/AgrShubham/Remote-trackpad-app/releases"><img src="https://img.shields.io/badge/Download_Windows_Server-v1.0.0-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Download Windows Server"/></a>
      <a href="https://github.com/AgrShubham/Remote-trackpad-app/releases"><img src="https://img.shields.io/badge/Download_Android_APK-v1.0.0-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Download Android APK"/></a>
    </td>
    <td width="46%" valign="top">
      <p>Open-source, ultra-low-latency wireless peripheral system converting smartphones into zero-lag input controllers for Windows 10 & 11 PCs.</p>
      <ul>
        <li><b>Sub-Millisecond UDP Pipeline:</b> Asynchronous datagram streaming over <code>Port 5002</code> directly injecting cursor deltas into <code>user32.dll</code> via Win32 <code>SendInput</code> with <b>&lt;1ms execution latency</b>.</li>
        <li><b>Kinetic Velocity Ballistics:</b> Mathematical acceleration model (<code>v_smooth = v_raw * (1.0 + min(2.5, v_raw * 0.6))</code>) with 0.1px deadband filtering.</li>
        <li><b>Driverless Daemon:</b> Standalone 27MB Windows system tray executable without third-party kernel drivers or elevated administrative rights.</li>
      </ul>
      <p>
        <code>Python 3.11</code> • <code>React Native</code> • <code>TypeScript</code> • <code>UDP Sockets</code> • <code>Win32 API</code>
      </p>
    </td>
  </tr>
</table>

<details>
  <summary><b>🔍 View Interface Previews & Layouts (Trackpad, Gamepad, Keyboard, Media Deck)</b></summary>
  <br/>
  <table>
    <tr>
      <td align="center" width="25%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/trackpad_preview.jpeg" width="100%" alt="Precision Glass Trackpad" style="border-radius: 6px;" /><br/>
        <sub><b>Glass Trackpad</b><br/>0.1px precision & gestures</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/gamepad_arc_preview.jpeg" width="100%" alt="Arc Console Gamepad" style="border-radius: 6px;" /><br/>
        <sub><b>Arc Gamepad</b><br/>Ergonomic handheld console</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/keyboard_landscape_preview.jpeg" width="100%" alt="Mechanical Keyboard" style="border-radius: 6px;" /><br/>
        <sub><b>Mechanical Keyboard</b><br/>3D bevel keycaps & LEDs</sub>
      </td>
      <td align="center" width="25%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote-trackpad-app/main/assets/media_remote_preview.jpeg" width="100%" alt="Hifi Media Remote Deck" style="border-radius: 6px;" /><br/>
        <sub><b>Hifi Media Deck</b><br/>Volume scrubber & transport</sub>
      </td>
    </tr>
  </table>
</details>

<br/>

### 2. Shree Mewa Commercial Platform
**Commercial Boutique & Gifting E-Commerce Store**

<table>
  <tr>
    <td width="54%" valign="middle" align="center">
      <a href="https://shree-mewa.vercel.app">
        <img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/royal-wooden-chest.jpg" alt="Shree Mewa Luxury Hampers Preview" width="100%" style="border-radius: 8px;" />
      </a>
      <br/><br/>
      <a href="https://shree-mewa.vercel.app"><img src="https://img.shields.io/badge/Live_Showroom-shreemewa.vercel.app-2ea44f?style=flat-square&logo=vercel&logoColor=white" alt="Live Showroom"/></a>
      <a href="https://github.com/AgrShubham/ShreeMewa"><img src="https://img.shields.io/badge/Repository-ShreeMewa-181717?style=flat-square&logo=github" alt="Repository"/></a>
    </td>
    <td width="46%" valign="top">
      <p>Commercial full-stack digital platform for an artisanal dry fruits purveyor and ceremonial gifting boutique, deployed in production on Vercel.</p>
      <ul>
        <li><b>Modern React 19 Platform:</b> Engineered with <b>React 19, TypeScript 5.8, Tailwind CSS v4, and Vite 6</b> with single-page routing and sub-second load times.</li>
        <li><b>WhatsApp Concierge Funnel:</b> Mitigated high-value order cart abandonment (₹25,000+) through state-driven checkout serializing configurations directly into WhatsApp inquiries.</li>
        <li><b>Client-Side Lookbook Engine:</b> Instant offline PDF catalog generation leveraging dedicated CSS <code>@media print</code> stylesheets and Web Share API.</li>
      </ul>
      <p>
        <code>React 19</code> • <code>TypeScript 5.8</code> • <code>Tailwind CSS v4</code> • <code>Vite 6</code> • <code>Vercel</code>
      </p>
    </td>
  </tr>
</table>

<details>
  <summary><b>🔍 View Gifting Collection Previews</b></summary>
  <br/>
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/imperial-velvet-box.jpg" width="100%" alt="The Imperial Emerald Velvet Box" style="border-radius: 6px;" /><br/>
        <sub><b>Imperial Velvet Box</b><br/>24K gold foil rigid box</sub>
      </td>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/trousseau-hamper.jpg" width="100%" alt="The Shubh Vivah Trousseau Hamper" style="border-radius: 6px;" /><br/>
        <sub><b>Shubh Vivah Hamper</b><br/>Handcrafted wedding platter</sub>
      </td>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/ShreeMewa/main/public/assets/gifting/executive-sovereign-box.jpg" width="100%" alt="The Executive Sovereign Box" style="border-radius: 6px;" /><br/>
        <sub><b>Executive Sovereign Box</b><br/>Midnight matte corporate gift</sub>
      </td>
    </tr>
  </table>
</details>

<br/>

### 3. Remote Trackpad Web
**Turn Smartphone Browser into PC Mouse (Zero Installation)**

<table>
  <tr>
    <td width="54%" valign="middle" align="center">
      <a href="https://github.com/AgrShubham/Remote_trackpad_web">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/banner.jpg" alt="Remote Trackpad Web Hero Banner" width="100%" style="border-radius: 8px;" />
      </a>
      <br/><br/>
      <a href="https://github.com/AgrShubham/Remote_trackpad_web"><img src="https://img.shields.io/badge/Repository-Remote__trackpad__web-181717?style=flat-square&logo=github" alt="Repository"/></a>
    </td>
    <td width="46%" valign="top">
      <p>Zero-install browser-based input server running over local Wi-Fi with real-time WebSocket synchronization and synthetic acoustic haptics.</p>
      <ul>
        <li><b>Zero-Install Input Server:</b> Lightweight Flask and Socket.IO server turning any mobile browser into a PC mouse via local Wi-Fi.</li>
        <li><b>Acoustic Feedback Synthesis:</b> Synthesized mechanical switch acoustics using the <b>Web Audio API</b> (1750Hz tactile snap + 220Hz bottom-out clack), bypassing iOS Safari vibration restrictions.</li>
        <li><b>Touch Event Batching:</b> Batched touch coordinate deltas with <code>requestAnimationFrame</code>, reducing WebSocket bandwidth by <b>40%</b> while maintaining smooth 60fps tracking.</li>
      </ul>
      <p>
        <code>Python</code> • <code>Flask</code> • <code>Socket.IO</code> • <code>JavaScript</code> • <code>Web Audio API</code> • <code>Pynput</code>
      </p>
    </td>
  </tr>
</table>

<details>
  <summary><b>🔍 View Web Controller Previews (Trackpad, Gamepad, Keyboard)</b></summary>
  <br/>
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/Trackpad%20.png" width="100%" alt="Web Trackpad Interface" style="border-radius: 6px;" /><br/>
        <sub><b>Browser Trackpad</b><br/>Multi-touch gesture surface</sub>
      </td>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/Gamepad%20layout%201.png" width="100%" alt="Web Gamepad Interface" style="border-radius: 6px;" /><br/>
        <sub><b>Browser Gamepad</b><br/>Virtual D-Pad & action triggers</sub>
      </td>
      <td align="center" width="33%">
        <img src="https://raw.githubusercontent.com/AgrShubham/Remote_trackpad_web/main/assets/Keyboard%20control.png" width="100%" alt="Web Keyboard Interface" style="border-radius: 6px;" /><br/>
        <sub><b>Browser Keyboard</b><br/>Desktop keyboard shortcuts</sub>
      </td>
    </tr>
  </table>
</details>

---

## Technical Skills & Ecosystem

<table>
  <tr>
    <td width="20%"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
    </td>
  </tr>
  <tr>
    <td><b>Frontend & Mobile</b></td>
    <td>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend & Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
      <img src="https://img.shields.io/badge/RESTful_APIs-005571?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs"/>
      <img src="https://img.shields.io/badge/UDP_Sockets-4B5563?style=flat-square" alt="UDP Sockets"/>
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets"/>
      <img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Win32 API"/>
    </td>
  </tr>
  <tr>
    <td><b>Cloud & Tooling</b></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
    </td>
  </tr>
</table>

---

## GitHub Analytics & Velocity

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=AgrShubham&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="100%" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AgrShubham&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="100%" />
      </td>
    </tr>
  </table>
</div>

---

## Professional Background & Credentials

- **Internship Experience:** Former Frontend Web Development Intern at *Amnesea*; engineered modular React components, integrated backend RESTful APIs, and reduced page-load latency by ~35% (audited via Google Lighthouse).
- **Certifications:**
  - AWS Academy Graduate — AWS Academy Cloud Foundations
  - AWS Academy Graduate — AWS Academy Cloud Developing
  - AWS Academy Graduate — AWS Academy Machine Learning Foundations
- **Core Coursework:** Data Structures & Algorithms, Object-Oriented Programming (Java/C++), Operating Systems, Database Management Systems (DBMS), Computer Networks.

---

<div align="center">
  <p>
    <b>Explore More:</b> <a href="https://shubham-agrawal-portfolio.vercel.app/">shubham-agrawal-portfolio.vercel.app</a> &nbsp;|&nbsp; 
    <a href="https://linkedin.com/in/shubham-agrawal-dev">LinkedIn</a> &nbsp;|&nbsp; 
    <a href="mailto:shubhamagrawal.code@gmail.com">Contact via Email</a>
  </p>
  <sub>© Shubham Agrawal • Engineered with precision</sub>
</div>
