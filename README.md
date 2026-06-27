<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=header" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Hrishi+Patil+%F0%9F%91%8B;Backend+%26+AI+Engineer;Building+systems+that+scale;From+Mumbai%2C+India+%F0%9F%87%AE%F0%9F%87%B3" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/linkedhrishi)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hrishi.patil.dev@gmail.com)

</div>

---

## `whoami`

```ts
const hrishi = {
  role:       "Backend + AI Engineer",
  education:  "B.E. Computer Engineering @ University Of Mumbai (CGPA: 9.5/10)",
  honors:     "AI & Machine Learning",
  location:   "Mumbai, India 🇮🇳",
  currently:  ["Building CertJS — async document issuance platform"],
  interests:  ["Distributed Systems", "Deep Learning", "Developer Tooling"],
  funFact:    "I built my own Git — yes, the version control system."
};
```

---

## ⚡ Tech Arsenal

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Infrastructure**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white)

**AI / ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**DevOps & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ [DeepOrbit](https://github.com/Hrishi-524/DeepOrbit)
**Deep Learning · Time Series · Satellite Systems**

Built a multi-architecture deep learning pipeline — BiLSTM, Transformer (4-head self-attention), and Probabilistic LSTM — to predict GPS satellite positioning errors **12 hours ahead**.

- 📐 **0.12m MAE / 0.14m RMSE** on MEO satellites
- 🔁 15-min interval telemetry over 7-day rolling windows
- 🧠 Custom orbital feature engineering: lag features, cyclical encodings, rolling trend signals
- ⚙️ RobustScaler + Huber loss to handle ±45m GEO outliers

`Python` `TensorFlow` `Scikit-learn` `Pandas` `NumPy`

</td>
<td width="50%" valign="top">

### 🗃️ [Track2Go](https://github.com/Hrishi-524/Track2Go)
**Distributed Systems · Developer Tooling · Cloud**

A Git-inspired distributed version control & code hosting platform — built from scratch.

- 🔗 Hash-based object storage with commit-chaining persisted to **AWS S3**
- 🖥️ Custom CLI: `init`, `add`, `commit`, `push`
- 🏗️ Production infra: EC2 + Caddy (auto TLS) + Redis JWT blacklisting + MongoDB
- 🌐 Live at [track2go.hrishi-developer.in](https://track2go.hrishi-developer.in)

`Node.js` `Express` `AWS S3` `Redis` `MongoDB` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📜 [CertJS](https://github.com/Hrishi-524/certjs)
**Async Systems · Document Processing · Backend**

Developer-first certificate generation platform with templates, batch processing, webhooks, and public verification.

- 📬 Async job pipeline: API → queue → worker (decoupled from request lifecycle)
- 🖼️ SVG-overlay rendering engine for dynamic placeholder documents
- 🔐 Tamper-resistant verification via cryptographic hashing + unique document IDs

`Node.js` `PostgreSQL` `Drizzle ORM` `Sharp` `Express`

</td>
<td width="50%" valign="top">

### ⚡ [QuizBurst](https://github.com/Hrishi-524/Quiz-Burst)
**Real-time Systems · WebSockets · Backend**

A live multiplayer quiz platform with event-driven architecture.

- 📡 **Sub-100ms** update propagation across concurrent sessions
- 🔄 Room-based WebSocket management with disconnect recovery & state reconciliation
- 🏆 Live scoring and real-time leaderboards

`Node.js` `Socket.IO` `React` `MongoDB`

</td>
</tr>
</table>

---

## 🏆 Major Achievements

| 🥇 | Event | Scale |
|---|---|---|
| 🥇 1st Place | **Avishkar Research Convention** — Mumbai University | 500+ teams |
| 🥇 1st Place | **Tech-A-Thon 25 Hackathon** | — |
| 🥉 3rd Place | **Prakalp 3.0 and 4.0 Hackathon** *(Team Lead)* | — |
| 🥈 2nd Place | **RizviTank Ideathon** | — |
 - more such

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats-pi-snowy-86.vercel.app?user=Hrishi-524&theme=dark)](https://git.io/streak-stats)

</div>

---

## 💼 Experience

**Network Operations Intern** · Tata Tele Business Services *(Dec 2025 – Jan 2026)*

- Onboarded **500+ enterprise devices** onto Zabbix for production telecom monitoring
- Built VBA automation pipelines → MySQL/PostgreSQL, cutting manual reporting by **40%**
- Diagnosed performance issues on Linux-based enterprise networking infrastructure

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=80&section=footer" width="100%"/>

*"The best infrastructure is the kind users never think about."*

</div>
