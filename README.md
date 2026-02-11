<h1 align="center">Ruslan T. (WaiperOK)</h1>
<p align="center">Security Engineering | AI Security Platforms | Detection & Response Tooling</p>

<p align="center">
  <a href="https://github.com/WaiperOK"><img src="https://img.shields.io/badge/GitHub-WaiperOK-111827?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/ruslan-t-05238721b/"><img src="https://img.shields.io/badge/LinkedIn-Ruslan%20T.-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://huggingface.co/Waiper"><img src="https://img.shields.io/badge/HuggingFace-Waiper-f59e0b?style=for-the-badge" alt="HuggingFace" /></a>
</p>

## Flagship Projects

| Project | Stack | Focus |
|---|---|---|
| [nexus-security-platform](https://github.com/WaiperOK/nexus-security-platform) | Meta | Portfolio hub, architecture map, roadmap |
| [llm-gateway-control-plane](https://github.com/WaiperOK/llm-gateway-control-plane) | Go | LLM routing, policy enforcement, budget and audit controls |
| [soc-llm-triage-lab](https://github.com/WaiperOK/soc-llm-triage-lab) | Python | SOC incident triage, explainable scoring, playbook retrieval |
| [cloud-drift-guardian](https://github.com/WaiperOK/cloud-drift-guardian) | Rust | Desired-vs-actual cloud drift detection with risk scoring |
| [SecFlow](https://github.com/WaiperOK/SecFlow) | Python | Multi-scanner DevSecOps orchestration framework |
| [API-Shield](https://github.com/WaiperOK/API-Shield) | Python | Deterministic API posture scanning for AppSec workflows |
| [argus](https://github.com/WaiperOK/argus) | TypeScript/Next.js | Analyst UI with deterministic malware risk scoring |

## Engineering Standards

- Deterministic core logic for security-critical paths
- CI pipelines with tests and quality gates
- Architecture docs + threat model + security policy
- Tagged releases and changelog discipline
- API-first design with observability (`/metrics`) where applicable

## Portfolio Architecture

```mermaid
flowchart LR
  HUB["nexus-security-platform"] --> A["llm-gateway-control-plane"]
  HUB --> B["soc-llm-triage-lab"]
  HUB --> C["cloud-drift-guardian"]
  HUB --> D["SecFlow"]
  HUB --> E["API-Shield"]
  HUB --> F["argus"]
```

## Current Focus

- AI-native security control planes
- SOC automation with explainable outputs
- Cloud posture drift and risk prioritization
- Production-grade repo quality and release discipline

## Contact

- GitHub: [@WaiperOK](https://github.com/WaiperOK)
- LinkedIn: [ruslan-t-05238721b](https://www.linkedin.com/in/ruslan-t-05238721b/)
- Hugging Face: [Waiper](https://huggingface.co/Waiper)
