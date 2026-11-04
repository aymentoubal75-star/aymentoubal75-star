from pathlib import Path

readme = r'''<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:070B18,35:21105A,70:075985,100:00D4C7&height=220&section=header&text=Aymen%20Toubal&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=Web%20Developer%20%7C%20Tech%20Enthusiast&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="Aymen Toubal cyber banner" />

### `DREAM • CODE • INNOVATE`

**Web Developer | Tech Enthusiast**  
*Turning ideas into useful digital experiences.*

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-Visit%20Website-00D4C7?style=for-the-badge&logo=vercel&logoColor=white)](https://aymen-portfolio-rio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aymen-toubal)
[![Email](https://img.shields.io/badge/EMAIL-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:toubalaymene@gmail.com)

📍 **Médéa, Algeria** 🇩🇿 · **Pronouns:** he/him

</div>

---

## 👨‍💻 About Me | À propos

**EN** — Hi! I'm **Aymen Toubal**, a Web Developer from Algeria interested in creating modern websites and digital solutions. I enjoy learning new technologies, building practical projects, and turning ideas into reality.

**FR** — Salut ! Je suis **Aymen Toubal**, développeur web algérien. Je m'intéresse à la création de sites modernes et de solutions numériques. J'aime apprendre de nouvelles technologies, développer des projets pratiques et transformer des idées en réalisations concrètes.

- 🌐 Focus: Web Development
- 📱 Exploring: Mobile Development & Flutter
- 🎨 Interests: UI/UX, responsive design, and user-friendly experiences
- 🤝 Member of the **[@masaar-project](https://github.com/masaar-project)** community
- 🌱 Always learning and improving

---

## ⚡ Tech Stack | Technologies

<div align="center">

**Web Development**

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,nodejs&theme=dark" alt="Web development technologies" />

**App Development & Programming**

<img src="https://skillicons.dev/icons?i=flutter,dart,python,java&theme=dark" alt="App development and programming technologies" />

**Tools & Platforms**

<img src="https://skillicons.dev/icons?i=git,github,vscode,figma,firebase,supabase,androidstudio&theme=dark" alt="Development tools and platforms" />

</div>

---

## 🚀 Featured Projects | Projets

| Project | Description | Link |
|---|---|---|
| **MASSAR** | A volunteering platform connecting young people with associations and opportunities. | [GitHub repository](https://github.com/masaar-project/massar-website) |
| **Aymen Portfolio** | My personal portfolio showcasing my work and developer profile. | [Visit website](https://aymen-portfolio-rio.vercel.app/) |
| **Amina Harik Portfolio** | Portfolio website created for a graphic and brand designer. | [Visit website](https://minnaharik.netlify.app/) |
| **DZ Life** | Concept for an all-in-one Algerian services application. | *Concept / in development* |
| **Aymen Grade Calculator** | Student-focused grade and average calculator concept. | *Project link coming soon* |

---

## 📊 GitHub Analytics | Statistiques

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=aymentoubal75-star&show_icons=true&hide_border=true&bg_color=080B1A&title_color=00D4C7&icon_color=7C3AED&text_color=E6EDF3" alt="GitHub statistics for Aymen Toubal" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aymentoubal75-star&layout=compact&hide_border=true&bg_color=080B1A&title_color=00D4C7&text_color=E6EDF3" alt="Most used programming languages" />

<img width="95%" src="https://streak-stats.demolab.com?user=aymentoubal75-star&theme=tokyonight&hide_border=true&background=080B1A&ring=00D4C7&fire=7C3AED&currStreakLabel=00D4C7" alt="GitHub contribution streak" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=aymentoubal75-star&bg_color=080B1A&color=E6EDF3&line=00D4C7&point=7C3AED&area=true&hide_border=true" alt="GitHub contribution activity graph" />

</div>

---

## 🌐 Find Me Online | Retrouvez-moi

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-aymentoubal75--star-181717?style=for-the-badge&logo=github)](https://github.com/aymentoubal75-star)
[![Organization](https://img.shields.io/badge/Organization-MASSAR-7C3AED?style=for-the-badge&logo=github)](https://github.com/masaar-project)
[![Portfolio](https://img.shields.io/badge/Portfolio-aymen--portfolio-00A6A6?style=for-the-badge&logo=vercel&logoColor=white)](https://aymen-portfolio-rio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aymen%20Toubal-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/aymen-toubal)
[![Email](https://img.shields.io/badge/Email-Say%20Hello-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:toubalaymene@gmail.com)

</div>

---

<div align="center">

### `Code. Create. Innovate.`

**Aymen Toubal** · *Made with curiosity in Algeria* 🇩🇿

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4C7,50:075985,100:21105A&height=100&section=footer" width="100%" alt="Cyber footer" />

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Updated {path} ({path.stat().st_size:,} bytes)")

