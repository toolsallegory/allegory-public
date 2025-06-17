# Allegory Public

> A public window into what we’ve built—and what’s next.

Hi there. I’m Onur, founder of [Allegory](https://allegory.app), and this is the **first public release** from a platform that has shipped 4,700+ commits of full-stack, AI-native insurance infrastructure behind the scenes.

This repo doesn’t contain product code (yet). It contains something more fundamental: **our blueprint**.

---

## 👀 Why This Exists

In 2024–2025, we built a platform that automates nearly every core insurance function using AI—from underwriting and claims to quoting, multi-region infra, and dynamic agent tooling.  

But until now, *none of it* has been open to the world.

We believe in the power of open ecosystems. So this repo is the first step in:

- Sharing the internal systems we’ve built
- Making parts of it reusable for other builders in regulated and AI-driven verticals
- Starting a real conversation about what *should* be open-source in insurance

---

## 📦 What’s Inside

Right now, just this README. But inside this README is our:

- 🔁 **AI orchestration philosophy**
- 🧠 “Chief of Tech” system prompt
- 🏗️ High-level infrastructure architecture (AWS, Terraform, CI/CD, security)
- 💡 List of potential open-source candidates (see below)
- 🧩 Modular project goals across React, Node, PostgreSQL, and LLM-powered flows

---

## 🛠️ Things We Might Open-Source

We’re not here to dump code for the sake of it. We want to open things that help others ship better, faster, and more securely. Some ideas:

| Candidate | Description |
|----------|-------------|
| `allegory-auth` | JWT-based auth system with SOC-2 ready policies |
| `allegory-terraform` | Fully modular Terraform stack for multi-tenant SaaS |
| `allegory-agent-ui` | Lightweight React UI kit for agent workflows |
| `allegory-llm-core` | LLM-native orchestration framework for vertical AI products |
| `allegory-ci-cd` | GitHub Actions templates for secure deployment to AWS |

Have a preference? Drop it in the [Discussions](https://github.com/toolsallegory/allegory-public/discussions) or open an [Issue](https://github.com/toolsallegory/allegory-public/issues).

---

## 💬 We Want Your Input

This repo is open so we can learn from you.  
Please comment or suggest:

- What parts of Allegory’s infra or codebase are most useful to open?
- Have you built or struggled with similar problems?
- Would you use these components if they were modular + documented?

Create an [Issue](https://github.com/toolsallegory/allegory-public/issues) or reply to [this LinkedIn post](https://www.linkedin.com/in/onur-gungor/) (if that’s where you came from).

---

## 🧠 Our System Prompt (v4.0)

We use an internal “Chief of Tech” AI system that powers our infra decisions. Here's the high-level version:

> _You are an advanced AI model specializing in full-stack web development for complex insurance platforms. Your primary objective is to refactor, modularize, and harden a multi-tenant, multi-region system using React, Node.js, PostgreSQL, and Terraform deployed securely on AWS..._  

[👉 Read the full system prompt here](#) *(optional: link to full prompt in a subfolder if desired)*

---

## 🧭 Our Stack (TL;DR)

| Layer | Tech |
|------|------|
| Frontend | React 18, Context API, CSS Modules |
| Backend | Node.js (Express), Babel |
| Infra | Terraform, GitHub Actions, AWS ECS/Fargate |
| Database | PostgreSQL, multi-tenant schemas |
| Auth | JWT, custom IAM + Cognito hybrid |
| Security | SOC-2 design, VPCs, WAF, KMS, SSL |
| Testing | Jest, Playwright, E2E & CI/CD |

---

## 🔐 Ethos

We don’t believe in “move fast and break things.”  
We believe in **ship fast and fix forever.**  
This public repo is us living that belief.

---

## 🙌 Join Us

If any of this resonates:

- ⭐ Star this repo  
- 🗣️ Join the discussion  
- 🧪 Test things as we publish  
- 🛠️ Or just lurk — that’s cool too

Thanks for being part of something new.

— Onur  
*Founder, Allegory*
