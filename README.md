<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 360" role="img" aria-labelledby="title desc" preserveAspectRatio="xMidYMid slice" width="100%">
  <title id="title">its-ash profile banner</title>
  <desc id="desc">Futuristic neon grid banner with animated title and status.</desc>
  <style>
    @media (prefers-color-scheme: light) {
      .bg-stop-0 { stop-color: #e8ecf1 !important; }
      .bg-stop-1 { stop-color: #dde4ed !important; }
      .bg-stop-2 { stop-color: #e0d8e8 !important; }
      .grid-line { stroke: #4a90a4 !important; stroke-opacity: 0.18 !important; }
      .title-fill { fill: #1a2744 !important; }
      .subtitle-fill { fill: #0066cc !important; }
      .status-panel-fill { fill: #eef2f7 !important; }
      .status-panel-stroke { stroke: #0066cc !important; stroke-opacity: 0.55 !important; }
      .status-label { fill: #0066cc !important; }
      .horizon-line { opacity: 0.7 !important; }
    }
  </style>
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop class="bg-stop-0" offset="0%" stop-color="#05070f">
        <animate attributeName="stop-color" values="#05070f;#071024;#05070f" dur="10s" repeatCount="indefinite"/>
      </stop>
      <stop class="bg-stop-1" offset="55%" stop-color="#09152a">
        <animate attributeName="stop-color" values="#09152a;#0b2a3f;#09152a" dur="12s" repeatCount="indefinite"/>
      </stop>
      <stop class="bg-stop-2" offset="100%" stop-color="#12070f">
        <animate attributeName="stop-color" values="#12070f;#22041a;#12070f" dur="14s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="line" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00eaff">
        <animate attributeName="stop-color" values="#00eaff;#36ffc9;#ff8f00;#00eaff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#36ffc9">
        <animate attributeName="stop-color" values="#36ffc9;#ff8f00;#00eaff;#36ffc9" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#ff8f00">
        <animate attributeName="stop-color" values="#ff8f00;#00eaff;#36ffc9;#ff8f00" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="scanGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset="40%" stop-color="#7fffd4" stop-opacity="0.12"/>
      <stop offset="60%" stop-color="#ffffff" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <pattern id="grid" width="45" height="45" patternUnits="userSpaceOnUse">
      <path class="grid-line" d="M 45 0 L 0 0 0 45" fill="none" stroke="#11c0d4" stroke-opacity="0.13" stroke-width="1"/>
    </pattern>
  </defs>
  <rect width="1200" height="360" fill="url(#bg)"/>
  <rect width="1200" height="360" fill="url(#grid)" opacity="0.75"/>
  <rect id="scanRect" x="-420" y="0" width="420" height="360" fill="url(#scanGradient)" opacity="0.35">
    <animateTransform attributeName="transform" type="translate" from="-420 0" to="1200 0" dur="6s" repeatCount="indefinite"/>
  </rect>
  <g opacity="0.9">
    <circle cx="180" cy="70" r="2" fill="#00f5ff">
      <animate attributeName="r" values="1.2;2.8;1.8" dur="3.6s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0 0;2 -2;0 0" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="260" cy="120" r="1.5" fill="#36ffc9">
      <animate attributeName="r" values="1;2.6;1.4" dur="4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0 0;-3 2;0 0" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="980" cy="92" r="2" fill="#ff8f00">
      <animate attributeName="r" values="1.5;3;1.5" dur="3.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0 0;4 -1;0 0" dur="7.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1060" cy="40" r="1.6" fill="#00f5ff">
      <animate attributeName="r" values="1;2.8;1.2" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1120" cy="140" r="1.6" fill="#36ffc9">
      <animate attributeName="r" values="1;2.8;1.2" dur="4.4s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g class="horizon-line" filter="url(#glow)">
    <line x1="70" y1="82" x2="1130" y2="82" stroke="url(#line)" stroke-width="2" stroke-linecap="round" stroke-dasharray="12 24">
      <animate attributeName="stroke-dashoffset" from="0" to="-360" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.95;0.7;0.95" dur="6s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="278" x2="1130" y2="278" stroke="url(#line)" stroke-width="2" stroke-linecap="round" stroke-dasharray="16 20">
      <animate attributeName="stroke-dashoffset" from="0" to="360" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.9;0.6;0.9" dur="8s" repeatCount="indefinite"/>
    </line>
  </g>
  <g id="titleGroup" transform="translate(0,0)">
    <text class="title-fill" x="80" y="170" fill="#e6fbff" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="60" font-weight="700" letter-spacing="2">
      ITS-ASH
      <animate attributeName="opacity" values="1;0.96;1" dur="4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0 0;0 -4;0 0" dur="6s" repeatCount="indefinite"/>
    </text>
    <text class="subtitle-fill" x="80" y="215" fill="#7cf4ff" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="24" letter-spacing="1.2">
      FULL-STACK DEVELOPER  //  PERFORMANCE + PRIVACY + DX
      <animate attributeName="opacity" values="0.98;0.85;0.98" dur="5s" repeatCount="indefinite"/>
    </text>
  </g>
  <g transform="translate(830 128)">
    <rect class="status-panel-fill" x="0" y="0" width="320" height="100" rx="12" fill="#0a1021" stroke="#1ce7ff" stroke-opacity="0.65"/>
    <text class="status-label" x="20" y="38" fill="#39f0ff" font-family="Consolas, 'SFMono-Regular', Menlo, monospace" font-size="18">SYSTEM STATUS</text>
    <text id="statusText" x="20" y="70" fill="#f7b24b" font-family="Consolas, 'SFMono-Regular', Menlo, monospace" font-size="20">ONLINE
      <animate attributeName="fill" values="#f7b24b;#ffd76b;#f7b24b" dur="1.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.85;1" dur="1.6s" repeatCount="indefinite"/>
    </text>
    <circle cx="282" cy="38" r="6" fill="#39f0ff" opacity="0.95">
      <animate attributeName="r" values="6;10;6" dur="1.6s" repeatCount="indefinite"/>
      <animate attributeName="fill" values="#39f0ff;#1ef0b5;#39f0ff" dur="1.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.9;0.5;0.9" dur="1.6s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>
</div>

<h1 align="center">
	<picture>
		<source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&pause=1000&color=00F5FF&center=true&vCenter=true&width=900&lines=SYSTEM+ONLINE+%3A%3A+Ashvini+Jangid;Full-Stack+Developer;Privacy-First+Tooling+Builder;WebAssembly+%7C+Rust+%7C+Node.js+%7C+React+%7C+Vue" />
		<source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&pause=1000&color=0066CC&center=true&vCenter=true&width=900&lines=SYSTEM+ONLINE+%3A%3A+Ashvini+Jangid;Full-Stack+Developer;Privacy-First+Tooling+Builder;WebAssembly+%7C+Rust+%7C+Node.js+%7C+React+%7C+Vue" />
		<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&pause=1000&color=00F5FF&center=true&vCenter=true&width=900&lines=SYSTEM+ONLINE+%3A%3A+Ashvini+Jangid;Full-Stack+Developer;Privacy-First+Tooling+Builder;WebAssembly+%7C+Rust+%7C+Node.js+%7C+React+%7C+Vue" alt="Typing intro" />
	</picture>
</h1>

<p align="center">
	<i>Building products that stay fast, clear, and reliable at scale.</i>
</p>

<p align="center">
	<a href="https://github.com/its-ash"><img src="https://img.shields.io/badge/GitHub-0A0A0A?style=for-the-badge&logo=github&logoColor=00F5FF" alt="GitHub" /></a>
	<a href="https://www.linkedin.com/in/ashvinijangid/"><img src="https://img.shields.io/badge/LinkedIn-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=36FFC9" alt="LinkedIn" /></a>
	<a href="https://its-ash.github.io/"><img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=vercel&logoColor=FF8F00" alt="Portfolio" /></a>
	<a href="https://ash-tools.store/"><img src="https://img.shields.io/badge/Ash%20Tools-0A0A0A?style=for-the-badge&logo=cloudflarepages&logoColor=00F5FF" alt="Ash Tools" /></a>
	<img src="https://komarev.com/ghpvc/?username=its-ash&label=Profile%20Views&color=00b7cc&style=for-the-badge" alt="Profile views" />
</p>

---

<picture>
	<source media="(prefers-color-scheme: dark)" srcset="https://github.com/its-ash/its-ash/raw/output/github-contribution-grid-snake-dark.svg" />
	<source media="(prefers-color-scheme: light)" srcset="https://github.com/its-ash/its-ash/raw/output/github-contribution-grid-snake.svg" />
	<img src="https://github.com/its-ash/its-ash/raw/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" width="100%" />
</picture>

---

## 🧬 Who I Am

```yaml
name: Ashvini Jangid
role: Full-Stack Developer
location: India
focus: Performance | Privacy | Developer Experience
languages: JavaScript, TypeScript, Rust, Go, Python
currently_learning: WebGPU + Distributed Systems
ask_me_about: Browser tooling, edge computing, IoT
```

- 🛠️ I ship practical software across frontend, backend, and developer tooling.
- ⚡ I focus on performance, maintainability, and shipping speed — no quality trade-offs.
- 🏗️ I prefer clear architecture, measurable outcomes, and low operational drag.
- 🔒 Privacy-first advocate — your data stays on your device.

---

## 🧰 Core Stack

<p>
	<img src="https://img.shields.io/badge/JavaScript-121212?style=for-the-badge&logo=javascript&logoColor=FFD93D" alt="JavaScript" />
	<img src="https://img.shields.io/badge/TypeScript-121212?style=for-the-badge&logo=typescript&logoColor=2EBDFF" alt="TypeScript" />
	<img src="https://img.shields.io/badge/Node.js-121212?style=for-the-badge&logo=node.js&logoColor=71E17B" alt="Node.js" />
	<img src="https://img.shields.io/badge/React-121212?style=for-the-badge&logo=react&logoColor=5DE4FF" alt="React" />
	<img src="https://img.shields.io/badge/Vue-121212?style=for-the-badge&logo=vuedotjs&logoColor=45E38D" alt="Vue" />
	<img src="https://img.shields.io/badge/Python-121212?style=for-the-badge&logo=python&logoColor=8FD3FF" alt="Python" />
	<img src="https://img.shields.io/badge/Go-121212?style=for-the-badge&logo=go&logoColor=67E8F9" alt="Go" />
	<img src="https://img.shields.io/badge/Rust-121212?style=for-the-badge&logo=rust&logoColor=FFB86B" alt="Rust" />
	<img src="https://img.shields.io/badge/FastAPI-121212?style=for-the-badge&logo=fastapi&logoColor=36FFC9" alt="FastAPI" />
	<img src="https://img.shields.io/badge/Django-121212?style=for-the-badge&logo=django&logoColor=89F0C4" alt="Django" />
</p>

## 📡 IoT & Edge

<p>
	<img src="https://img.shields.io/badge/IoT-121212?style=for-the-badge" alt="IoT" />
	<img src="https://img.shields.io/badge/MQTT-121212?style=for-the-badge" alt="MQTT" />
	<img src="https://img.shields.io/badge/ESP32-121212?style=for-the-badge" alt="ESP32" />
	<img src="https://img.shields.io/badge/Raspberry%20Pi-121212?style=for-the-badge&logo=raspberry-pi" alt="Raspberry Pi" />
	<img src="https://img.shields.io/badge/Home%20Assistant-121212?style=for-the-badge&logo=home-assistant" alt="Home Assistant" />
	<img src="https://img.shields.io/badge/PlatformIO-121212?style=for-the-badge&logo=platformio" alt="PlatformIO" />
	<img src="https://img.shields.io/badge/LoRaWAN-121212?style=for-the-badge" alt="LoRaWAN" />
</p>

---

## 🎯 Focus Areas

| Track | Mission |
|---|---|
| 🖥️ Frontend Systems | Accessible interfaces, meaningful motion, and production-grade performance tuning. |
| ⚙️ Backend Platforms | APIs and service boundaries designed for observability and predictable scaling. |
| 🔧 Developer Experience | Tooling and CI guardrails that reduce friction and keep teams shipping. |
| 🔌 IoT & Edge | Embedded systems, MQTT pipelines, and edge intelligence for real-world hardware. |

---

## 🚀 Featured Build // Ash Tools

<p>
	<a href="https://ash-tools.store/"><img src="https://img.shields.io/badge/LIVE-ash--tools.store-00F5FF?style=for-the-badge&logo=cloudflarepages&logoColor=0A0A0A" alt="Ash Tools Live" /></a>
	<a href="https://github.com/its-ash/ash-tools"><img src="https://img.shields.io/badge/SOURCE-ash--tools-FF8F00?style=for-the-badge&logo=github&logoColor=0A0A0A" alt="Ash Tools Source" /></a>
</p>

Ash Tools is a privacy-first workspace of browser tools for media, documents, and dev workflows.

- 🧠 Local-first processing with **WebAssembly** and **WebGPU**.
- ⚡ Built to run fast — **no upload required** for sensitive files.
- 🧰 Includes **Video Studio**, **Image Editor**, **PDF Merger**, **Regex Generator**, and **Code Sandbox**.

---

## 📊 GitHub Signal

<p align="center">
	<picture>
		<source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=its-ash&background=0D1117&ring=00F5FF&fire=FF8F00&currStreakLabel=00F5FF&sideNums=E6EDF3&sideLabels=9FB3C8&dates=8EA4BA&stroke=00B7CC" />
		<source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=its-ash&background=F6F8FA&ring=0066CC&fire=FF8F00&currStreakLabel=0066CC&sideNums=24292F&sideLabels=586069&dates=586069&stroke=00B7CC" />
		<img src="https://streak-stats.demolab.com?user=its-ash&background=0D1117&ring=00F5FF&fire=FF8F00&currStreakLabel=00F5FF&sideNums=E6EDF3&sideLabels=9FB3C8&dates=8EA4BA&stroke=00B7CC" alt="GitHub streak" />
	</picture>
</p>

<p align="center">
	<picture>
		<source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=its-ash&bg_color=0d1117&color=e6edf3&line=00f5ff&point=ff8f00&area=true&hide_border=true" />
		<source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=its-ash&bg_color=f6f8fa&color=24292f&line=0066cc&point=ff8f00&area=true&hide_border=true" />
		<img src="https://github-readme-activity-graph.vercel.app/graph?username=its-ash&bg_color=0d1117&color=e6edf3&line=00f5ff&point=ff8f00&area=true&hide_border=true" alt="Activity graph" width="90%" />
	</picture>
</p>

---

## 🔗 Live Warp Gates

<table>
	<tr>
		<td align="center" width="33%">
			<a href="https://its-ash.github.io/"><img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=vercel&logoColor=FF8F00" alt="Portfolio" /></a>
		</td>
		<td align="center" width="33%">
			<a href="https://its-ash.github.io/project.html"><img src="https://img.shields.io/badge/Projects-0A0A0A?style=for-the-badge&logo=github&logoColor=00F5FF" alt="Projects" /></a>
		</td>
		<td align="center" width="33%">
			<a href="https://its-ash.github.io/resume.pdf"><img src="https://img.shields.io/badge/Resume-0A0A0A?style=for-the-badge&logo=adobeacrobatreader&logoColor=36FFC9" alt="Resume" /></a>
		</td>
	</tr>
	<tr>
		<td align="center" width="33%">
			<a href="https://www.linkedin.com/in/ashvinijangid/"><img src="https://img.shields.io/badge/LinkedIn-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=36FFC9" alt="LinkedIn" /></a>
		</td>
		<td align="center" width="33%">
			<a href="https://ash-tools.store/"><img src="https://img.shields.io/badge/Ash%20Tools-0A0A0A?style=for-the-badge&logo=cloudflarepages&logoColor=00F5FF" alt="Ash Tools" /></a>
		</td>
		<td align="center" width="33%">
			<a href="mailto:ashvini.jangid@email.com"><img src="https://img.shields.io/badge/Email-0A0A0A?style=for-the-badge&logo=gmail&logoColor=FF8F00" alt="Email" /></a>
		</td>
	</tr>
</table>

---

<div align="center">
	<picture>
		<source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:00b7cc,100:00F5FF&height=100&section=footer" />
		<source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:E1E4E8,100:0066CC&height=100&section=footer" />
		<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b7cc,100:00F5FF&height=100&section=footer" alt="Footer wave" width="100%" />
	</picture>
</div>

<p align="center">
	<i>Thanks for stopping by ⭐ Star a repo if something helped you.</i>
</p>
