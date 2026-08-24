<div align="center">
<img src="https://vercel.app"/>
<img src="https://demolab.com"/>

<br/>
<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://shields.io"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com"/>
</div>
<br/>

## 🧑‍💻 About Me
<img align="right" width="260" src="https://skillicons.dev"/>

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

<a href="https://github.com">
<img src="https://vercel.app"/>
</a>

<img src="https://shields.io"/>
<img src="https://shields.io"/>
<img src="https://shields.io"/>
<img src="https://shields.io"/>
<img src="https://shields.io"/>

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

Use code with caution.Client → Auth → Booking API → Atomic DB Operation ──┬── Booking confirmed└── Conflict rejected → live update to all clients
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
<img src="https://skillicons.dev"/>

**Frontend**
<br/>
<img src="https://skillicons.dev"/>

**Backend**
<br/>
<img src="https://skillicons.dev"/>

**Databases**
<br/>
<img src="https://skillicons.dev"/>

**Tools**
<br/>
<img src="https://skillicons.dev"/>

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://vercel.app" height="165"/>
<img src="https://vercel.app" height="165"/>

<img src="https://vercel.app" height="165"/>

<img src="https://vercel.app" width="95%"/>

</div>

<br/>

## 🐍 Contribution Activity

<div align="center">
<img src="https://githubusercontent.com" alt="GitHub Contribution Snake"/>
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
          GITHUB_TOKEN: \${{ secrets.GITHUB_TOKEN }}
```

3. Commit it, then run it once manually from the **Actions** tab. After it finishes, the snake above renders your real commit history.

</details>

<br/>

## 🏆 Achievements

<div align="center">
<img src="https://soulteary.com" alt="GitHub Profile Trophies"/>
</div>

<br/>

## 💼 Open to Opportunities

<div align="center">

**Full Stack Developer · Java Backend Developer · Backend Engineer**

I'm looking for a role where I can contribute, learn from engineers ahead of me, and grow into someone who builds systems that hold up under real load — not just in a demo.

<br/>

<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://shields.io"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38C6A6,50:1F3864,100:0B0D0C&height=120&section=footer"/>
