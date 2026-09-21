import os

content = """<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,20&height=180&section=header&text=KIM%20HENG%20✦%20SE7EN&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" alt="Header" />

  <!-- Animated Typing Text -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&multiline=true&width=620&height=90&lines=Hey+there!+I%27m+Kim+Heng+(SE7EN)+%E2%9C%A8;Full-Stack+Developer+%26+Tech+Enthusiast+%E2%98%95;Building+Scalable+Web+Apps+%26+POS+Systems+%F0%9F%9A%80;Lo-Fi+vibes+%26+late-night+coding...%F0%9F%8E%A7" alt="Typing SVG" />
  </a>

  <p align="center">
    <samp>
      ⚡ <b>"Turning caffeine into clean code & modern solutions"</b> ⚡
      <br>
      📍 Based in Phnom Penh, Cambodia 🇰🇭
    </samp>
  </p>

  <!-- Modern Social Badges -->
  <p align="center">
    <a href="https://t.me/Kim_Heng01" target="_blank">
      <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
    </a>
    <a href="https://web.facebook.com/kimheng.seng.902819/" target="_blank">
      <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
    </a>
    <a href="https://www.youtube.com/@SE7EN168-VC" target="_blank">
      <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
    </a>
    <a href="mailto:kimheng0361@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
    <a href="https://github.com/SE7EN-01?tab=followers">
      <img src="https://img.shields.io/github/followers/SE7EN-01?label=Followers&style=for-the-badge&color=24292e&logo=github" alt="Followers" />
    </a>
  </p>

</div>

---

### 👨‍💻 About Me

```typescript
const SE7EN = {
    name: "Kim Heng",
    alias: "SE7EN",
    role: "Full-Stack Web Developer",
    location: "Phnom Penh, Cambodia 🇰🇭",
    specialties: [
        "Modern Web Apps (Laravel & Vue / Blade)",
        "Database Architecture & Optimization (PostgreSQL / MySQL)",
        "Fintech & Payment Gateway Integration (Bakong KHQR)"
    ],
    passion: ["Clean Architecture", "UI/UX Aesthetics", "Problem Solving"],
    currentObsession: "Mastering Full-Stack Ecosystems & High-Performance Systems",
    quote: "Talk is cheap. Show me the code."
};
```

---

### 🛠️ Arsenal & Tech Stack

<div align="center">

  <!-- Core Tech Stack via skillicons.dev -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,ts,php,laravel,vue,react,tailwind,bootstrap,mysql,postgres,git,github,vscode,postman,py,cpp&perline=9&theme=dark" alt="Tech Stack" />
  </a>

</div>

<br/>

| Category | Technologies & Tools |
| :--- | :--- |
| **Backend** | `PHP 8.x`, `Laravel 11/12`, `Python`, `C++`, `RESTful APIs` |
| **Frontend** | `JavaScript (ES6+)`, `Vue.js`, `Alpine.js`, `Tailwind CSS`, `HTML5 / CSS3` |
| **Databases** | `PostgreSQL`, `MySQL` |
| **Payments & Integration** | `Bakong KHQR (NBC)`, `Webhook Handling`, `Payment Gateways` |
| **Tools & Workflow** | `Git`, `GitHub`, `VS Code`, `Postman`, `TablePlus`, `Composer`, `NPM` |

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SE7EN-01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=a855f7&text_color=94a3b8" height="175" alt="GitHub Stats" />
  <img src="https://streak-stats.demolab.com?user=SE7EN-01&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=f43f5e&currStreakLabel=38bdf8" height="175" alt="Streak Stats" />
</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SE7EN-01&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8" height="165" alt="Top Languages" />
</div>

---

### ☕ What I'm Currently Working On

- 💼 **Bong Heng Cafe POS & Inventory System**: Advanced POS with Table Floor Plan, Real-time BOM deductions, and Bakong KHQR integration.
- 💳 **Fintech Integrations**: Seamless transaction workflows with Cambodian payment rails (Bakong).
- 🚀 **Next-Gen Web Apps**: Creating sleek, modern, fast web applications with Laravel & modern UI.

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,20&height=100&section=footer" width="100%" alt="Footer" />
</div>
"""

out_dir = r"D:\RPITSB\SE7EN-01"
os.makedirs(out_dir, exist_ok=True)
out_file = os.path.join(out_dir, "README.md")
with open(out_file, "w", encoding="utf-8") as f:
    f.write(content)

print(f"Successfully updated {out_file}")
