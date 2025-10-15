# Allegory OS - AI-Native Operating System

---
    ╔═══════════════════════════════════════════════════════════════════╗
    ║                                                                   ║
    ║         _    _ _                                   ___  ____      ║
    ║        / \  | | | ___  __ _  ___  _ __ _   _     / _ \/ ___|      ║
    ║       / _ \ | | |/ _ \/ _` |/ _ \| '__| | | |   | | | \___ \      ║
    ║      / ___ \| | |  __/ (_| | (_) | |  | |_| |   | |_| |___) |     ║
    ║     /_/   \_\_|_|\___|\__, |\___/|_|   \__, |    \___/|____/      ║
    ║                       |___/            |___/                      ║
    ║                                                                   ║
    ║                     AI-Native Operating System                    ║
    ║                        https://allegory.app                       ║
    ╚═══════════════════════════════════════════════════════════════════╝
---

# Allegory
    > AI-Native operating system for risk and (re)insurance
    > Insurance distribution with 80% lower costs
    > Transforming insurance with machine intelligence

---

## What We Do

Allegory is an AI-native insurance distribution platform that automates the entire insurance lifecycle—from customer acquisition to policy binding to claims processing—at a fraction of traditional costs.

**The Problem:**
Selling $100M in insurance costs $12-15M in operational expenses. That's 12-15¢ of every premium dollar spent on overhead, requiring 100-200 staff per $100M in sales.

**Our Solution:**
The same $100M in sales costs $4-5M with Allegory. Instant quotes. Immediate binding. Accident prevention. Customer protection. Zero labour per transaction.

---

## Technology Stack

### *AllegoryOS*: Hybrid AI-Native Architecture

AllegoryOS combines Large Language Models such as Claude and ChatGPT for sophisticated reasoning with Specialized Language Models (AI-1 & AI-2) for domain-specific execution.

Our AI-2 model executes 1,000+ enterprise operations, including billing, underwriting, claims processing, regulatory filings, and reinsurance across 13 languages and dialects. Visit https://allegory.app/supported-countries for more information.

### Core Infrastructure

| Layer | Technology | Details |
|-------|-----------|---------|
| Frontend | React 19, Context API, CSS Modules, HTML | Native document metadata, mobile-first responsive design, full design library for any dashboard requirements |
| Backend | Node.js 24, Serverless Lambda Functions | Custom-built event-driven architecture similar to Apache Kafka |
| Containerization | Docker + Nginx Multi-stage | Automated GitHub Actions → AWS ECR → ECS pipeline |
| Infrastructure | Terraform IaC, AWS Multi-region | VPC isolation, auto-scaling, SSL automation, global CDN, CloudWatch dashboards for every service |
| Database | DynamoDB + Redis | 100+ scalable NoSQL tables, high-performance caching |
| API Architecture | RESTful + WebSocket | Rate limiting, API key relationships between parent/sibling/child organizations, real-time communication, 1,000+ business app commands serviced from 5 API endpoints |
| AI/ML | Hybrid LLM/SLM Architecture | 60+ specialized agents, real-time streaming, multilingual processing, ~20B-token *Synthetic Insurance Universe* |
| Authentication | Custom JWT + Cognito Hybrid + Passwordless Access | Role-based access, session management, enterprise SSO |
| Security | SOC 2 Type II, WAF, KMS | VPC isolation, encryption at rest/transit, automated monitoring, in-house fraud models |
| CI/CD | GitHub Actions, Automated Testing | Environment-based deployments, zero-downtime updates |
| Compliance | GDPR, HIPAA, PCI DSS Ready | Built-in regulatory compliance across all supported regions |

### Development & Deployment Capabilities

**Automated Project & Digital Channel Generation:**

Working with the Allegory WebCraft Agent, our system delivers complete business application deployment in 15-30 minutes through our proprietary React 19 generation framework:

    > Complete business-to-production pipeline
    > ./create-react19-project-v2.sh [project-name] [project-secret] [domain.com]

Once you purchase AllegoryOS, all you need to do is talk to our WebCraft Agent and then run the above command on your local machine to make it ready for deployment. Or simply talk to us and let us handle the automated building and deployment on your behalf.

**Example:**
Say you want to create a new digital channel to target pet owners with your new brand called "Frankie Pet Insurance."

After you describe your new venture to our WebCraft AI Agent, making it live and acquiring new pet owners is as simple as running the command below:

    > ./create-react19-project-v2.sh frankie SecretByWebCraft frankiepetinsurance.com


*Please note that you must use the secret provided by WebCraft agent along with the same project name and domain address.*

Once prompted, authorize GitHub repository creation and codebase access rules.

After this step, you will be directed to the first version of your website at the dev.frankiepetinsurance.com domain. This process may take up to 24 hours depending on how quickly the CDN and DNS setup propagates for your new website. However, in our experience, it usually completes within 60 minutes.

No code. No integration.

Contact us at ai1@allegory.app to learn more.

## Intelligent Requirements Processing

Our system automatically processes your conversation history with the WebCraft Agent, translating natural language requirements into technical specifications. 

The platform intelligently selects industry-specific templates and applies sector-specific best practices for insurance, healthcare, legal, and other regulated industries. 

Core functionality is implemented first, with built-in expansion capabilities that grow with your business needs.

## Complete Application Stack Generation

**Frontend Architecture:**

Every generated application is built on React 19 with native document metadata, eliminating unnecessary dependencies like react-helmet. 

The CSS Modules Design System includes utility classes and custom properties that maintain consistency across your entire application. 

Multi-language internationalization comes standard, supporting 13 languages with context-based translation that adapts to cultural nuances. 

The mobile-first responsive design consistently achieves 95+ Lighthouse performance scores, while React Context API manages SEO, language preferences, authentication, theming, and notifications seamlessly.

**Backend Infrastructure:**

The backend combines Node.js 24 with Nginx in a multi-stage Docker containerization setup. 

Our event-driven architecture provides access to over 1,000 commands with auto-scaling capabilities. 

The API Gateway handles both RESTful and WebSocket endpoints with intelligent rate limiting, while DynamoDB tables use multi-tenant schemas backed by a Redis caching layer for optimal performance. 

Custom JWT authentication integrates with Cognito for a hybrid implementation that balances security with user experience.

Across the core technology stack of Allegory, we use our own hybrid retrieval architecture: Lexical Information Retrieval through BM25 Algorithms, Signal-aware Reranking, and Event-Sourced Freshness.

You can read more about our engineering at https://allegory.app/news/plato-search-beyond-vector-embeddings-production-retrieval

## Enterprise AWS Infrastructure (Terraform-Managed)
We've coined the term "Predictive Infrastructure," which represents the main ideation behind AllegoryOS succinctly. 

In short: Our OS is a million perpetual text rivers flowing in parallel where each output token by the Large Language Model is an executable function.

**Networking & Security:**

The VPC architecture spans multiple availability zones with carefully segregated public and private subnets. 

Application Load Balancers handle SSL termination and health checks, while WAF protection guards against common web attacks. 

KMS encryption secures data both at rest and in transit, and Route53 DNS includes health checks with automated failover to ensure continuous availability.

**Deployment & Monitoring:**

GitHub Actions powers the CI/CD pipeline with automated testing and deployment workflows. 

Containerized deployment through AWS ECR and ECS enables zero-downtime updates. 

CloudWatch integration provides comprehensive metrics, logging, and alerting across all services. 

SSL certificates renew automatically, and global CDN integration ensures fast content delivery worldwide.

You can read more about our infrastructure engineering at https://allegory.app/news/predictive-infrastructure-every-token-becomes-executable

## Business-Specific Feature Integration

Industry templates are automatically applied based on your business requirements. 

Insurance implementations include quote calculators, policy management, claims processing workflows, and regulatory compliance tools. 

Healthcare applications feature HIPAA-compliant patient portals, appointment booking, and insurance verification. 

Legal practices get document management, consultation scheduling, and case tracking systems. 

Real estate platforms include lead capture, virtual tours, and market analysis. 

Professional services receive client portals, project management, and automated billing. 

E-commerce sites are equipped with shopping carts, payment processing, inventory management, and order tracking.

The AI agent ecosystem integrates seamlessly through a real-time chat interface powered by WebSocket communication. Multi-agent coordination handles specialized business operations, with streaming AI responses delivered through chunked message processing. Cross-language support provides automatic translation capabilities, ensuring your business can serve customers in their preferred language.

## Post-Deployment Automation

**Immediate Business Operations:**

Domain configuration happens automatically with DNS propagation and SSL activation. We acquire new domains on your behalf or you can simply choose your existing domains managed by Allegory. In either case, your existince internet presence will not be impacted and the change is seamless.

Email and SMS integration enables customer communication workflows from day one.

Analytics setup includes conversion tracking and performance monitoring, while SEO optimization implements structured data, sitemaps, and meta tag generation to maximize your online visibility.

**Scalability & Maintenance:**

Auto-scaling configuration adapts from startup traffic levels to enterprise scale without requiring architecture changes. Backup and recovery procedures are automated with disaster recovery capabilities built in. At every new deployment, we automatically enable multi-region subnets over the cloud to ensure service stays uninterrupted.

However, for heavy enterprise use cases with portfolios over 5 million customers, we suggest carriers consider our hybrid on-site and cloud solutions simultaneously.

Security monitoring includes threat detection with automated response protocols. Performance optimization leverages CDN caching and database query optimization to maintain fast response times as your business grows.

## Technical Performance Metrics

Deployment takes 15-30 minutes from initial conversation to live website. 

Global load times stay under 5 seconds worldwide through CDN optimization. The 5-second cases occur when we need to initialize services from cold start and when the initial user bootstrapping takes more time to prevent potential threats and attacks.

After various volumetric attacks and load-balance testings, we deem that the architecture can support over 1 million concurrent users with auto-scaling Lambda functions. 

We maintain a 98%+ uptime guarantee through automated monitoring and recovery systems, a metric that depends on the available human and capital resources.

## Development Efficiency Comparison

Traditional development requires 3-6 months, costs $50K-$200K, and needs 5-10 developers. 

Allegory WebCraft delivers the same result in 15-30 minutes, costs $3K-$15K, and requires zero developers. 

This is a 95%+ reduction in development costs while delivering enterprise-grade architecture from day one.

## AI Agent Integration Architecture

Our platform includes over 60 specialized agents organized across multiple categories. 

Customer service agents handle intelligent chatbot interactions, lead qualification, and multi-language support. 

Business operations agents manage quotes, users, and billing automation. 

Industry specialists include insurance underwriters, actuaries, and claims processors. 

Technical operations agents provide code analysis, system integration, and performance optimization. Strategic consultation agents offer technology advisory, due diligence, and business analysis services.

**Real-Time Processing Capabilities:**

Streaming AI responses use WebSocket-based real-time communication for instant interactions. 

Multi-language processing provides simultaneous translation and cultural adaptation. 

The enterprise command bus grants access to over 1,000 specialized backend operations. 

Cross-agent coordination, aka *Agentic Cross-Pollination*, enables seamless handoffs between specialized agents, ensuring customers always interact with the most appropriate expertise for their needs.

### Live Technical Demonstrations

See AllegoryOS in action across three production platforms. 

**The Allegory Platform** at [allegory.app](https://allegory.app) showcases our complete business platform built with React 19 and AI architecture.

### What Makes AllegoryOS Different

Unlike single-model systems, our hybrid AI architecture combines Large Language Models for sophisticated reasoning with Specialized Language Models for precise execution. 

Infrastructure-as-Code enables complete business applications to be deployed in minutes rather than months. Every component is built for AI integration from the ground up, not retrofitted afterward. 

Compliance and security are architectural foundations, not afterthoughts. 

The multi-tenant design delivers enterprise scalability without enterprise complexity, while the event-driven core ensures real-time responsiveness across all business operations.

### Key Technical Metrics via *Allegory Codebase Manager*

Our production codebase spans 574,521 lines across 3,731 files, maintaining a 76% quality score based on lines of code, comment ratio, code smells, cyclomatic complexity, and latest vulnerability count. 

We have generated 4,380 Markov simulations for synthetic training data, analyzed over 1.5 million insurance policies for pattern recognition, and processed over 1 million insurance claims for automation training. 

Full localization covers 13 language and region combinations across 28 product modules and business application layers.

### Competitive Technical Advantages

AllegoryOS delivers development speed 100 times faster than traditional approaches, completing in minutes what typically takes months. 

Cost efficiency improves by 90% compared to custom agency development. 

The platform provides enterprise-grade performance with consumer-grade simplicity, scaling seamlessly from startup to enterprise traffic levels without requiring architecture changes. 

Built-in regulatory compliance covers all supported industries, while multi-region deployment ensures local data sovereignty for global reach.

---

## Allegory Digital Workforce

Our platform includes over 60 specialized AI agents organized to handle complete business operations across five key categories.

**Customer Acquisition & Service** agents include WebCraft AI for instant website creation and business deployment, a General Purpose Assistant for universal problem-solving and consultation, Save on Insurance for quote comparison and policy optimization, and Migration AI for business process automation and system integration.

**Insurance Operations** agents handle the full policy lifecycle. The Quote-and-Bind Agent provides instant policy issuance and binding. Specialized underwriters assess vehicle insurance risk and evaluate real estate properties. The Actuary agent optimizes risk modeling and pricing, while the Claims Processor automates claims handling and settlement.

**Business Intelligence & Analytics** capabilities include Plato, our comprehensive insurance knowledge agent covering P&C, Health, Life, and Pension products. The Data Scientist agent provides advanced analytics and predictive modeling. The Feedback Classifier analyzes customer sentiment and categorizes responses, while the Performance Monitor tracks real-time business metrics and identifies optimization opportunities.

**Technical Operations** agents maintain and improve the platform. The Codebase Manager handles software development and code optimization. The Technology Officer provides strategic technology consultation and architecture guidance. The System Integrator manages third-party application connectivity and data synchronization, while the Security Specialist monitors compliance and assesses threats.

**Communication & Support** agents ensure seamless customer interactions. The Translator provides multi-language customer support across 13 languages. The Meeting Scribe documents customer interactions and manages follow-up. The Email Specialist automates communication and campaign management, while the Document Processor handles file validation and organization.

---

## Allegory Distribution Channels

**Allegory Digital Wallet** works like Apple Wallet, but for insurance. Upload your existing policy, get an instant quote, and bind immediately.

**CoverCrush by Allegory** grades your current insurance, compares it against thousands of real policies, and helps you buy cheaper coverage through AI-powered price comparison.

**Allegory ChatBot** offers zero-friction conversational insurance. Answer questions, get a quote, and bind immediately without leaving the conversation.

**Allegory WebCraft** transforms business requirements into complete websites that go live in 15-30 minutes, providing AI-powered website creation with enterprise capabilities.

---

## Founder

**Onur Güngör** — Founder & Technical CEO, Actuary

Onur brings 15 years of actuarial experience to Allegory, having been a founding team member at Onlia Insurance previously. He is the architect and builder of AllegoryOS and its hybrid AI architecture.

[LinkedIn](https://linkedin.com/in/onur-gungor) | [Articles](https://allegory.app/news)

---

## Why This Repo Exists

Until now, Allegory has been built entirely behind closed doors—over 6,000 commits of full-stack, AI-native insurance infrastructure with none of it public.

As we navigate through this ecosystem, we more believe in the power of open ecosystems. This repository represents the first step in sharing the internal systems we've built, making parts of it reusable for other builders in regulated and AI-driven verticals, and starting a real conversation about what should be open-source in insurance.

---

## What We Might Open-Source

We're not here to dump code for the sake of it. We want to open things that help others ship better, faster, and more securely.

| Candidate | Description |
|----------|-------------|
| allegory-auth | JWT-based auth system with SOC 2-ready policies |
| allegory-terraform | Fully modular Terraform stack for multi-tenant SaaS |
| allegory-agent-ui | Lightweight React UI kit for agent workflows |
| allegory-llm-core | LLM-native orchestration framework for vertical AI products |
| allegory-ci-cd | GitHub Actions templates for secure deployment to AWS |
| allegory-insurance-agents | Specialized AI agents for insurance operations |
| allegory-react19-generator | Automated React 19 project generation with enterprise features |
| allegory-websocket-api | Real-time communication framework for AI applications |

---

## We Want Your Input

This repository is open so we can learn from you. 

What parts of Allegory's infrastructure or codebase would be most useful to open? 

Have you built or struggled with similar problems? 

Would you use these components if they were modular and documented?

Create an [Issue](https://github.com/toolsallegory/allegory-public/issues) here.

---

## Our Philosophy

We don't believe in "move fast and break things."

We believe in **shipping quality digital products that people can rely on at their toughest times.**

This public repository is us living that belief.

---

## Links

- **Website**: [allegory.app](https://allegory.app)
- **Digital Wallet**: [Allegory Insurance](https://allegoryinsurance.com)
- **CoverCrush**: [covercrush.ai](https://covercrush.ai)
- **Contact**: support@allegory.app
- **Book a Call**: [Calendly](https://calendly.com/onur-allegory)

Please note that Digital Wallet and CoverCrush are our regulated products and only available to certain regions as we expand our network with new fundings and partnerships.

---

## Join Us

If any of this resonates, star this repository, join the discussion, test things as we publish them, and reach out at onur@allegory.app.

Thanks for being part of something new.

— Onur Güngör  
Founder & Technical CEO, Allegory

---

© 2025 Allegory Technology Inc. All rights reserved.

**Confidential**: This repository contains information about Allegory Technology Inc. By accessing this repository, you acknowledge that the information contained herein is confidential and agree to maintain its confidentiality.