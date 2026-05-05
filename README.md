<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Mateus%20Dev&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Full-Stack%20Developer%20%7C%20AI%20Engineer%20%7C%20Building%20Real%20Products&descSize=16&descAlignY=52"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2500&pause=800&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=false&width=550&height=75&lines=Chrome+Extensions+%7C+Mobile+Apps+%7C+SaaS+Platforms;AI+Integration+%7C+Full-Stack+%7C+Cloud+Deployment)](https://github.com/mtdev-py)

</div>

---

## About Me

I'm a Systems Analysis & Development student and Full-Stack Developer with hands-on experience building and shipping real software products. I work daily with code editors and modern dev tools, turning ideas into functional applications that solve actual problems.

My approach is simple: **when I face a problem, I build a solution.** Whether it's automating a repetitive task with a script, building a Chrome extension to fill a gap, or architecting a full SaaS platform from scratch -- I enjoy the entire process from idea to deployment.

I'm passionate about sharing what I build. Most of my projects are **open-source and free to use**, because I believe good tools should be accessible to everyone. I actively develop across multiple platforms: web apps hosted on production servers, Chrome extensions published on the Web Store, backend APIs deployed on cloud infrastructure, and mobile apps heading to app stores.

**What drives me:**
- Identifying real-world problems and engineering practical solutions
- Building end-to-end: from database design to UI polish
- Automating everything that can be automated
- Sharing tools and solutions publicly for the community

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### AI Web Reader Pro
> Chrome Extension | Published on Chrome Web Store

An intelligent browser extension that **extracts, summarizes, and reads aloud** any web page using AI. Built to solve a specific problem: course platforms that convert text into images to prevent copying, making it impossible for students to study efficiently.

The extension captures full-page screenshots via automated scrolling, processes each frame through **GPT-4o Vision or Gemini Vision** for OCR text extraction, deduplicates overlapping content between captures, and combines the result with DOM-extracted text for complete coverage. Users can then summarize, explain, or simplify the content with AI, and listen to everything with natural human voice via ElevenLabs TTS.

The audio playback runs in a persistent **offscreen document**, so it continues playing even when the popup is closed -- perfect for passive studying while doing other tasks.

**Technical highlights:**
- Hybrid DOM extraction engine with density-based scoring and noise removal
- Full-page OCR pipeline: scroll capture, Vision AI processing, overlap deduplication
- Persistent audio via Chrome Offscreen API (Manifest V3)
- Session state persistence across popup open/close cycles
- Rate limiting, error retry with exponential backoff, audio caching

**Stack:** `TypeScript` `React` `TailwindCSS` `Chrome MV3` `Vite`
**APIs:** `OpenAI GPT-4o` `Google Gemini 2.0` `ElevenLabs TTS`

[![View Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/mtdev-py/ai-web-reader-pro)

</td>
<td width="50%" valign="top">

### Orbita -- Productivity Platform
> Full-Stack SaaS | Mobile App | Coming to Google Play

A complete **life management and productivity platform** designed to help users organize finances, track goals, build habits, and get AI-powered assistance -- all in one place. Built as a hybrid mobile application with a real-time cloud backend.

The platform features a fully integrated **AI assistant powered by Gemini** with an extensive internal knowledge base, enabling it to answer questions about the platform, register expenses and tasks via natural language, and provide personalized productivity advice -- all while minimizing API token usage through smart FAQ matching.

User authentication is handled via **Google OAuth** with proper SPA routing for production deployment. All data is isolated per-user using **Row Level Security** policies in PostgreSQL, ensuring multi-tenant data safety.

**Technical highlights:**
- AI assistant with context-aware responses and internal knowledge base
- Full financial dashboard: income, expenses, categories, analytics charts
- Goal tracking with progress visualization and habit streaks
- Google OAuth authentication with Supabase Auth
- Edge Functions for server-side AI processing and secure API key management
- Row Level Security for complete data isolation between users
- Responsive mobile-first UI with dark/light theme support

**Stack:** `React` `TypeScript` `Capacitor` `Supabase` `PostgreSQL` `Edge Functions`
**Deploy:** `Hostinger` `Supabase Cloud` `Google Play (soon)`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### YT Downloader
> Chrome Extension + Backend API | Live on Railway

A full-stack media download solution combining a **Chrome extension frontend** with a **Flask backend API** deployed on Railway. The extension injects a clean, modern UI directly into target pages, while the backend handles all the heavy processing using yt-dlp.

Built to solve the frustration of unreliable online download tools filled with ads and malware. This solution provides a clean, ad-free experience with support for multiple formats and quality levels, all processed through a secure backend API.

**Technical highlights:**
- Chrome extension with injected UI components
- Flask API with yt-dlp integration for reliable media processing
- Proxy support and format selection (MP3, MP4, WebM)
- Railway deployment with automatic scaling
- Clean, modern interface without ads or trackers

**Stack:** `Python` `Flask` `JavaScript` `Chrome MV3` `HTML/CSS`
**Deploy:** `Railway`

[![View Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/mtdev-py/yt-downloader-api)

</td>
<td width="50%" valign="top">

### Enterprise Internal Tools
> Confidential Client Project | NDA

Developed custom **internal automation tools and scripts** for a private organization to streamline their digital operations. The project involved building solutions to automate repetitive workflows, process and transform data at scale, and integrate with third-party services and APIs.

Due to confidentiality agreements, specific details and the client's identity cannot be disclosed. The work demonstrates experience with enterprise-level requirements including security considerations, data handling, and building reliable tools that operate in production environments.

**Technical highlights:**
- Custom automation scripts for workflow optimization
- Data processing and transformation pipelines
- Third-party API integration and service orchestration
- Production-grade error handling and logging
- Designed for reliability and minimal maintenance

**Stack:** `Python` `JavaScript` `Node.js` `API Integration` `Automation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Geolocation Map
> Web App | Live Deployment

An interactive geolocation web application that detects and displays the user's current position on a dynamic map. Built as a practical utility tool using the **browser Geolocation API** with an IP-based fallback system for environments where GPS access is restricted or denied.

**Technical highlights:**
- Real-time GPS positioning via browser Geolocation API
- IP geolocation fallback for restricted/denied access scenarios
- Interactive map with zoom controls and position markers
- Fully responsive design for mobile and desktop

**Stack:** `HTML` `CSS` `JavaScript` `Geolocation API`

[![View Repo](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github)](https://github.com/mtdev-py/mapa-localizacao_atual)

</td>
<td width="50%" valign="top">

### Open Source Scripts & Automations
> Public Utilities | Free to Use

A growing collection of **scripts, automations, and small tools** built to solve specific everyday problems. Whenever I encounter a repetitive task or a workflow bottleneck, I build a solution and share it publicly.

These range from file processing utilities and API interaction scripts to browser automation tools and data transformation helpers. All published openly for anyone to use, modify, and learn from.

**Philosophy:** If a task takes more than 5 minutes and you'll do it again, automate it and share the script.

**Stack:** `Python` `JavaScript` `Shell` `Automation`

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

### Languages & Frameworks
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Platforms & Tools
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Cloud & Deployment
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Hostinger](https://img.shields.io/badge/Hostinger-673DE6?style=for-the-badge&logo=hostinger&logoColor=white)
![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)

### AI & APIs
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mtdev-py&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mtdev-py&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="170"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mtdev-py&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="170"/>

</div>

---

<div align="center">

### Where to Find My Work

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Published-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/)
[![Google Play](https://img.shields.io/badge/Google_Play-Coming_Soon-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/)
[![GitHub](https://img.shields.io/badge/GitHub-mtdev--py-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mtdev-py)

---

**Open to opportunities** -- Let's build something great.

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
