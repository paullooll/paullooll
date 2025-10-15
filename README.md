# 👋 Hi, I'm **Richie Paul Aquiño**

Welcome to my GitHub profile! I’m an enthusiastic **Information Technology student** and **developer** passionate about building seamless, high-performance **web and mobile applications**. I enjoy turning creative ideas into functional, visually appealing, and impactful digital solutions.

---

## 🚀 About Me

* 🎓 Pursuing a degree in **Information Technology**
* 💻 Focused on **full-stack web** and **mobile app development**
* 🧠 Continuously exploring new frameworks, tools, and architectures
* 🌱 Currently learning **advanced backend design patterns** and **cloud-native development**
* 🎯 Goal: **Build innovative, scalable apps** and contribute to **open-source projects**

---

## 🛠️ Tech Stack

**Languages:**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge\&logo=dart\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)

**Frameworks & Libraries:**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge\&logo=flutter\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge\&logo=nextdotjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge\&logo=nestjs\&logoColor=white)

**Tools & Platforms:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge\&logo=firebase\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=paullooll&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" height="160" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=paullooll&theme=tokyonight&hide_border=true" height="160" alt="GitHub Streak Stats" />
</div>

---

## 🔥 Contribution Visuals (Animated + Heatmap)

I added two visual, dynamic representations of activity to this README:

### 1) Animated Contribution Snake (fun, eye-catching)

This creates an animated GIF that "snakes" through your contribution grid — a playful way to showcase momentum.

**How to enable it (recommended):**

1. Add the `Platane/snk` GitHub Action (or an equivalent) to your repository to generate `assets/contrib-snake.gif` on every push.
2. Include the generated GIF in your README like this:

```markdown
![Contribution Snake](assets/contrib-snake.gif)
```

**Example workflow (`.github/workflows/snake.yml`):**

```yaml
name: Generate contribution snake
on:
  push:
    branches: [ main ]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Generate contribution snake
        uses: platane/snk@v1
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          width: 860
          height: 200
          output: assets/contrib-snake.gif
      - name: Commit generated GIF
        run: |
          git config --local user.email "github-actions[bot]@users.noreply.github.com"
          git config --local user.name "github-actions[bot]"
          git add assets/contrib-snake.gif || true
          git commit -m "chore: update contribution snake" || true
          git push || true
```

> Note: `platane/snk` is a well-known action for this purpose; if you prefer another action/tool you can swap it in.

---

### 2) Activity Heatmap + Animated Activity Graph

These show recent contributions and an activity timeline.

**Heatmap (static SVG)** — quick and reliable:

```markdown
![Contribution Heatmap](https://ghchart.rshah.org/paullooll)
```

**Animated activity graph (area + activity)** — uses the `activity-graph` service (commonly used):

```markdown
![Activity Graph](https://activity-graph.herokuapp.com/graph?username=paullooll&area=true&hide_border=true&theme=gruvbox)
```

> If the hosted `activity-graph` or `ghchart` service is unavailable in the future, you can self-host the generated SVGs/assets or use alternative services/APIs.

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=paullooll&theme=gruvbox&no-frame=true&row=1&column=7" alt="GitHub Trophies" />
</div>

---

## 🧩 Featured Projects

* 🎸 [**ChorDefine**](https://github.com/ronmagpantay1/chordefine) — A mobile application for **guitar chord practice** using computer vision and audio recognition.
* 🧠 [**Face Recognition Attendance Scanner**](https://github.com/paullooll/FaceRecognitionAttendanceSystem) — A facial recognition-based attendance system for schools or organizations.
* 💬 [**Chatbot Application**](https://github.com/paullooll/cc206_chatbot_application) — A Flutter chatbot app that simulates real-time conversations.
* 🛒 [**Hyunwel Blackmarket**](https://github.com/paullooll/cc206_chatbot_application) — A secure e-commerce app built with Flutter and Firebase, featuring authentication and real-time updates.

---

## 🔗 Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/richie-paul-aquiño-2bb196265" target="_blank">
    <img src="https://img.shields.io/badge/-Richie%20Paul%20Aquiño-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

⭐ *Thanks for visiting my profile!*
💡 *Let’s collaborate and build something amazing together!* 🚀

---

## Notes & tips

* Replace every occurrence of `paullooll` in the image URLs with your actual GitHub username if different.
* If you want me to:
  • generate the exact GitHub Action workflow tuned to your repo structure, or
  • switch the visuals to a minimal, static-only setup (no Actions),
  tell me which option and I’ll update the README accordingly.
