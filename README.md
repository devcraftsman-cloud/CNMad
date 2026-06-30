# CNMad — Cloud Native Madison Agentic Platform

Cloud Native Madison’s official open-source playground for:

- **Hermes Agent CLI** — natural language → System Design Document (SDD)
- **MCP Meta-Agent** — agents that build and orchestrate other agents
- **Community Agent Fleet** — automation for jobs, posts, newsletters
- **Autonomous DevOps Loop** — agents embedded in CI/CD and platform engineering
- **CNMad Knowledge Base** — docs, patterns, and meetup materials

## Vision

CNMad bridges:

- Platform Engineering  
- Cloud Native Infrastructure  
- Autonomous Agents  
- Community Automation  

This repo powers live meetups, online workshops, and portfolio-grade demos.

---

## Monorepo Structure

cnmad/
├─ docs/
├─ packages/
│  ├─ hermes-cli/
│  ├─ mcp-meta-agent/
│  ├─ community-fleet/
│  └─ autonomous-devops-loop/
└─ roadmap/

Code

---

## Getting Started

Clone the repo:

```bash
git clone https://github.com/<your-user>/cnmad.git
cd cnmad
Install dependencies (later steps will walk you through this):

bash
pnpm install
Run Hermes CLI:

bash
cd packages/hermes-cli
pnpm start
Contributing
We welcome:

New agents

New SDD templates

New community automation workflows

Bug fixes and docs improvements

Open an issue or PR with:

Clear description

Architecture impact

Demo steps
