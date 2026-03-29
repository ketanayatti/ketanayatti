<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║  > whoami                                                        ║
║                                                                  ║
║    Ketan Ayatti — Software Engineer                              ║
║    Backend · Cloud Infrastructure · Systems that self-heal       ║
║                                                                  ║
║  > cat philosophy.txt                                            ║
║    "If it needs constant human attention, it isn't finished."    ║
╚══════════════════════════════════════════════════════════════════╝
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ketanayatti/)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://ketanayatti.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kethanayatti333@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=for-the-badge)](mailto:kethanayatti333@gmail.com)

</div>

---

## `$ cat about.txt`

Most engineers stop when the code runs.

I care about what comes **after** — how it deploys, how it survives failure, and how little human effort it needs to keep running.

My focus is on **backend systems, cloud infrastructure, and operational reliability** — the unglamorous layer where production actually lives.

---

## `$ ls ./projects`

### ⟶ [Self-Hosted AIOps Agent on AWS](https://github.com/ketanayatti/Self-Hosted-AIOps-Agent-on-AWS)

> *A local AI agent that monitors and acts — without phoning home.*

Built a lightweight autonomous system on a constrained EC2 instance that:
- Monitors CPU and memory metrics in real time
- Executes controlled system commands via API
- Runs a **local LLM (TinyLlama / llama.cpp)** — no external API calls, no data leaving the machine

```
EC2 (low resource)
 ├── FastAPI backend
 ├── llama.cpp  ← local inference
 ├── system tools
 └── /monitor  /execute  /chat  endpoints
```

`FastAPI` `llama.cpp` `TinyLlama` `Python` `AWS EC2` `Linux`

---

### ⟶ [Autonomous Self-Healing Deployment Platform](https://github.com/ketanayatti/Autonomous-Self-Healing-Deployment-Platform)

> *Deployments that watch themselves — and roll back when something breaks.*

No one should be paged at 2 AM because a deploy went wrong. This system handles it:

```
git push
    │
    ▼
 [Green] starts
    │
    ├── health check PASS ──▶ NGINX routes traffic → live
    └── health check FAIL ──▶ auto rollback → old version restored
```

Zero manual intervention. Zero downtime if green is healthy.

`Docker` `NGINX` `Bash` `Python` `Health Checks` `Blue-Green Deploy`

---

### ⟶ [Communiatec — Real-Time Collaboration Platform](https://github.com/ketanayatti/communiatec-devops-platform)

> *Not just a chat app. A full production system.*

- Real-time messaging with WebSockets
- Multi-user sessions with authentication
- Deployed via **Docker + Jenkins + NGINX** — the whole pipeline

`Node.js` `MongoDB` `Redis` `Docker` `Jenkins` `NGINX` `WebSockets`

---

### ⟶ [AI Mock Interview Platform](https://github.com/ketanayatti/ai-mock-interview)

> *Backend-first AI tooling — sessions, evaluation, deployment.*

- Generates structured interview flows
- Tracks and persists sessions
- Evaluates user responses with AI-backed scoring

Built for the workflow, not just the interface.

`Python` `FastAPI` `LLM Integration` `Session Management`

---

## `$ cat experience.txt`

### IonIdea — Software Engineering Intern

Worked across the full stack in a real product environment:

- Built client-facing frontend modules
- Set up and maintained **CI/CD pipelines with Jenkins**
- Containerized services with **Docker**
- Configured **Linux** environments and server infrastructure
- Supported deployment debugging and release workflows
- Currently building a full-stack system with **React + FastAPI**

---

## `$ cat stack.json`

```json
{
  "backend":     ["Node.js", "Python", "FastAPI"],
  "databases":   ["MongoDB", "Redis", "MySQL"],
  "deployment":  ["Docker", "Jenkins", "NGINX", "Apache"],
  "cloud":       ["AWS (EC2, project-based)"],
  "systems":     ["Linux"],
  "learning":    ["Kubernetes", "Terraform"]
}
```

---

## `$ cat github-stats.md`

<div align="center">

![Ketan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ketanayatti&show_icons=true&theme=github_dark&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ketanayatti&layout=compact&theme=github_dark&hide_border=true&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

![GitHub Streak](https://streak-stats.demolab.com?user=ketanayatti&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)

</div>

---

## `$ cat mindset.txt`

Systems fail not because of bad logic —  
but because of what happens **around** the logic.

```
What I think about most:
  ├── Deployment pipelines that don't require babysitting
  ├── Services that recover without a runbook
  ├── Environments that behave the same everywhere
  └── Reducing the gap between "it works" and "it runs in prod"
```

---

<div align="center">

```
$ ./contact.sh
──────────────────────────────────────
  LinkedIn  →  linkedin.com/in/ketanayatti
  Portfolio →  ketanayatti.netlify.app
  Email     →  kethanayatti333@gmail.com
──────────────────────────────────────
  status: open to work
  roles:  backend · systems · cloud · devops-adjacent
──────────────────────────────────────
```

*Available for software engineering roles in backend, systems, and cloud infrastructure.*

</div>
