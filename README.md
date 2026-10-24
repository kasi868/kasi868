<!--
  Profile README for github.com/kasi868
  Before publishing: replace the two placeholders below (search for "REPLACE")
    1. YOUR-LINKEDIN-SLUG  -> your LinkedIn profile slug
    2. YOUR-EMAIL          -> your email address
-->

<!-- ═══════════════════════════ HERO ═══════════════════════════ -->

<img width="100%" alt="Header banner: Kasi Viswanath Anuboyina, Software Engineer" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0b1220,50:0f2a44,100:0e7490&text=Kasi%20Viswanath%20Anuboyina&fontColor=e2e8f0&fontSize=36&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20Mobile&descAlignY=58&descSize=16&animation=fadeIn" />

<p align="center">
  <a href="https://github.com/kasi868">
    <img alt="Typing animation: Building reliable web applications, mobile experiences, and backend systems" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=620&height=40&lines=Building+reliable+web+applications;React+Native+mobile+apps+for+Android+%26+iOS;Python+%2B+FastAPI+backend+services;Transaction-safe+workflows+on+PostgreSQL" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/kasi868"><img alt="GitHub: kasi868" src="https://img.shields.io/badge/GitHub-kasi868-0f172a?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-SLUG/"><img alt="LinkedIn profile" src="https://img.shields.io/badge/LinkedIn-Connect-0e7490?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:YOUR-EMAIL"><img alt="Send an email" src="https://img.shields.io/badge/Email-Contact-1e293b?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <b>Software Engineer</b> building reliable web applications, mobile experiences, and backend systems.<br/>
  I work across <b>React</b> and <b>React Native</b> on the front, <b>Python / FastAPI</b> services on the back,
  and <b>PostgreSQL</b> underneath — with a focus on correctness: transactions, retries, validation, and the edge cases that break real apps.
</p>

<br/>

<!-- ═══════════════════════════ ROLES ═══════════════════════════ -->

## ◆ What I Do

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>⚙️ Software Engineer</h3>
      <sub>
        • Debugging and root-cause analysis<br/>
        • Data consistency with transactions, row locking and idempotency<br/>
        • Defensive error handling and input validation<br/>
        • Clear separation of responsibilities between layers
      </sub>
    </td>
    <td width="33%" valign="top">
      <h3>🧩 Full Stack Developer</h3>
      <sub>
        • React.js interfaces backed by FastAPI REST services<br/>
        • PostgreSQL schemas for transactional business workflows<br/>
        • Role-based access control and scope-aware authorization<br/>
        • Docker-based development environments
      </sub>
    </td>
    <td width="33%" valign="top">
      <h3>📱 Mobile Developer</h3>
      <sub>
        • React Native apps for Android and iOS<br/>
        • Resumable chunked uploads with SHA-256 verification<br/>
        • Persistent SQLite queues with background sync<br/>
        • Android builds, foreground services and debugging
      </sub>
    </td>
  </tr>
</table>

<!-- ═══════════════════════════ STACK ═══════════════════════════ -->

## ◆ Tech Stack

<table>
  <tr>
    <td width="140"><b>Languages</b></td>
    <td><img height="38" alt="Python, Java, JavaScript, TypeScript" src="https://skillicons.dev/icons?i=py,java,js,ts&theme=dark" /> &nbsp;<sub>+ SQL</sub></td>
  </tr>
  <tr>
    <td><b>Web</b></td>
    <td><img height="38" alt="React, Tailwind CSS, HTML5, CSS3" src="https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>Mobile</b></td>
    <td><img height="38" alt="React Native, Android Studio" src="https://skillicons.dev/icons?i=react,androidstudio&theme=dark" /> &nbsp;<sub>React Native · cross-platform · background sync · media caching</sub></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img height="38" alt="FastAPI, Node.js" src="https://skillicons.dev/icons?i=fastapi,nodejs&theme=dark" /> &nbsp;<sub>REST APIs · auth · validation · transactional workflows</sub></td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><img height="38" alt="PostgreSQL, MySQL, SQLite, Redis" src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" /> &nbsp;<sub>modeling · indexing · transactions · WAL</sub></td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td><img height="38" alt="Git, GitHub, Docker, AWS" src="https://skillicons.dev/icons?i=git,github,docker,aws&theme=dark" /></td>
  </tr>
</table>

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->

## ◆ Featured Projects

### 📦 Gallery Hub — Mobile Media Backup

<sub>
<img alt="React Native" src="https://img.shields.io/badge/React_Native-0f172a?style=flat-square&logo=react&logoColor=61DAFB" />
<img alt="Python" src="https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=FFD43B" />
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0f172a?style=flat-square&logo=fastapi&logoColor=22D3EE" />
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-0f172a?style=flat-square&logo=sqlite&logoColor=7dd3fc" />
<img alt="Android" src="https://img.shields.io/badge/Android-0f172a?style=flat-square&logo=android&logoColor=3DDC84" />
</sub>

**Problem —** Large phone videos fail to upload on unstable mobile networks, and a dropped connection usually means starting over.

**Approach**
- Resumable chunked uploads using `Content-Range`, with **SHA-256** verification on the server
- Persistent **SQLite** upload queue (WAL mode, indexed) that survives app restarts
- Network-loss recovery, retries, cancellation and adaptive chunk sizing
- Android foreground backup service with background processing
- Authenticated video playback and on-device media caching

<!-- REPLACE: add a repo link here once confirmed, e.g. <a href="https://github.com/kasi868/REPO">Repository →</a> -->

<br/>

### 🧾 ERP + POS — Retail ERP & Point of Sale

<sub>
<img alt="React" src="https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=61DAFB" />
<img alt="Python" src="https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=FFD43B" />
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0f172a?style=flat-square&logo=fastapi&logoColor=22D3EE" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0f172a?style=flat-square&logo=postgresql&logoColor=7dd3fc" />
<img alt="Docker" src="https://img.shields.io/badge/Docker-0f172a?style=flat-square&logo=docker&logoColor=2496ED" />
</sub>

**Problem —** Retail checkout must never double-charge, oversell stock, or skip an invoice number — even under concurrent requests.

**Approach**
- Transaction-safe checkout with **row locking**, **idempotency keys** and gap-free document sequencing
- Payment validation and atomic inventory updates in a single transaction
- Product, inventory, billing, returns, refunds and reporting modules
- Stock movement, damaged-inventory and audit workflows
- Role-based access control across staff roles

<p>
  <a href="https://github.com/kasi868/ERP"><img alt="ERP backend repository" src="https://img.shields.io/badge/ERP_Backend-Repository_→-0e7490?style=flat-square&logo=github" /></a>
  <a href="https://github.com/kasi868/POS"><img alt="POS frontend repository" src="https://img.shields.io/badge/POS_Frontend-Repository_→-0e7490?style=flat-square&logo=github" /></a>
</p>

<br/>

### 🎓 ICMS — Integrated College Management System

<sub>
<img alt="React" src="https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=61DAFB" />
<img alt="Python" src="https://img.shields.io/badge/Python-0f172a?style=flat-square&logo=python&logoColor=FFD43B" />
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0f172a?style=flat-square&logo=fastapi&logoColor=22D3EE" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0f172a?style=flat-square&logo=postgresql&logoColor=7dd3fc" />
<img alt="Redis" src="https://img.shields.io/badge/Redis-0f172a?style=flat-square&logo=redis&logoColor=DC382D" />
<img alt="Docker" src="https://img.shields.io/badge/Docker-0f172a?style=flat-square&logo=docker&logoColor=2496ED" />
</sub>

**Problem —** Academic operations involve many roles acting on overlapping data, so every action must respect who can do what, and where.

**Approach**
- Scope-aware authorization for academic and administrative operations
- Curriculum proposals, course offerings and approval flows
- Faculty allocation, timetable changes and academic-year rollover
- Dashboards and audit-oriented actions for traceability

<!-- REPLACE: add a repo link here once confirmed -->

<!-- ═══════════════════════════ QUALITY ═══════════════════════════ -->

## ◆ Testing & Quality Mindset

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Backend</b><br/>
      <sub>Validation and error-response paths · auth and permission checks · transaction and concurrency edge cases · positive, negative and boundary inputs</sub>
    </td>
    <td width="50%" valign="top">
      <b>Mobile</b><br/>
      <sub>Network interruption and retry · upload cancel and resume · queue persistence across restarts · Android build verification</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Web</b><br/>
      <sub>Form validation and error states · API integration · auth flows · regression checks on existing features</sub>
    </td>
    <td valign="top">
      <b>End-to-end workflows</b><br/>
      <sub>Checkout → payment → stock update · media select → upload → recover → play · proposal → approval → offering</sub>
    </td>
  </tr>
</table>

<!-- ═══════════════════════════ EXPERIENCE ═══════════════════════════ -->

## ◆ Experience

<table>
  <tr>
    <td width="70%">
      <b>Full Stack Developer</b> · KRGY Infotech Pvt Ltd<br/>
      <sub>React & React Native · Python / FastAPI services · REST APIs · PostgreSQL transactional workflows · auth · Docker · debugging</sub>
    </td>
    <td align="right"><sub>Dec 2025 – Present</sub></td>
  </tr>
  <tr>
    <td>
      <b>Mobile Application Developer</b> · Maxzen Tech<br/>
      <sub>React Native · reusable components · API integration · Android builds · Git-based development</sub>
    </td>
    <td align="right"><sub>Jun 2024 – Nov 2025</sub></td>
  </tr>
</table>

## ◆ Certifications & Education

<p>
  <img alt="PCAP Certified Associate Python Programmer" src="https://img.shields.io/badge/PCAP-Python_Institute-1e293b?style=flat-square&logo=python&logoColor=FFD43B" />
  <img alt="AWS Certified Cloud Practitioner" src="https://img.shields.io/badge/AWS-Cloud_Practitioner-1e293b?style=flat-square&logo=amazonwebservices&logoColor=FF9900" />
  <img alt="SQL Developer Certificate, Infosys Springboard" src="https://img.shields.io/badge/SQL_Developer-Infosys_Springboard-1e293b?style=flat-square&logo=postgresql&logoColor=7dd3fc" />
</p>

🎓 **B.Tech, Computer Science** — Aditya College of Engineering and Technology <sub>· 2020 – 2024</sub>

<!-- ═══════════════════════════ STATS ═══════════════════════════ -->

## ◆ GitHub Activity

<p align="center">
  <img height="165" alt="GitHub statistics for kasi868" src="https://github-readme-stats.vercel.app/api?username=kasi868&show_icons=true&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=22d3ee&text_color=cbd5e1&count_private=true" />
  <img height="165" alt="Contribution streak for kasi868" src="https://streak-stats.demolab.com?user=kasi868&hide_border=true&background=0b1220&ring=22d3ee&fire=22d3ee&currStreakLabel=22d3ee&sideLabels=cbd5e1&dates=94a3b8&currStreakNum=e2e8f0&sideNums=e2e8f0" />
</p>

<p align="center"><sub>Public-repo activity only — much of my professional work lives in private repositories.</sub></p>

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:0e7490,50:0f2a44,100:0b1220" />
