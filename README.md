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
  currently:  ["Maintaining CertJS — shipping new features on the async document issuance platform"],
  interests:  ["Distributed Systems", "Deep Learning", "Developer Tooling"],
  funFact:    "I built my own Git — yes, the version control system."
};
```

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
- 🌐 Live at [deeporbit.hrishi-developer.in](https://deeporbit.hrishi-developer.in)

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

Developer-first certificate generation platform with templates, batch processing, webhooks, and public verification — completed and actively maintained.

- 🔄 Async BullMQ pipeline decouples request handling from background rendering & batch finalization
- 🏗️ Monorepo architecture: service-layer abstractions, resource-oriented APIs, dashboard aggregation
- 📦 Multi-stage worker pipeline for concurrent rendering, ZIP archive generation, and S3 artifact storage
- ⚡ Promise-based template deduplication + in-memory caching to cut redundant work
- 🐳 Fully dockerized (Turborepo-pruned multi-stage builds); Next.js frontend deployed separately
- 🌐 Live at [certjs.hrishi-developer.in](https://certjs.hrishi-developer.in)

`Node.js` `PostgreSQL` `Drizzle ORM` `BullMQ` `Sharp` `Express`

</td>
<td width="50%" valign="top">

### ⚡ [QuizBurst](https://github.com/Hrishi-524/Quiz-Burst)
**Real-time Systems · WebSockets · Backend**

A live multiplayer quiz platform with event-driven architecture.

- 📡 **Sub-100ms** update propagation across concurrent sessions
- 🔄 Room-based WebSocket management with disconnect recovery & state reconciliation
- 🏆 Live scoring and real-time leaderboards
- 🌐 Live at [quizburst.hrishi-developer.in](https://quizburst.hrishi-developer.in)

`Node.js` `Socket.IO` `React` `MongoDB`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩸 Vein Visualization System
**Computer Vision · Embedded Systems · Deep Learning**

A real-time subcutaneous vein imaging device built on embedded hardware — 🥇 **1st Place & Gold Medal, Avishkar Research Convention** (Mumbai University, 500+ teams).

- 📷 Raspberry Pi + NoIR camera for infrared vein capture
- 🎛️ CLAHE-based contrast enhancement for low-visibility vein patterns
- 🧠 U-Net segmentation model for real-time vein structure extraction
- 🏅 State-level podium finish among 500+ competing teams

`Python` `OpenCV` `U-Net` `Raspberry Pi`

</td>
<td width="50%" valign="top">

### 🏡 [Avora](https://github.com/Hrishi-524/Avora)
**Full-Stack · MERN · UI/UX**

My first full-stack project — a stays discovery & booking platform, and still the most colorful frontend I've shipped.

- 🎨 React 19 + Material-UI + Tailwind CSS, with Mapbox-powered location search
- 💳 Razorpay checkout woven into the booking flow
- 🔐 JWT auth + bcrypt, with session handling across frontend and backend
- 🌐 Deployed on Vercel (frontend) + Render (backend)
- 🌐 Live at [avora.hrishi-developer.in](https://avora.hrishi-developer.in)

`React` `Express` `MongoDB` `Tailwind CSS` `Razorpay`

</td>
</tr>
</table>

---

## 🏆 Major Achievements

| | Event | Scale |
|---|---|---|
| 🥇 1st Place | **Avishkar Research Convention** — Mumbai University (Gold Medal) | 500+ teams |
| 🥇 1st Place | **VNPS 2026** *(Team Lead)* | — |
| 🥇 1st Place | **Tech-A-Thon 25 Hackathon** | — |
| 🥉 3rd Place | **Prakalp 4.0 Hackathon** *(Team Lead)* | — |
| 🥉 3rd Place | **Prakalp 3.0 Hackathon** | — |
| 🥈 2nd Place | **RizviTank Ideathon** | — |
| 🔟 Top 10 | **InCubate 2025** — JIPMER & IIT Bombay | National MedTech Hackathon |

## 💼 Experience

**Winter Intern** · Tata Tele Business Services *(Dec 2025 – Jan 2026)*
- Worked with Docker and Kubernetes, building container images and working with Kubernetes deployments and services while learning container orchestration and cloud-native infrastructure practices
- Used SQL to query networking databases and extract operational data for VBA automation, reporting workflows, and downstream analysis/model-training use cases
- Gained practical exposure to Linux server administration, system monitoring, troubleshooting, and enterprise server infrastructure
- Onboarded 500+ enterprise client devices onto Zabbix, configuring monitoring and alerts across telecom infrastructure and automating data/reporting workflows using VBA, MySQL, and PostgreSQL, reducing manual reporting effort by 40%

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=80&section=footer" width="100%"/>

*"The best infrastructure is the kind users never think about."*

</div>
