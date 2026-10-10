<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:080B12,50:1E1B4B,100:0E7490&text=Swaraj%20Gaikwad&fontColor=ffffff&fontSize=56&fontAlignY=38&desc=Backend%20Developer%20%C2%B7%20Open-Source%20Contributor&descAlignY=60&descSize=18&animation=fadeIn" alt="Swaraj Gaikwad - Backend Developer and Open-Source Contributor" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=1100&color=22D3EE&center=true&vCenter=true&repeat=true&width=720&height=44&lines=Building+reliable+APIs+and+real-time+systems;Node.js+%C2%B7+Express+%C2%B7+WebSockets+%C2%B7+WebRTC;Contributor+to+Postiz+and+Eclipse+Theia;Currently+building+Sentra+%E2%80%94+website+health+monitoring" alt="Typing animation of what I do" />

**Building reliable APIs, real-time systems, and backend infrastructure.**

📍 Nashik, Maharashtra, India

<a href="https://swaraj-gaikwad.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a> <a href="https://linkedin.com/in/Gaikwad-Swaraj"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> <a href="https://github.com/swaraj017"><img src="https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a> <a href="https://leetcode.com/swarajgaikwad"><img src="https://img.shields.io/badge/LeetCode-262626?style=for-the-badge&logo=leetcode&logoColor=FFA116" alt="LeetCode" /></a>

<img src="https://komarev.com/ghpvc/?username=swaraj017&style=flat-square&color=22d3ee&label=PROFILE+VIEWS" alt="Profile views" /> <img src="https://img.shields.io/github/followers/swaraj017?label=FOLLOWERS&style=flat-square&color=A78BFA&labelColor=161B22" alt="Followers" />

</div>

---

## `01` — About

I'm a backend developer interested in building software that is reliable, maintainable, and ready to scale.

* **Backend:** Node.js, Express.js, REST APIs, authentication
* **Real-time systems:** WebSockets, WebRTC
* **Data:** MongoDB, MySQL, PostgreSQL
* **Infrastructure:** Docker, GitHub Actions, CI/CD
* **Open source:** Contributions to Postiz and Eclipse Theia

Currently building **Sentra**, a website health-monitoring platform to learn backend engineering, observability, and DevOps through hands-on implementation.

```yaml
now:
  building:      Sentra — website health monitoring
  learning:      [observability, DevOps, system design]
  contributing:  [Postiz, Eclipse Theia]
  practicing:    Data Structures & Algorithms on LeetCode
```

## `02` — Tech Stack

<div align="center">

**LANGUAGES**

<img src="https://skillicons.dev/icons?i=js,cpp,postgres&theme=dark" alt="JavaScript, C++, SQL" />

**BACKEND & REAL-TIME**

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,mysql&theme=dark" alt="Node.js, Express, MongoDB, MySQL" />

<img src="https://img.shields.io/badge/REST_APIs-0F766E?style=flat-square" alt="REST APIs" />
<img src="https://img.shields.io/badge/WebSockets-334155?style=flat-square" alt="WebSockets" />
<img src="https://img.shields.io/badge/WebRTC-334155?style=flat-square" alt="WebRTC" />
<img src="https://img.shields.io/badge/JWT-6D28D9?style=flat-square" alt="JWT" />
<img src="https://img.shields.io/badge/Mongoose-880000?style=flat-square" alt="Mongoose" />

**INFRASTRUCTURE & TOOLS**

<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,linux&theme=dark" alt="Docker, Git, GitHub, GitHub Actions, Linux" />

**CLOUD & INTEGRATIONS**

<img src="https://img.shields.io/badge/Backblaze_B2-E21E29?style=flat-square&logo=backblaze&logoColor=white" alt="Backblaze B2" />
<img src="https://img.shields.io/badge/Render-334155?style=flat-square&logo=render&logoColor=white" alt="Render" />
<img src="https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white" alt="Razorpay" />
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white" alt="Cloudinary" />

**ENGINEERING FUNDAMENTALS**

<img src="https://img.shields.io/badge/Data_Structures_&_Algorithms-4C1D95?style=flat-square" alt="Data Structures and Algorithms" />
<img src="https://img.shields.io/badge/OOP-1E3A8A?style=flat-square" alt="OOP" />
<img src="https://img.shields.io/badge/MVC-155E75?style=flat-square" alt="MVC" />
<img src="https://img.shields.io/badge/API_Design-065F46?style=flat-square" alt="API Design" />
<img src="https://img.shields.io/badge/Authentication-991B1B?style=flat-square" alt="Authentication" />

</div>

## `03` — How I Build Backends

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#0f1730','primaryTextColor':'#e2e8f0','primaryBorderColor':'#22d3ee','lineColor':'#a78bfa','fontFamily':'monospace'}}}%%
flowchart LR
    A([Client]) -->|HTTP| B[Express API]
    A <-.->|WebSocket / WebRTC| R[Real-time layer]
    B --> C{JWT Auth}
    C -->|valid| D[Controllers · MVC]
    C -->|invalid| X[401 Unauthorized]
    D --> E[(MongoDB · PostgreSQL · MySQL)]
    D --> F[Backblaze B2 · Cloudinary]
    D --> G[Razorpay]
    H[GitHub Actions CI/CD] --> I[Docker image] --> J[Render]
```

## `04` — Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### Sentra

**Website health monitoring**

Building a monitoring service that checks website availability, response latency, HTTP status codes, and failures.

`Node.js` `Express` `Monitoring`

<a href="https://github.com/swaraj017/sentra">View repository →</a>

</td>
<td width="50%" valign="top">

### CloudShare

**Object storage & access control**

File storage platform integrating Backblaze B2 with APIs for uploads, access control, API keys, and CDN delivery.

`Node.js` `MongoDB` `Backblaze B2`

<a href="https://github.com/swaraj017/CloudShare">View repository →</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### CodeVerse

**Real-time collaborative coding**

Collaborative development experience featuring WebRTC, Monaco Editor, and real-time communication.

`WebRTC` `JavaScript` `Real-time`

<a href="https://github.com/swaraj017/codeverse_v1">View repository →</a>

</td>
<td width="50%" valign="top">

### AI-Agent Recruiter

**Intelligent resume matching**

Academic project focused on resume ranking using transformer embeddings and automated recruitment workflows.

`AI` `Embeddings` `Recruitment`

<a href="https://github.com/swaraj017/AI_Agent_Recruitment_Sytem">View repository →</a>

</td>
</tr>
</table>

## `05` — Open Source

<div align="center">

<a href="https://github.com/gitroomhq/postiz-app"><img src="https://img.shields.io/badge/Postiz-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="Postiz" /></a> <a href="https://github.com/eclipse-theia/theia"><img src="https://img.shields.io/badge/Eclipse_Theia-F7941E?style=for-the-badge&logo=eclipseide&logoColor=white" alt="Eclipse Theia" />
</div>

Contributing fixes to real-world software projects and learning from established codebases, reviews, and maintainers.

## `06` — GitHub Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=swaraj017&bg_color=080B12&color=22D3EE&line=A78BFA&point=FFFFFF&area=true&area_color=A78BFA&hide_border=true&radius=16&custom_title=Contribution%20Graph" width="100%" alt="Contribution activity graph" />

<img height="165" src="https://github-readme-stats.vercel.app/api?username=swaraj017&show_icons=true&hide_border=true&bg_color=080B12&title_color=22D3EE&text_color=C9D1D9&icon_color=A78BFA" alt="GitHub statistics" />
<img height="165" src="https://streak-stats.demolab.com?user=swaraj017&hide_border=true&background=080B12&ring=22D3EE&fire=A78BFA&currStreakLabel=22D3EE&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=94A3B8" alt="GitHub contribution streak" />

<a href="https://leetcode.com/swarajgaikwad">
<img src="https://leetcard.jacoblin.cool/swarajgaikwad?theme=dark&font=JetBrains%20Mono&ext=heatmap" alt="LeetCode activity" />
</a>

</div>

---

<div align="center">

**Designing APIs. Debugging systems. Shipping improvements.**

<sub>Always learning. Always building.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=110&color=0:0E7490,50:1E1B4B,100:080B12" alt="" />

</div>
