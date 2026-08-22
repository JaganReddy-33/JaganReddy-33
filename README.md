<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0D0C,50:1F3864,100:38C6A6&height=250&section=header&text=Jaganmohan%20Reddy&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Full%20Stack%20Developer%20%C2%B7%20Java%20Backend%20Developer&descAlignY=52&descSize=19"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=38C6A6&center=true&vCenter=true&width=800&height=50&lines=Building+real+systems%2C+not+tutorial+clones;MERN+Stack+%2B+Java+Backend+Engineering;Currently+deep+in%3A+JDBC+%C2%B7+SQL+%C2%B7+Spring+Boot;Fixing+race+conditions+is+my+idea+of+fun"/>

<br/>

<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-38C6A6?style=for-the-badge&logo=vercel&logoColor=0B0D0C"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=JaganReddy-33&style=for-the-badge&color=38C6A6&label=PROFILE+VIEWS"/>

</div>

<br/>

## 🧑‍💻 About Me

<img align="right" width="260" src="https://skillicons.dev/icons?i=java,js,react,nodejs,express,mongodb,mysql&theme=dark&perline=4"/>

I'm **Jaganmohan Reddy** — a 2026 Electronics & Communication Engineering graduate who taught myself full-stack development, then went looking for the parts tutorials skip.

I started with the **MERN stack**, building complete apps end to end. Now I'm going deeper into **Java backend engineering** — how reliable systems are actually built: transactions, concurrency, layered architecture, not just "make it run."

```text
MERN Stack → Full Stack Dev → Backend Engineering → Java + JDBC + SQL → Spring Boot
```

**What I actually care about:**
- 🧩 Understanding *why* a design decision was made, not copying it
- 🔒 Concurrency-safe, race-condition-aware systems
- 🧪 Testing failure paths, not just the happy path
- 📖 Code someone else can read without asking me what it does

<br clear="right"/>

<div align="center">

`✨ I don't build projects to say I built them — I build them to learn how real systems work ✨`

</div>

<br/>

## 🚀 Featured Project

<div align="center">

### 🎟️ Seatline — Atomic Booking Engine
**A concurrency-safe, real-time seat booking system**

<a href="https://github.com/JaganReddy-33/Seatline_Atomic-Booking-Engine">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=JaganReddy-33&repo=Seatline_Atomic-Booking-Engine&theme=tokyonight&hide_border=true&bg_color=00000000"/>
</a>

<img src="https://img.shields.io/badge/React-38C6A6?style=flat-square&logo=react&logoColor=0B0D0C"/>
<img src="https://img.shields.io/badge/Node.js-38C6A6?style=flat-square&logo=nodedotjs&logoColor=0B0D0C"/>
<img src="https://img.shields.io/badge/MongoDB-38C6A6?style=flat-square&logo=mongodb&logoColor=0B0D0C"/>
<img src="https://img.shields.io/badge/Socket.IO-38C6A6?style=flat-square&logo=socketdotio&logoColor=0B0D0C"/>
<img src="https://img.shields.io/badge/JWT-38C6A6?style=flat-square&logo=jsonwebtokens&logoColor=0B0D0C"/>

</div>

> **The problem:** what happens when many users try to book the same seat at the exact same instant?
> A naive check-then-write flow lets two requests both see "available" before either updates it. Seatline fixes this at the **database layer**, not with a frontend patch.

| Area | What's implemented |
|---|---|
| ⚛️ Atomicity | Single atomic MongoDB `findOneAndUpdate` — no read/write gap to race |
| 🔑 Idempotency | Duplicate-click and retry-safe booking keys |
| 📡 Real-time | Socket.IO — every connected client updates instantly |
| 🔐 Auth | JWT with role-based organizer access |
| 🧪 Proof | Custom load test simulating concurrent bookings — verified, not assumed |

```
Client → Auth → Booking API → Atomic DB Operation ──┬── Booking confirmed
                                                      └── Conflict rejected → live update to all clients
```

<div align="center">
<sub><b>Not:</b> "user clicked → seat booked."&nbsp;&nbsp;<b>Actually:</b> "many requests → one valid state → predictable result."</sub>
</div>

<br/>

## 🧠 Current Engineering Focus

| Area | Exploring |
|---|---|
| ☕ Java | OOP, Collections, Exception Handling |
| 🔌 JDBC | Connections, PreparedStatement, Transactions |
| 🗄️ SQL | Joins, Subqueries, Aggregation, Schema Design |
| 🏗️ Architecture | DAO → Service → Controller layering |
| 🚀 Next up | Spring Boot, production REST APIs |

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=java,js,c&theme=dark"/>

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,html,css,tailwind,bootstrap&theme=dark"/>

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express&theme=dark"/>

**Databases**
<br/>
<img src="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark"/>

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman&theme=dark"/>

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JaganReddy-33&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JaganReddy-33&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000" height="165"/>

<img src="https://streak-stats.demolab.com/?user=JaganReddy-33&theme=tokyonight&hide_border=true&background=00000000&stroke=38C6A6&ring=38C6A6&fire=F2A93B&currStreakLabel=38C6A6"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=JaganReddy-33&theme=tokyo-night&hide_border=true&bg_color=00000000&line=38C6A6&color=38C6A6" width="95%"/>

</div>

<details>
<summary><sub>⚠️ If any card above shows broken — click for the fix</sub></summary>
<br/>

These pull live data from free, shared public servers used by millions of GitHub profiles. Two things cause failures:

1. **Wrong host** — streak-stats moved off `herokuapp.com` (Heroku ended free hosting in 2022) to `streak-stats.demolab.com`, which is what's used above. If it's still broken, the domain may have changed again — search "`github-readme-streak-stats`" for the current official host.
2. **Server overload** — the shared Vercel instances rate-limit under heavy global traffic. Permanent fix: fork [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats), deploy your fork to your own Vercel account (free, ~3 min), then swap `github-readme-stats.vercel.app` for your own URL above.

</details>

<br/>

## 🐍 Contribution Activity

<div align="center">
<img src="https://raw.githubusercontent.com/JaganReddy-33/JaganReddy-33/output/github-contribution-grid-snake-dark.svg"/>
</div>

<details>
<summary><sub>⚙️ One-time setup (~3 min) — required for the animation above to appear</sub></summary>
<br/>

1. In this repo: **Settings → Secrets and variables → Actions**
2. Create `.github/workflows/snake.yml`:

```yaml
name: Generate Snake
on:
  schedule: [{cron: "0 */6 * * *"}]
  workflow_dispatch:
  push: {branches: ["main"]}
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: JaganReddy-33
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Commit it, then run it once manually from the **Actions** tab. After it finishes, the snake above renders your real commit history.

</details>

<br/>

## 🏆 Achievements

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=JaganReddy-33&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=6&margin-w=10"/>
</div>

<br/>

## 💼 Open to Opportunities

<div align="center">

**Full Stack Developer · Java Backend Developer · Backend Engineer**

I'm looking for a role where I can contribute, learn from engineers ahead of me, and grow into someone who builds systems that hold up under real load — not just in a demo.

<br/>

<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://img.shields.io/badge/🌐_Portfolio-38C6A6?style=for-the-badge&logoColor=0B0D0C"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38C6A6,50:1F3864,100:0B0D0C&height=120&section=footer"/>
