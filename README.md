# Chaithu anv

**Security Engineer** — AppSec · Cloud Security · DevSecOps · Threat Intel

Building and hardening security programs on an AWS-centric stack with Jenkins CI/CD. Finishing a **Georgia Tech OMS Cybersecurity** degree (**graduating December 2026**; capstone: AI-powered threat intel pipeline). Off hours: VAPT study toward **PNPT** — in progress, applied AI × security, and automating bug-bounty recon with Claude Code.

[![GitHub](https://img.shields.io/badge/GitHub-Chaithu5-181717?style=flat-square&logo=github)](https://github.com/Chaithu5)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-chaitanya--anv-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/chaitanya-anv/)

---

## What I'm working on

### [AWS Exposure Monitor](https://github.com/Chaithu5/AWS-Exposure-Monitor)

Read-only continuous monitoring for internet-exposed AWS services. Discovers public assets in an owned account, checks a fixed high-risk port list, attributes each finding to the real resource (not just the security group), and diffs runs for `NEW` / `CHANGED` / `RESOLVED`.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![boto3](https://img.shields.io/badge/boto3-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

```mermaid
flowchart LR
  A[Discover] --> B[Verify]
  B --> C[Attribute]
  C --> D[Diff]
  D --> E[Report]
```

- **Product security at scale** — vulnerability remediation and SCA / SAST / API-security tooling across the delivery pipeline.
- **OMS Cybersecurity (Georgia Tech)** — degree in progress, graduating **December 2026**; capstone: AI-powered threat intel pipeline.
- **VAPT / PNPT** — offensive practice toward PNPT ![in progress](https://img.shields.io/badge/in_progress-555?style=flat-square).
- **Bug bounty recon automation** — Claude Code skills for a `subfinder → httpx → nuclei` pipeline ![experimental](https://img.shields.io/badge/experimental-555?style=flat-square).
- **Applied AI × security** — prompt injection, LLM red-teaming, securing AI-assisted systems ![learning](https://img.shields.io/badge/learning-7C3AED?style=flat-square).

<details>
<summary><strong>Focus areas</strong></summary>

| Area | How I spend time |
|---|---|
| AppSec / DevSecOps | SCA, SAST, secret scanning, pipeline gates (Snyk, SonarCloud, Gitleaks, Trivy, Checkov, Akto) |
| Cloud security | AWS exposure & misconfiguration; GuardDuty / SIEM-adjacent detection work |
| Threat intel | Capstone — AI-assisted collection / triage pipeline |
| Offense | VAPT lab work toward PNPT; Burp, nmap, Metasploit, BloodHound, nuclei |

</details>

---

## Skills

| Daily driver | Building toward | Platform |
|:---|:---|:---|
| [![Python](https://skillicons.dev/icons?i=py)](https://www.python.org/) [![JS](https://skillicons.dev/icons?i=js)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Bash](https://skillicons.dev/icons?i=bash)](https://www.gnu.org/software/bash/) | ![Burp](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square) ![nmap](https://img.shields.io/badge/nmap-4682B4?style=flat-square) ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square) | [![AWS](https://skillicons.dev/icons?i=aws)](https://aws.amazon.com/) [![Terraform](https://skillicons.dev/icons?i=terraform)](https://www.terraform.io/) |
| ![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=flat-square&logo=snyk&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square) ![Akto](https://img.shields.io/badge/Akto-API_Security-0B1F33?style=flat-square) | ![BloodHound](https://img.shields.io/badge/BloodHound-E03C31?style=flat-square) ![nuclei](https://img.shields.io/badge/nuclei-3DDC84?style=flat-square) | [![Docker](https://skillicons.dev/icons?i=docker)](https://www.docker.com/) [![Kubernetes](https://skillicons.dev/icons?i=kubernetes)](https://kubernetes.io/) |
| ![GuardDuty](https://img.shields.io/badge/AWS_GuardDuty-FF9900?style=flat-square&logo=amazon-aws&logoColor=white) ![Elastic](https://img.shields.io/badge/Elastic_SIEM-005571?style=flat-square&logo=elastic&logoColor=white) ![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white) | ![PNPT](https://img.shields.io/badge/PNPT-in_progress-555?style=flat-square) ![AI×Sec](https://img.shields.io/badge/AI_for_Security-learning-7C3AED?style=flat-square) | ![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white) |
| ![Gitleaks](https://img.shields.io/badge/Gitleaks-1A1A2E?style=flat-square) ![Checkov](https://img.shields.io/badge/Checkov-0B2E59?style=flat-square) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) | ![Claude](https://img.shields.io/badge/Claude_Code-recon_automation-CC785C?style=flat-square) | [![Linux](https://skillicons.dev/icons?i=linux)](https://www.kernel.org/) [![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com/) |

How I triage: alert/finding → validate exploitability (not just the severity label) → find root cause → clear, neutral write-up.

---

## Public work

Most of my day-to-day security work lives in private/employer repos — what's here is personal projects and practice.

| Repo | Description |
|---|---|
| [**AWS-Exposure-Monitor**](https://github.com/Chaithu5/AWS-Exposure-Monitor) | AWS internet-exposure monitor: inventory, high-risk port reachability, resource attribution, run diffs. |
| [**portfolio-website**](https://github.com/Chaithu5/portfolio-website) | Personal site (HTML/CSS/JS/Bootstrap) — [live](https://chaithu5.github.io/portfolio-website/). |

<details>
<summary><strong>Earlier projects</strong></summary>

| Repo | Description |
|---|---|
| [Sorting-Visualizer](https://github.com/Chaithu5/Sorting-Visualizer) | Visualizes bubble, insertion, selection, merge, and quick sort. |
| [DMA-project](https://github.com/Chaithu5/DMA-project) | World Happiness Index 2020 — visualize, cluster, predict. |
| [Audiobook](https://github.com/Chaithu5/Audiobook) | PDF → speech (PyPDF2 / gTTS / Streamlit). |
| [Speech-to-Text](https://github.com/Chaithu5/Speech-to-Text) | Mic → text via SpeechRecognition. |
| [Face-Detection](https://github.com/Chaithu5/Face-Detection) | Minimal OpenCV face-detection demo. |
| [Public-Face-mask-Detection](https://github.com/Chaithu5/Public-Face-mask-Detection) | Mask detection with OpenCV + TensorFlow. |
| [Traffic-Sign-recognition](https://github.com/Chaithu5/Traffic-Sign-recognition) | Traffic-sign recognition. |
| [Electric-Billing-System](https://github.com/Chaithu5/Electric-Billing-System) | DBMS project (PHP). |
| [Simple-Chatbox-using-NLTK](https://github.com/Chaithu5/Simple-Chatbox-using-NLTK) | Small NLTK chatbot experiment. |

</details>

---

## GitHub stats

<img width="320" src="https://github-readme-stats.vercel.app/api?username=Chaithu5&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true" alt="Chaithu5 GitHub stats" />
<img width="260" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chaithu5&layout=compact&theme=dark&hide_border=true&langs_count=6" alt="Chaithu5 top languages" />

---

## Contact

- GitHub: [@Chaithu5](https://github.com/Chaithu5)
- LinkedIn: [chaitanya-anv](https://www.linkedin.com/in/chaitanya-anv/)
