<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:050505,60:0b3a4a,100:00D9FF&height=210&section=header&text=Saugat%20Rauniyar&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=builds%20things.%20breaks%20them.%20ships%20them%20better.&descAlignY=60&descSize=17)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=00D9FF&center=true&vCenter=true&width=640&lines=2nd+place+%7C+SecLeaf+CTF+2026;3rd+of+50%2B+teams+%7C+HackaFest+2026;AI+radiology+workstation+%40+IIIT+Kottayam;solving+problems+students+actually+have)](https://saugatrauniyar.com.np)

<a href="https://www.saugatrauniyar.com.np/"><img src="https://img.shields.io/badge/PORTFOLIO-050505?style=for-the-badge&logo=vercel&logoColor=00D9FF" /></a>
<a href="https://www.linkedin.com/in/saugat-rauniyar/"><img src="https://img.shields.io/badge/LINKEDIN-050505?style=for-the-badge&logo=linkedin&logoColor=00D9FF" /></a>
<a href="mailto:saugat.rauniyar.work@gmail.com"><img src="https://img.shields.io/badge/EMAIL-050505?style=for-the-badge&logo=gmail&logoColor=00D9FF" /></a>
<a href="https://instagram.com/rauniyarsaugat"><img src="https://img.shields.io/badge/INSTAGRAM-050505?style=for-the-badge&logo=instagram&logoColor=00D9FF" /></a>

</div>

---

```console
saugat@raw-swag:~$ whoami
saugat-rauniyar  //  full-stack dev · AI builder · security explorer

saugat@raw-swag:~$ cat education.txt
B.E. Computer Science & Engineering, Siddaganga Institute of Technology, Tumakuru
2025 - 2029  ·  CGPA 9.5 / 10

saugat@raw-swag:~$ cat trophies.log
[2026]  SecLeaf CTF ............ 2nd place · 7,407 pts · team Merp Era
[2026]  HackaFest .............. 3rd place · 50+ teams · Impostr
[2026]  TECHASHY 2.0 ........... IIIT Kottayam · Lucerna · team Aether

saugat@raw-swag:~$ cat philosophy.txt
I don't build tutorial projects. I build things for problems I can see around me.

saugat@raw-swag:~$ _
```

## 🎯 Active Missions

| | Mission | What it is | Status |
|---|---|---|---|
| 🏠 | **[DORMEX](https://github.com/raw-swag/DORMEX)** | Hostel allotment platform for college students: priority-based seat allocation, PostgreSQL integrity constraints, 6-role access control, floor-plan seat picker | ![](https://img.shields.io/badge/status-in%20development-00D9FF?style=flat-square&labelColor=050505) |
| 🩻 | **Lucerna** | Distributed AI diagnostic workstation for radiology with Google MedGemma 4B-IT and clinicians kept in the loop. Built with Team Aether at TECHASHY 2.0, IIIT Kottayam | ![](https://img.shields.io/badge/status-hackathon%20build-00D9FF?style=flat-square&labelColor=050505) |
| 🕵️ | **[Impostr](https://github.com/raw-swag/Impostr)** | Threat-intel and domain forensics platform. 3rd of 50+ teams at HackaFest 2026 | ![](https://img.shields.io/badge/status-live-2ea043?style=flat-square&labelColor=050505) |
| 🎮 | **ECHOES** | A 2D puzzle-platformer for the browser | ![](https://img.shields.io/badge/status-in%20the%20lab-8957e5?style=flat-square&labelColor=050505) |

### 🔬 Under the hood: how Impostr reaches a verdict

```mermaid
flowchart LR
    A([🔗 Suspicious URL / domain]) --> B{{Aggregation layer}}
    B --> C1[URLhaus]
    B --> C2[PhishTank]
    B --> C3[OpenPhish]
    B --> C4[crt.sh]
    B --> C5[WHOIS · DNS · SSL]
    C1 & C2 & C3 & C4 & C5 --> D[Normalize responses]
    D --> E([🧾 One verdict view])
    D --> F([🕸️ Infrastructure graph])
    G([✉️ Pasted scam text]) --> H[AI text analyzer] --> E
```

### 🏠 Under the hood: why DORMEX can't double-book a bed

```text
 student clicks "confirm seat"
        │
        ▼
 server checks its OWN clock (client time & priority = untrusted)
        │
        ▼
 PostgreSQL partial unique indexes
   ├─ one CURRENT allocation per seat    / cycle
   ├─ one CURRENT allocation per student / cycle
   └─ one active turn per pool
        │
        ▼
 conflict? the database rejects it, not the UI
```

## 🧰 Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,java,py,js,ts,react,nextjs,nodejs,express,fastapi,php,postgres,mysql,firebase,tailwind,git,github,vercel,linux&perline=10" />
</p>

<details>
<summary><b>🔍 Full breakdown</b></summary>
<br>

| Domain | Tools |
|---|---|
| **Languages** | C, C++, Java, Python, JavaScript, TypeScript, SQL |
| **Frontend** | React, Next.js, React Native (Expo), Tailwind CSS, HTML5, CSS3 |
| **Backend & data** | Node.js, Express, FastAPI, PHP, PostgreSQL, MySQL, Firebase |
| **AI** | Generative AI, LLM integration, prompt engineering, OpenCV, OCR |
| **Security** | API security, threat-intel APIs, WHOIS/DNS/SSL analysis, CTFs |
| **Desktop & tools** | Electron, pdf-lib, Git, Figma |

</details>

## 🗂️ Side Quests

| Project | Description | Stack |
|---|---|---|
| 🎓 **LoopAngan Certificate Generator** | Desktop app that bulk-generates verifiable course certificates from Excel data | Electron, React, pdf-lib |
| 📋 **TaskBuddy** | Student attendance and productivity tracker | React Native, Firebase, Redux Toolkit |
| 🧪 **CyberDNA** | Hackathon demo: URL scanning, email analysis, QR decoding, in-browser OCR | HTML, React, CDN APIs |
| 🏢 **[Capital Marketing](https://capitalmarketingnp.com)** | Live corporate gifting website for a Nepal-based client | HTML, CSS, JavaScript |
| 🏗️ **[ShubhLabh Construction](https://shubhlabhconstruction.com.np)** | Live company website with service showcase and lead-capture sections | HTML, CSS, JavaScript |

## ✍️ Writing

I write about what I build. Latest: **[From URL to Verdict: Constructing a Multi-Vector Web Threat Forensics Engine](https://medium.com/@saugat.rauniyar.work/from-url-to-verdict-constructing-a-multi-vector-web-threat-forensics-engine-c9eb4722d352?sharedUserId=saugat.rauniyar.work)**, a deep dive into the architecture and design decisions behind Impostr.

## 🏅 Certifications

`API Security · APIsec University (2026)` `Claude Code in Action · Anthropic (2026)` `Prompt Engineering · Infosys Springboard (2026)` `Getting Started with AI on Jetson Nano · NVIDIA (2025)` `Generative AI Literacy · NASSCOM FutureSkills Prime (2025)`

## 🚩 Hidden flag

Since I like CTFs, here's one for you:

```bash
echo 'U2VjTGVhZnt5b3VfcmVhZF90aGVfc291cmNlX25pY2V9' | base64 -d
```

<div align="center">

*"I like building useful things, breaking them, and figuring out how to make them better."*

<img src="https://komarev.com/ghpvc/?username=raw-swag&label=visitors&color=00D9FF&style=flat-square" />

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,60:0b3a4a,100:050505&height=110&section=footer)

</div>