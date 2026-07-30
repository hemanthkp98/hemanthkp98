<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=6E40C9&center=true&vCenter=true&width=700&lines=Hey+there%2C+I'm+Hemanth+%F0%9F%91%8B;I+build+AI-native+DevOps+tools;Kubernetes+%C3%97+LLMs+%C3%97+Platform+Eng;Making+infra+talk+back+%F0%9F%9A%80" alt="Typing SVG" />

<br/>

[![GitHub followers](https://img.shields.io/github/followers/hemanthkp98?style=for-the-badge&logo=github&logoColor=white&color=6E40C9&labelColor=0d1117)](https://github.com/hemanthkp98?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=hemanthkp98&style=for-the-badge&color=6E40C9&label=PROFILE+VIEWS)](https://github.com/hemanthkp98)

</div>

---

## 🧠 About Me

I'm an engineer obsessed with the intersection of **AI and infrastructure** — building tools that let teams talk to their clusters, automatically remediate vulnerabilities, and get intelligent insights from their systems without drowning in YAML and dashboards.

- 🔭 &nbsp; Currently building **AI-native Kubernetes tooling**
- 🤖 &nbsp; Heavy user of **LangGraph**, **Claude**, and **Gemini** for agentic pipelines
- ☸️ &nbsp; Deep into **Kubernetes internals**, multi-cluster management, and platform engineering
- 🔐 &nbsp; Passionate about **DevSecOps** — especially automated vulnerability remediation
- ⚡ &nbsp; Believe great developer tools should feel like **superpowers**, not chores

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ☸️ [KubeNova](https://github.com/hemanthkp98/kubenova)

> **Talk to your cluster. See it live. Fix it fast.**

A production-ready, open-source AI Kubernetes assistant that lets you interact with your clusters using **natural language** — right from a browser.

**✨ Highlights**
- 💬 Natural language → `kubectl` with dry-run preview before anything runs
- 📡 Live resource panel via WebSocket streaming
- 🔀 Multi-cluster context switching
- 🔒 4-tier risk classification & safety gate (LangGraph)
- 📋 Full audit log with CSV export
- 🔌 Pluggable LLMs: Claude · Gemini · GPT · Ollama

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square&logo=chainlink&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

[![Stars](https://img.shields.io/github/stars/hemanthkp98/kubenova?style=for-the-badge&color=6E40C9&labelColor=0d1117)](https://github.com/hemanthkp98/kubenova/stargazers)

</td>
<td width="50%" valign="top">

### 🔐 [Trivy Remediation Agent](https://github.com/hemanthkp98/trivy-remediation-agent)

> **Zero-touch vulnerability remediation — scan to PR in one pipeline step.**

An end-to-end agentic pipeline that reads a Trivy vulnerability report, uses an LLM to generate precise file patches, and opens a Pull Request — **no human in the fix loop**.

**✨ Highlights**
- 🔍 Parses Trivy JSON v2 reports (OS pkgs, Python, Node.js, Go)
- 🤖 LLM (Claude / Gemini) generates search→replace patches
- 🧪 Verify-and-self-heal loop — retries if patched code breaks
- 🔀 GitHub & GitLab PR/MR creation built-in
- 🔄 Drop-in GitHub Actions & GitLab CI pipeline templates
- 🏃 Dry-run mode for safe previewing

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

[![Stars](https://img.shields.io/github/stars/hemanthkp98/trivy-remediation-agent?style=for-the-badge&color=6E40C9&labelColor=0d1117)](https://github.com/hemanthkp98/trivy-remediation-agent/stargazers)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔌 [OpenLens Chat Extension](https://github.com/hemanthkp98/openlens-chat-extension)

> **AI Chat sidebar — right inside your Kubernetes IDE.**

A renderer-only Lens Extension that embeds a persistent AI chat panel inside the cluster view of OpenLens or FreeLens. Ask questions in plain English, get answers about your active cluster in real time.

**✨ Highlights**
- 🧩 Zero-config Lens extension — install & chat
- 🔄 Automatic kubeconfig context + namespace injection
- 💾 Conversation history persisted per cluster (localStorage)
- 🪶 Zero added npm dependencies on the Lens runtime
- 🔑 Supports Gemini and OpenAI backends

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)

[![Stars](https://img.shields.io/github/stars/hemanthkp98/openlens-chat-extension?style=for-the-badge&color=6E40C9&labelColor=0d1117)](https://github.com/hemanthkp98/openlens-chat-extension/stargazers)

</td>
<td width="50%" valign="top">

### 🧰 What I'm Working On Next

<br/>

```
🔭  Expanding KubeNova with incident auto-healing
🔐  Multi-cloud vulnerability scanning pipelines  
📊  AI-driven observability & alerting
🤖  More agentic DevSecOps automation
```

<br/>

> *"The best infrastructure tool is the one you forget is there."*

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**AI / LLMs**

![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=for-the-badge&logo=chainlink&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**Cloud & Infra**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**Backend / Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=websocket&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=hemanthkp98&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6E40C9&icon_color=6E40C9&text_color=c9d1d9&include_all_commits=true&count_private=true" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hemanthkp98&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6E40C9&text_color=c9d1d9&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=hemanthkp98&theme=tokyonight&hide_border=true&background=0d1117&stroke=6E40C9&ring=6E40C9&fire=FF6B35&currStreakLabel=6E40C9&sideLabels=c9d1d9&dates=666e80" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=hemanthkp98&theme=tokyonight&no-frame=true&row=1&column=7&no-bg=true&margin-w=4" />

</div>

---

## 📬 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@hemanthkp98-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hemanthkp98)
[![Email](https://img.shields.io/badge/Email-hemanthkp98@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hemanthkp98@gmail.com)

<br/>

*Open to collaborations on AI-native DevOps tooling, Kubernetes platform engineering, and developer productivity tools.*

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6E40C9&height=100&section=footer&fontSize=14" />

</div>
