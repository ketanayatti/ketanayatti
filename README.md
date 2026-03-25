```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║   $ whoami                                                    ║
║   > Ketan Ayatti                                              ║
║                                                               ║
║   $ cat mission.txt                                           ║
║   > Make deployments so boring, nobody talks about them.      ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

<br/>

I'm a **DevOps Engineer** obsessed with one thing:  
**systems that fix themselves before anyone notices they broke.**

Not "I know Docker." Not "I've used Jenkins."  
I mean — I built a deployment platform that detects failure, reroutes traffic,  
and rolls back to stable — with zero human involvement.  
At 3am. Without waking anyone up.

That's the bar I hold myself to.

---

## What I've Actually Built

> Not tutorial projects. Not course assignments.  
> Real problems I found, got annoyed by, and built solutions for.

<br/>

**① An LLM running on $0/month** &nbsp;·&nbsp; [↗ repo](https://github.com/ketanayatti/Self-Hosted-AIOps-Agent-on-AWS)

Everyone's paying OpenAI. I got curious — *what's the minimum viable self-hosted AI agent?*  
Ran TinyLlama on a t2.micro. 1GB RAM. Had to fake an extra 2GB with swap.  
Exposed it via FastAPI. Live CPU/memory monitoring. Shell execution. Health checks.  
Total external AI cost: **$0**.

```
EC2 t2.micro (1GB RAM)
├── llama.cpp → TinyLlama 1.1B (quantized)
├── 2GB swap  → stable inference within memory limits
├── FastAPI   → /metrics /query /exec /health
└── systemd   → survives reboots, production-ready
```

<br/>

**② A deployment platform that argues back** &nbsp;·&nbsp; [↗ repo](https://github.com/ketanayatti/Autonomous-Self-Healing-Deployment-Platform)

Blue-green deployment isn't new. But most implementations still need  
a human to say "okay, switch." Mine doesn't.

Health checks pass → NGINX flips to green. Automatically.  
Health checks fail → stays on blue. Rolls back. Sends no pages at 3am.

```
push code
    │
    ▼
green container spins up
    │
    ├─ health check PASSES → nginx switches → blue retired ✓
    │
    └─ health check FAILS  → nginx stays   → green killed ✗
                                              no downtime.
                                              no humans paged.
```

<br/>

**③ A full platform with everything wired together** &nbsp;·&nbsp; [↗ repo](https://github.com/ketanayatti/communiatec-devops-platform)

Real-time messaging. Collaborative code editor. Secure file vault. Admin dashboard.  
Built the whole thing — then built the deployment layer on top of it.  
Jenkins pipeline. Docker. NGINX on Linux. One push ships everything.

<br/>

**④ AI interviews that actually adapt** &nbsp;·&nbsp; [↗ repo](https://github.com/ketanayatti/ai-mock-interview)

Upload your resume → platform reads it → generates role-specific questions →  
runs your answers through Gemini + OpenAI + Cohere → scores you.  
Branch-aware pipeline: dev branch → staging, main → production. Automatically.

---

## The Internship (What I Do at IonIdea)

I joined as an intern. I've been running infrastructure.

- Hardened Linux servers from scratch — SSH key-only, UFW rules, role-based access.  
  Eliminated password-based login across all dev instances.  
  *(It's 2026. Passwords are a vulnerability.)*
- Built a Jenkins pipeline that took an 8-command manual deploy  
  and turned it into a single git push.
- Containerized a full-stack app with Docker Compose —  
  "works on my machine" became "works everywhere, always."
- Automated every database backup. Zero manual effort. Scheduled recovery points.  
  The kind of thing you only miss when it's gone.

---

## Stack (what I actually reach for, not what looks good in a list)

```
When I need to automate          →  Jenkins, GitHub Actions, Bash
When I need to containerize      →  Docker, Docker Compose
When I need a server             →  Linux (Ubuntu), AWS EC2
When I need traffic routing      →  NGINX, Apache
When I need observability        →  Docker logs, Apache logs, custom health endpoints
When I need to write logic       →  Python, Node.js
Currently learning               →  Kubernetes, Terraform
Next cert on the wall            →  AWS Solutions Architect Associate
```

---

## Certifications

```
✓  Oracle Cloud Infrastructure 2025 AI Foundations Associate
```

---

## GitHub Activity

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ketanayatti&theme=tokyonight&hide_border=true&background=0D1117&ring=00C2FF&fire=00C2FF&currStreakLabel=00C2FF"/>
</div>

---

## One Thing I Believe

Most people treat reliability as something you add at the end.  
A monitoring alert here. A restart policy there.

I think reliability is an architecture decision you make on day one.  
Health checks aren't afterthoughts. Rollback isn't a plan B.  
They're the system.

*"The goal isn't uptime. The goal is a system that doesn't need you to maintain its uptime."*

---

## If You Want to Talk

I'm actively looking for full-time **DevOps / SRE / Cloud Infrastructure** roles.  
Bengaluru, Pune, Hyderabad — or remote.

&nbsp;[LinkedIn](https://www.linkedin.com/in/ketanayatti/) &nbsp;·&nbsp; [Portfolio](https://ketanayatti.netlify.app/) &nbsp;·&nbsp; kethanayatti333@gmail.com

<br/>

```
$ status
> open to work. respond within 24hrs. let's build something reliable.
```
