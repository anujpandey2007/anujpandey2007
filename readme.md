<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Anuj%20Pandey&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=B.Tech%20CSE%20%7C%20Data%20Science%20%7C%20Future%20Software%20Developer&descAlignY=58&descColor=a0a8d0&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=7B8CDE&center=true&vCenter=true&multiline=false&width=650&lines=First%2C+solve+the+problem.+Then%2C+write+the+code.;Code+is+poetry+written+for+machines.;Every+expert+was+once+a+beginner.;Build+things+that+matter.)](https://git.io/typing-svg)

</div>

---

<div align="center">

<img src="https://img.shields.io/badge/Status-Actively%20Learning-brightgreen?style=for-the-badge&logo=bookstack&logoColor=white"/>
<img src="https://img.shields.io/badge/Degree-B.Tech%20CSE%20(Data%20Science)-blue?style=for-the-badge&logo=graduation-cap&logoColor=white"/>
<img src="https://img.shields.io/badge/Year-See%20Progress%20Below-orange?style=for-the-badge&logo=calendar&logoColor=white"/>

</div>

---

## About Me

```python
class AnujPandey:
    name           = "Anuj Pandey"
    degree         = "B.Tech — Computer Science & Engineering"
    specialization = "Data Science"
    college        = "GL Bajaj Institute of Technology and Management, Greater Noida"
    goal           = "Software Developer with in-depth knowledge"

    timeline = {
        "2024–2025": "1st Year — Building Foundations",
        "2025–2026": "2nd Year — Exploring Core CS + Data Science",
        "2026–2027": "3rd Year — Projects, Internships & Real-World Experience",
        "2027–2028": "4th Year — Advanced Specialization & Placement Prep",
        "2028+":     "Passout — Software Developer, Full Throttle"
    }

    currently_exploring = [
        "Programming Languages & their Paradigms",
        "Data Structures & Algorithms",
        "Python for Data Science",
        "Software Engineering Principles"
    ]

    def life_philosophy(self):
        return "Write code that's not just correct — make it clean, scalable, and meaningful."
```

---

## Academic Journey

<div align="center">

| Year | Period | Phase | Status |
|------|--------|-------|--------|
| <img src="https://img.shields.io/badge/Year%201-2024--2025-4a90d9?style=flat-square"/> | 2024 – 2025 | Foundation & Discovery | `Completed` |
| <img src="https://img.shields.io/badge/Year%202-2025--2026-7b8cde?style=flat-square"/> | Aug 2025 – 2026 | Core CS + Data Science Concepts | `In Progress` |
| <img src="https://img.shields.io/badge/Year%203-2026--2027-9b6dde?style=flat-square"/> | 2026 – 2027 | Projects, Internships & Depth | `Upcoming` |
| <img src="https://img.shields.io/badge/Year%204-2027--2028-c45ae3?style=flat-square"/> | 2027 – 2028 | Mastery, Leadership & Placement | `Upcoming` |
| <img src="https://img.shields.io/badge/Passout-2028+-ff6b9d?style=flat-square"/> | 2028+ | Software Developer — Full Career | `The Goal` |

</div>

> **Automation Note:** This timeline auto-highlights the current year. If you'd like this README to update dynamically, see the [GitHub Actions workflow](#automated-year-tracker) section below.

---

## Tech Stack

<div align="center">

### Languages I'm Exploring

<img src="https://skillicons.dev/icons?i=python,c,cpp,java&theme=dark"/>

### Tools & Technologies

<img src="https://skillicons.dev/icons?i=git,github,vscode,linux&theme=dark"/>

### On the Radar

<img src="https://skillicons.dev/icons?i=tensorflow,sklearn,pandas,numpy&theme=dark"/>

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=anujpandey2007&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7b8cde&icon_color=a78bfa&text_color=c9d1d9&rank_icon=github" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anujpandey2007&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7b8cde&text_color=c9d1d9" height="180"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=anujpandey2007&theme=tokyonight&hide_border=true&background=0d1117&stroke=7b8cde&ring=a78bfa&fire=ff6b9d&currStreakLabel=c9d1d9" width="60%"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=anujpandey2007&bg_color=0d1117&color=7b8cde&line=a78bfa&point=ff6b9d&area=true&hide_border=true" width="100%"/>

</div>

---

## What Drives Me

<div align="center">

> *"The best software developers are not the ones who know everything — they are the ones who never stop learning."*

> *"In-depth knowledge is not a destination. It is the habit of going one level deeper than everyone else."*

</div>

My goal is not just to build software — it is to understand it completely. Every language I learn, every algorithm I study, and every project I build is a step toward becoming a developer who can create systems that are elegant, efficient, and impactful.

---

## Automated Year Tracker

<a name="automated-year-tracker"></a>

Want this README to automatically highlight your current academic year? Here's a simple GitHub Actions script you can add to your repo:

**File:** `.github/workflows/update-year.yml`

```yaml
name: Update Academic Year Badge

on:
  schedule:
    - cron: '0 0 1 8 *'
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - name: Update current year marker
        run: |
          CURRENT_YEAR=$(date +%Y)
          echo "Academic year script running for $CURRENT_YEAR"

      - name: Commit changes
        run: |
          git config --local user.email "action@github.com"
          git config --local user.name "GitHub Action"
          git add README.md
          git diff --staged --quiet || git commit -m "chore: auto-update academic year badge"
          git push
```

> This workflow runs every August 1st — exactly when your new academic year begins — so your README stays current without manual edits.

---

## Connect With Me

<div align="center">

<a href="https://github.com/anujpandey2007">
  <img src="https://img.shields.io/badge/GitHub-anujpandey2007-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
&nbsp;
<a href="https://in.linkedin.com/in/anuj-pandey-5585093b8">
  <img src="https://img.shields.io/badge/LinkedIn-Anuj%20Pandey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&text=Building%20one%20commit%20at%20a%20time&fontSize=18&fontColor=a0a8d0&fontAlignY=65" width="100%"/>

</div>