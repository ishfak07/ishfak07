<!-- README.md for Faizul Ishfak (updated) -->

<!-- =========================
     INLINE SVG ANIMATED HEADER
     (No external clickable images)
   ========================= -->
<div align="center">

<!-- Animated SVG banner -->
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" role="img" aria-label="Faizul Ishfak header">
  <defs>
    <linearGradient id="gradA" x1="0" x2="1">
      <stop offset="0%" stop-color="#1e3a8a"/>
      <stop offset="50%" stop-color="#6d28d9"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
    <filter id="blur">
      <feGaussianBlur stdDeviation="40" result="b"/>
      <feBlend in="SourceGraphic" in2="b"/>
    </filter>
  </defs>

  <!-- background -->
  <rect width="1200" height="220" fill="url(#gradA)" />

  <!-- animated soft blobs -->
  <g fill="#ffffff" opacity="0.08" filter="url(#blur)">
    <circle cx="150" cy="60" r="70">
      <animate attributeName="cx" dur="14s" values="150;1050;150" repeatCount="indefinite"/>
    </circle>
    <circle cx="400" cy="120" r="55">
      <animate attributeName="cx" dur="9s" values="400;800;400" repeatCount="indefinite"/>
    </circle>
    <circle cx="950" cy="50" r="40">
      <animate attributeName="cx" dur="12s" values="950;200;950" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- main name -->
  <text x="50%" y="84" text-anchor="middle" font-family="Inter, Roboto, Arial, sans-serif" font-size="36" font-weight="700" fill="#ffffff">Faizul Ishfak</text>

  <!-- subtitle -->
  <text x="50%" y="115" text-anchor="middle" font-family="Inter, Roboto, Arial, sans-serif" font-size="14" fill="#ffffff" opacity="0.95">
    Software Engineer | BSc (Hons) Computer Science | MERN • ERP • Agile
  </text>

  <!-- small accent line -->
  <rect x="380" y="132" width="440" height="3" rx="2" fill="#ffffff" opacity="0.12"/>
</svg>

</div>

---

<!-- =========================
     INLINE TAGLINE (safe SVG alternating text)
   ========================= -->
<div align="center" style="margin-top: 12px; margin-bottom: 12px;">
  <svg width="700" height="40" viewBox="0 0 700 40" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <style>
      /* font fallback displayed by GitHub */
      <![CDATA[
        .t { font-family: "Fira Code", "Courier New", monospace; font-size:14px; fill:#0f172a; }
      ]]>
    </style>

    <!-- three lines that fade in/out in sequence -->
    <text x="50%" y="25" text-anchor="middle" class="t">
      <tspan id="line1" opacity="1">Software Engineer Intern at Imara Software Solutions</tspan>
      <tspan id="line2" opacity="0" x="50%" dy="20">Building scalable solutions with ❤️</tspan>
      <tspan id="line3" opacity="0" x="50%" dy="20">MERN • ERP • Automation • Testing • Agile</tspan>

      <!-- timing: 0–5s show line1, 5–10s show line2, 10–15s show line3, loop -->
      <animate xlink:href="#line1" attributeName="opacity" values="1;1;0" dur="15s" keyTimes="0;0.33;1" repeatCount="indefinite"/>
      <animate xlink:href="#line2" attributeName="opacity" values="0;1;0" dur="15s" keyTimes="0;0.33;0.66" repeatCount="indefinite"/>
      <animate xlink:href="#line3" attributeName="opacity" values="0;1;1" dur="15s" keyTimes="0.33;0.66;1" repeatCount="indefinite"/>
    </text>
  </svg>
</div>

---

<!-- =========================
     CONTACT / BADGES
   ========================= -->
<p align="center">
  <a href="mailto:memberofpfc20@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/faizul-ishfaque"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://ishfak07.github.io/My_portfol.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-29a?style=for-the-badge&logo=google-chrome&logoColor=white"></a>
  <a href="https://github.com/ishfak07"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-222?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

# 👋 About Me

**M. I. F. Ishfaque** — Software Engineer | BSc (Hons) Computer Science (2nd Lower)  
Puttalam, North Western Province, Sri Lanka — passionate about building reliable web systems, ERP customizations (Frappe), and automation.

**Summary**  
I’m a Computer Science graduate (University of Plymouth, graduation Dec 2025) currently working as a Software Engineer Intern. I enjoy system design, full-stack development (MERN), QA/testing, and continuous improvement of products through automation and teamwork.

---

<!-- =========================
     EDUCATION / CERTIFICATIONS / EXPERIENCE
     Presented as visually distinct cards (table layout)
   ========================= -->

<table width="100%">
  <tr>
    <!-- EDUCATION card -->
    <td valign="top" width="33%" style="padding:8px;">
      <details open>
        <summary><h3>🎓 Education</h3></summary>
        <ul>
          <li><b>University of Plymouth</b> — BSc (Hons) Computer Science (March 2022 - Sep 2025)</li>
          <li><b>NSBM Green University</b> — BSc (Hons) Computer Science (2022 - 2025)</li>
          <li><b>Refresh College</b> — NVQ 4 (Computer Science)</li>
        </ul>
      </details>
    </td>

    <!-- CERTIFICATIONS card -->
    <td valign="top" width="33%" style="padding:8px;">
      <details>
        <summary><h3>📜 Certifications</h3></summary>
        <ul>
          <li>CPICS (NVQ Level 4-like syllabus)</li>
          <li>Computer Application Assistant</li>
          <li>Diploma in Computer Applications</li>
          <li>Graphic & Digital Designing</li>
          <li>Computer Hardware</li>
        </ul>
      </details>
    </td>

    <!-- EXPERIENCE card -->
    <td valign="top" width="33%" style="padding:8px;">
      <details>
        <summary><h3>💼 Experience</h3></summary>
        <p><b>Imara Software Solutions</b> — Software Engineer Intern<br>
        <em>Sep 2025 - Present • Puttalam, Sri Lanka</em></p>
        <ul>
          <li>Contribute to coding, testing and documentation for production features.</li>
          <li>Work with senior engineers to improve feature reliability and performance.</li>
          <li>Participate in sprint planning and peer reviews; strengthen QA coverage.</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

---

## 🛠️ Top Skills

- HTML5, CSS3 (responsive & animations), Vanilla JavaScript
- ReactJS, Node.js, Express, MongoDB (MERN)
- Python, FastAPI/Django, SQL
- Docker, Azure, CI/CD (GitHub Actions)
- ERP (Frappe), System design, QA & testing

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/ishfak07/HireMe" target="_blank">HireMe — Service Provider Platform</a></h4>
      <ul>
        <li>Connects service seekers with verified providers — OTP verification & real-time notifications.</li>
        <li>Stack: Node.js, Express, Socket.IO, MongoDB.</li>
      </ul>
      <p><small>Key: Authentication • Real-time • Admin controls</small></p>
    </td>

    <td width="50%" valign="top">
      <h4><a href="https://github.com/ishfak07/SmartRise-Puttalam" target="_blank">SmartRise Puttalam — Smart City</a></h4>
      <ul>
        <li>Responsive site showcasing smart city ideas and local services.</li>
        <li>Stack: React, Tailwind CSS.</li>
      </ul>
      <p><small>Key: UX • Responsive • Prototyping</small></p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/ishfak07/Sweet-Delights" target="_blank">Sweet Delights — Bakery Website Prototype</a></h4>
      <ul>
        <li>Requirement elicitation and ordering workflow prototype.</li>
        <li>Focus: Product listing, ordering & delivery flow.</li>
      </ul>
    </td>

    <td width="50%" valign="top">
      <h4><a href="https://github.com/ishfak07/Quite-Mate" target="_blank">Quite Mate — Smoke Tracking App</a></h4>
      <ul>
        <li>Mobile app built with Flutter & Firebase — user analytics and reminders.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📊 GitHub Analytics & Activity

<!-- Aligned stat cards -->
<table align="center" width="100%">
  <tr>
    <td align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=ishfak07&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" width="320"/>
    </td>
    <td align="center">
      <img src="https://streak-stats.demolab.com?user=ishfak07&theme=tokyonight&hide_border=true" alt="Streak stats" width="320"/>
    </td>
    <td align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ishfak07&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" width="320"/>
    </td>
  </tr>
</table>

<!-- Contribution calendar (stable service) -->
<p align="center">
  <img src="https://ghchart.rshah.org/ishfak07" alt="Contribution chart for ishfak07" width="90%"/>
</p>

---

## 📬 Contact

- Email: memberofpfc20@gmail.com  
- LinkedIn: https://www.linkedin.com/in/faizul-ishfaque  
- Portfolio: https://ishfak07.github.io/My_portfol.io/

---

<p align="center"><b>✨ Keep learning. Keep building. Keep shipping. 🚀</b></p>
