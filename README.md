<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:09090B,55:1C1917,100:F59E0B&text=Bedirhan%20%C4%B0mer&fontColor=FAFAFA&fontSize=52&fontAlignY=36&desc=Systems%20%C2%B7%20Full-Stack%20%C2%B7%20Hardware&descAlignY=58&descSize=18" alt="Bedirhan İmer" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=F59E0B&center=true&vCenter=true&width=620&lines=16+y%2Fo+system+%26+full-stack+architect;Building+Shovrum%2C+a+social+app%2C+from+scratch;WebGL2+video+export%2C+E2E+chat%2C+web+push;ESP32+%C2%B7+Orange+Pi+%C2%B7+offline+voice+AI" alt="Typing intro" /></a>
</p>

<p align="center">
  <a href="https://bedirhanimer.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=vercel&logoColor=F59E0B" alt="Portfolio" /></a>
  <a href="mailto:abimer2350@gmail.com"><img src="https://img.shields.io/badge/Email-F59E0B?style=for-the-badge&logo=gmail&logoColor=0A0A0A" alt="Email" /></a>
  <a href="https://sigalmedia.com.tr"><img src="https://img.shields.io/badge/Shovrum-live-1C1917?style=for-the-badge&logo=googlechrome&logoColor=F59E0B" alt="Shovrum live" /></a>
  <img src="https://komarev.com/ghpvc/?username=Bedirhan3428&style=for-the-badge&color=F59E0B&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## `$ whoami`

```yaml
name:      Bedirhan İmer
age:       16
role:      System & Full-Stack Architect · AI-driven developer · hardware tinkerer
building:  Shovrum, a social app (feed, reels, stories, chat, video editor)
stack:     TypeScript · Next.js · React Native · Node.js · Python · Firebase · GCP
hardware:  ESP32 · Orange Pi (arm64 Linux) · custom cyberdeck
motto:     "Designing systems that scale with logic."
```

I like problems that sit between layers: a video encoder that is too slow, a chat that loads from the network when it could load from disk, a recommender that should learn from a scroll instead of a rule. I fix them at the root, measure the result, and ship.

---

## 🔭 Now building: **Shovrum**

> A full social platform, built end to end. Feed with reply chains and polls, Reels and Stories with an in-browser editor, encrypted DMs, push notifications and animated profile themes.
> **Repo:** [`SigalMedia-Frontend`](https://github.com/Bedirhan3428/SigalMedia-Frontend) · **Live:** [sigalmedia.com.tr](https://sigalmedia.com.tr) · formerly *Sigal Media*

| Area | What I built | Result |
|---|---|---|
| 🎬 **Video editor & export** | CapCut-style Reels timeline, Story and Post studios. Export runs on a **WebGL2 compositor** with zero-copy `VideoFrame(canvas)` encoding, a remux fast path and HEVC/AV1 demux | 11 s clip with text: **10 s → 2 s** export, SSIM 0.997 |
| 💬 **Messaging** | Messages are encrypted on the client with the server's RSA public key (envelope encryption), with reactions, long-press menus, per-chat themes synced to both sides | Re-opening a chat **~360 ms → ~110 ms** via an IndexedDB cache-first feed and windowed pagination |
| 🔔 **Web Push** | VAPID push with the sender's avatar, an **inline "Reply" action** secured by an HMAC token, and the last 5 messages stacked per chat | Works on installed Android PWAs |
| 🧵 **Feed** | Card feed with **reply chains** (answer a post with a post, linked by a thin arrow), animated polls, a badge system with bronze, silver and gold tiers | Typed service layer, ready to swap backends |
| 🎨 **Profiles** | 4 profile themes, 10 code-drawn animated banners, an iTunes-powered profile song | Banners pause off-screen and respect reduced motion |
| 🛠️ **Workflow** | Orchestrated AI coding agents across Git worktrees: one branch per work package, automated Playwright E2E checks, backups before every merge | 160+ commits of reviewed, tested changes |

---

## 🧠 Selected projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [Keşfet Motoru](https://github.com/Bedirhan3428/kesfet-motoru)
**Self-learning discovery engine**
32-dimensional latent matrix factorisation trained with **online SGD**, with a **UCB bandit** for exploration. It learns from scroll speed, dwell time and likes in real time instead of static rules.
`Node.js` `Express` `ML`

</td>
<td width="50%" valign="top">

### 🎙️ [Chatbox](https://github.com/Bedirhan3428/chatbox)
**Peer-to-peer voice rooms**
1:1 and up to 4-person mesh calls in React Native. Audio flows device to device over **DTLS-SRTP**; the server only relays SDP and ICE.
`Expo` `WebRTC` `WebSocket`

</td>
</tr>
<tr>
<td valign="top">

### 📦 [StokPro](https://github.com/Bedirhan3428/stokpro)
**Stock, POS and accounting SaaS**
Optimistic UI on a local master-data cache, camera and USB **barcode scanning**, e-invoice and PDF printing, Excel export, sales and ledger dashboards.
`Next.js 16` `Firebase` `Chart.js` · [live](https://stokpro.vercel.app)

</td>
<td valign="top">

### 📺 [llofth](https://github.com/Bedirhan3428/llofth)
**Local media gateway**
A streaming portal for Smart TV, phone and desktop: HLS playback, a YouTube-style watch page, continue-watching, and smart-home hooks.
`Next.js` `HLS.js` `ffmpeg` · [live](https://llofth.vercel.app)

</td>
</tr>
<tr>
<td valign="top">

### 🎞️ [Clofthel](https://github.com/Bedirhan3428/clofthel-backend)
**Mobile streaming app & aggregation backend**
Expo app with intro skipping, offline-friendly caching and notifications, backed by a scheduled aggregation service on MongoDB Atlas.
`React Native` `Expo SDK 54` `Node.js` `MongoDB`

</td>
<td valign="top">

### 🛡️ [Ashfir Agent](https://github.com/Bedirhan3428/ashfir-agent)
**Encrypted cloud backup agent**
LLM-assisted file selection keeps only valuable documents. Files are **AES-256 encrypted on the client** before upload. Moving the server side to Cloud Functions cut hosting costs by about 90%.
`Python` `Groq · Llama 3.3` `GCP`

</td>
</tr>
<tr>
<td valign="top">

### 🛍️ [MHM Collection](https://github.com/Bedirhan3428/mhmcollection)
**Serverless e-commerce**
Cart and checkout flow with tight Firestore security rules, so the database can't be tampered with from the client.
`React` `Cloud Functions` `Firestore` · [live](https://mhmcollection.vercel.app)

</td>
<td valign="top">

### 🧩 [Şigal New Tab](https://github.com/Bedirhan3428/SIGAL_EXTENSION)
**Chrome extension (Manifest V3)**
Opens a web app in the new tab with no white flash: instant cache, DNS prefetch and TLS preconnect.
`Chrome MV3` `JavaScript`

</td>
</tr>
</table>

---

## 🔌 Off the screen

- **ESP32 firmware:** low-latency C++ for sensors, telemetry and wireless transmission.
- **Orange Pi 4 Pro:** headless arm64 Linux builds and GPIO integration running background agents.
- **Alya:** an offline voice assistant that captures audio locally and runs system actions on recognised commands.
- **Cyberdeck:** a self-built portable computer that ties all of the above together.

---

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,python,cpp,tailwind,firebase,mongodb,gcp,vercel,linux,raspberrypi,arduino,git&perline=8" alt="Skills" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WebGL2-990000?style=flat-square&logo=webgl&logoColor=white" alt="WebGL2" />
  <img src="https://img.shields.io/badge/WebCodecs-1C1917?style=flat-square&logo=googlechrome&logoColor=F59E0B" alt="WebCodecs" />
  <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" alt="WebRTC" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white" alt="PWA" />
  <img src="https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Vertex AI" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
</p>

---

## 📈 Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Bedirhan3428&show_icons=true&hide_border=true&bg_color=0A0A0A&title_color=F59E0B&icon_color=F59E0B&text_color=D4D4D8&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bedirhan3428&layout=compact&hide_border=true&bg_color=0A0A0A&title_color=F59E0B&text_color=D4D4D8&langs_count=6" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Bedirhan3428&bg_color=0A0A0A&color=D4D4D8&line=F59E0B&point=FAFAFA&area=true&area_color=F59E0B&hide_border=true" alt="Contribution graph" />
</p>

---

<p align="center">
  <i>"Designing systems that scale with logic."</i><br/>
  <sub><b>SYS_OPT_01 // AI DRIVEN // ALWAYS SHIPPING</b></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:F59E0B,45:1C1917,100:09090B" alt="" />
</p>
