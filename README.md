<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0D0C,50:1F3864,100:38C6A6&height=240&section=header&text=Jaganmohan%20Reddy&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full%20Stack%20Developer%20%C2%B7%20Java%20Backend%20Developer&descAlignY=56&descSize=18"/>

<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-38C6A6?style=for-the-badge&logo=vercel&logoColor=0B0D0C"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

```
$ whoami
```

**Jaganmohan Reddy** — 2026 Electronics & Communication Engineering graduate who taught himself full-stack development, then went looking for the parts tutorials skip.

Started with the **MERN stack**, shipping complete applications end to end. Now going deeper into **Java backend engineering** — how reliable systems actually get built: atomicity, transactions, concurrency, layered architecture. Not just "make it run."

```
$ cat priorities.txt
```

```
› understand WHY a design decision was made — not copy it blindly
› build concurrency-safe, race-condition-aware systems
› test the failure paths, not just the happy path
› write code the next engineer can read without asking me questions
```

<div align="center">

<sub>I don't build projects to say I built them — I build them to learn how real systems work.</sub>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12&height=2" width="100%"/>

## `⟶` featured build

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

```
$ cat the-problem.md
```

> What happens when many users try to book the same seat at the exact same instant?
> A naive check-then-write flow lets two requests both see "available" before either updates it.
> Seatline fixes this at the **database layer** — not with a frontend patch.

| area | what's actually implemented |
|---|---|
| ⚛️ atomicity | single atomic MongoDB `findOneAndUpdate` — zero read/write gap to exploit |
| 🔑 idempotency | duplicate-click and network-retry-safe booking keys |
| 📡 real-time | Socket.IO — every connected client updates the instant a seat changes |
| 🔐 auth | JWT with role-based organizer access |
| 🧪 proof | custom load test simulating concurrent bookings — verified, not assumed |

```
client → auth → booking service → atomic db operation ──┬── booking confirmed
                                                          └── conflict rejected → live sync
```

<div align="center">
<sub><b>not</b> "user clicked → seat booked" &nbsp;·&nbsp; <b>actually</b> "many requests → one valid state → predictable result"</sub>
</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12&height=2" width="100%"/>

## `⟶` currently studying

| area | focus |
|---|---|
| ☕ java | OOP, collections, exception handling |
| 🔌 jdbc | connections, prepared statements, transactions |
| 🗄️ sql | joins, subqueries, aggregation, schema design |
| 🏗️ architecture | DAO → service → controller layering |
| 🚀 next | Spring Boot, production REST APIs |

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12&height=2" width="100%"/>

## `⟶` stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,js,c,react,html,css,tailwind,bootstrap,nodejs,express,mongodb,mysql,git,github,vscode,postman&theme=dark&perline=8"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12&height=2" width="100%"/>

## `⟶` activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JaganReddy-33&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JaganReddy-33&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000" height="165"/>

<img src="https://streak-stats.demolab.com/?user=JaganReddy-33&theme=tokyonight&hide_border=true&background=00000000&stroke=38C6A6&ring=38C6A6&fire=F2A93B&currStreakLabel=38C6A6"/>

<img src="https://github-profile-trophy.vercel.app/?username=JaganReddy-33&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=6&margin-w=10"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12&height=2" width="100%"/>

## `⟶` open to

<div align="center">

**Full Stack Developer** · **Java Backend Developer** · **Backend Engineer**

Looking for a role where I contribute to real production systems, learn from engineers ahead of me, and build things that hold up under real load — not just in a demo.

<br/>

<a href="https://jmr-portfolio-chi.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-38C6A6?style=for-the-badge&logo=vercel&logoColor=0B0D0C"/></a>
<a href="https://www.linkedin.com/in/jaganmohanreddy33/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ragipalyamjaganmohanreddy@gmail.com"><img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38C6A6,50:1F3864,100:0B0D0C&height=110&section=footer"/>
