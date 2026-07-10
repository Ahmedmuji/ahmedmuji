<!--
  ANIMATED GITHUB PROFILE README
  ================================
  HOW TO USE:
  1. Create a new repo with the SAME name as your GitHub username
     (e.g. if your username is "johndoe", repo must be "johndoe/johndoe")
  2. Put this file in it as README.md — GitHub will auto-display it on your profile.
  3. Find/replace every "YOUR_USERNAME" with your actual GitHub username.
  4. Replace [Your Name], [Your Title], links, and skill lists below.
  5. For the snake animation at the bottom, follow the GitHub Action setup
     instructions in the comment above that section (one-time, ~2 min setup).
-->

<div align="center">

<!-- Animated wave header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:4A00E0&height=220&section=header&text=Hi%20There,%20I'm%20Ahmed%20Mujtaba%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20•%20Open%20Source%20Enthusiast%20•%20Lifelong%20Learner&descAlignY=55&descSize=18" width="100%"/>

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&duration=3000&pause=800&color=8E2DE2&center=true&vCenter=true&width=600&lines=Welcome+to+my+profile!;I+build+things+for+the+web+%26+beyond;Always+learning%2C+always+shipping;Let's+build+something+great+together." alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
<a href="https://linkedin.com/in/YOUR_LINKEDIN" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/YOUR_TWITTER" target="_blank">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="mailto:YOUR_EMAIL@example.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://YOUR_PORTFOLIO_SITE.com" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<br/><br/>

<!-- Profile view counter -->
<img src="https://komarev.com/ghpvc/?username=Ahmed Mujtaba&label=Profile%20Views&color=8E2DE2&style=for-the-badge" alt="profile views" />

</div>

<br/>

## 🚀 About Me

- 🔭 Currently working on **[Your Current Project]**
- 🌱 Currently learning **[New Technology]**
- 👯 Looking to collaborate on **[Type of Projects]**
- 💬 Ask me about **[Your Expertise Areas]**
- ⚡ Fun fact: **[Something interesting about you]**

<br/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<!-- Edit the badge list above freely — icon slugs from simpleicons.org work with shields.io -->

</div>

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=8E2DE2&icon_color=8E2DE2"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=8E2DE2&langs_count=8"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=radical&hide_border=true&background=0D1117&ring=8E2DE2&fire=8E2DE2&currStreakLabel=8E2DE2" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=react-dark&hide_border=true&bg_color=0D1117&color=8E2DE2&line=8E2DE2&point=ffffff" width="95%"/>

</div>

<br/>

## 🏆 Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=radical&no-frame=true&no-bg=true&margin-w=15&row=1" />
</div>

<br/>

<!--
  🐍 CONTRIBUTION SNAKE ANIMATION (eats your contribution graph)
  One-time setup (2 min):
  1. In your profile repo, go to Settings > Secrets and variables > Actions
  2. Create folder .github/workflows/snake.yml with this content:

      name: Generate Snake
      on:
        schedule:
          - cron: "0 0 * * *"
        workflow_dispatch: {}
        push:
          branches: [ main ]
      jobs:
        generate:
          runs-on: ubuntu-latest
          permissions:
            contents: write
          steps:
            - uses: Platane/snk/svg-only@v3
              with:
                github_user_name: YOUR_USERNAME
                outputs: |
                  dist/github-contribution-grid-snake.svg
                  dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            - uses: crazy-max/ghaction-github-pages@v4
              with:
                target_branch: output
                build_dir: dist
              env:
                GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Push it, let the Action run once, then it self-updates daily.
-->

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg" alt="snake animation" width="95%"/>
</div>

<br/>

## 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github-compact&hide_border=true" width="95%"/>
</div>

<br/>

<div align="center">

### 💜 Thanks for stopping by!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4A00E0,100:8E2DE2&height=120&section=footer" width="100%"/>

</div>
