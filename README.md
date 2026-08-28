<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/213760677-e45ca5f7-d1aa-4c2c-91e0-573819287304.gif" width="300"/>

<h1>Hi 👋, I'm Huzefa Khan</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=6C63FF&center=true&vCenter=true&width=500&lines=Software+Developer+%F0%9F%92%BB;Open+Source+Enthusiast+%F0%9F%8C%B1;Always+Learning+New+Things+%F0%9F%9A%80" alt="Typing SVG" />

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:huzefakhan2026@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/huzefa-khan26/)
[![GitHub followers](https://img.shields.io/github/followers/huzefakhan26?label=Follow&style=for-the-badge&logo=github)](https://github.com/huzefakhan26)

</div>

---

### 🚀 About Me

- 🔭 Currently building cool stuff with code
- 🌱 Always learning and exploring new technologies
- 💬 Ask me about anything tech-related
- 📫 Reach me at **huzefakhan2026@gmail.com**
- ⚡ Fun fact: I love turning ideas into working projects

---

### 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=huzefakhan26&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=huzefakhan26&layout=pie&theme=radical&hide_border=true&langs_count=8"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=huzefakhan26&theme=radical&hide_border=true" alt="GitHub Streak"/>
</div>

---

### 🏆 Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=huzefakhan26&theme=radical&no-frame=true&row=1&column=7" />
</div>

---

### 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=huzefakhan26&theme=react-dark&hide_border=true" />
</div>

---

### 🐍 Contribution Snake (Game-style Contribution Graph)

<div align="center">
  <img src="https://raw.githubusercontent.com/huzefakhan26/huzefakhan26/output/github-contribution-grid-snake.svg" alt="snake animation" />
</div>

> ⚙️ **Setup note:** The snake animation above needs a tiny one-time setup in your own repo (it's not automatic). See **"Enabling the Snake Game"** below.

---

### 🛠️ Tech Stack

<div align="center">

#### MERN Stack
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

#### Languages & Databases
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

#### Other Tools
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

*(Feel free to add/remove badges to match your exact skill set — [shields.io](https://shields.io) has hundreds more logos.)*

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=huzefakhan26&color=6c63ff&style=flat)

**Thanks for visiting my profile! Feel free to connect 🤝**

</div>

---


name: generate snake animation

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: huzefakhan26
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

