# Awesome Autonomous AI QA Testing Agents

A curated collection of autonomous AI agents, platforms, and frameworks transforming software Quality Assurance (QA), automated testing, synthetic data generation, and self-healing test automation.

---

## Sector Overview & Market Dynamics

The dedicated AI-powered software testing and QA sector is valued at approximately **$9.3B to $12.5B (2025–2026)**, expanding at a CAGR exceeding 25–30% toward an estimated $39B+ by the early 2030s. The sector is **moderately to highly fragmented** rather than winner-take-all: traditional test automation giants (Tricentis, SmartBear, Perforce) and cloud device testing grids (BrowserStack, Sauce Labs) compete alongside specialized codeless platforms (Katalon, mabl, Functionize, Virtuoso) and emerging AI-native, outcome-oriented managed QA agents (QA Wolf), while open-source test runners (Playwright, Cypress, Selenium) remain the ubiquitous execution backbone.

---

## Autonomous AI QA SaaS Platforms

The table below covers leading commercial SaaS platforms offering autonomous and AI-orchestrated QA testing capabilities. Entries are sorted descending by company size (valuation / estimated scale).

| Platform | Company Size (Valuation / Scale) | Starting Tier Pricing | Free Tier / Trial Limits | Key Capabilities & Focus |
|:---|:---|:---|:---|:---|
| **[Tricentis Testim](https://www.testim.io/)** | **~$4.5B** valuation (Parent Tricentis; ~$500M ARR; acquired Testim for ~$150M–$200M) | **$450/month** (Starter tier for up to 3 parallel slots, custom enterprise quote-based thereafter) | **7-day free trial**; no permanent free tier; includes full access to AI-powered locators and authoring evaluation | AI-powered low-code test automation, self-healing smart locators, Salesforce/web apps, enterprise CI/CD integration |
| **[BrowserStack](https://www.browserstack.com/)** | **~$4.0B** valuation ($225M–$230M+ ARR, bootstrapped & Series B) | **$39/month** (App Live / Live starting tier billed annually; Automate starts at $99/parallel slot/mo) | **Free trial**: 30 min interactive manual testing + 100 min automated testing on real devices; **Free forever tier**: Percy visual testing (5,000 screenshots/mo) | Cloud device & browser grid, Test Companion AI agents, automated failure analysis, Percy visual AI testing |
| **[mabl](https://www.mabl.com/)** | **~$360M** valuation (Series C; ~$18M ARR) | **~$450/month** ($5,400/year base entry tier for 500 monthly cloud credits; quote-based scaling) | **14-day free trial**; no permanent free tier; unlimited free local test authoring and runs; cloud execution metered | GenAI-powered low-code E2E testing, auto-healing assertions, performance regressions, accessibility testing |
| **[Applitools](https://www.applitools.com/)** | **~$250M–$300M** valuation (Acquired by Thoma Bravo; ~$25M–$30M ARR) | **$667/month** ($8,004/year Starter tier for 1,000 page checkpoints or 100K component checkpoints/mo) | **14-day free trial**; no permanent free tier; unlimited users and test execution during evaluation | Visual AI engine, Applitools Autonomous NLP-based test generation, Ultrafast Grid, cross-device visual diffing |
| **[QA Wolf](https://www.qawolf.com/)** | **~$170M** valuation (Series B; ~$15M–$20M ARR) | **Pay-As-You-Go** starting at **1¢/AI credit** + **15¢/runner minute** (Self-serve platform) or managed service contracts | **Free trial**: Initial package of free test runs included upon signup; no permanent free tier; custom monthly spend caps supported | Autonomous multi-agent E2E test generation, 80% automated coverage guarantee, 100% parallel runs, zero test flakiness triage |
| **[Functionize](https://www.functionize.com/)** | **~$100M+** estimated valuation ($67M total funding; ~$17M–$19M ARR) | **$20/month** (Growth plan; 3,200,000 execution credits/mo); Scale plan at $100/mo (20M credits/mo) | **Free forever plan**: $0/mo with **800,000 credits/month** (+ 2,000,000 one-time onboarding bonus); all core agents included | Autonomous Architect agents, natural language test creation, self-healing SmartFix, big data visual & performance analysis |
| **[Katalon Studio AI](https://www.katalon.com/)** | **~$80M–$150M** estimated valuation ($30M funding; ~$36M–$62M ARR) | **$84/seat/month** ($1,000/seat/year for first 3 seats Studio Professional; Platform True bundles from $59/seat/mo) | **Free forever tier**: Katalon Studio Free (unlimited local authoring & execution; no CI/CD or headless runtime); **30-day free trial** for Pro | Enterprise test authoring, AI-assisted test generation, StudioAssist failure analysis, cross-platform web/mobile/API/desktop |
| **[Virtuoso QA](https://www.virtuoso.qa/)** | **~$45M–$60M** estimated valuation (£18M / $23M total equity & debt) | **$4,500/month** (~$54,000/year starting enterprise capacity tier via custom/partner contracts) | **14-day trial / pilot** available on request following demo; no permanent free tier; enterprise journey volume limits apply | Natural Language Programming (NLP) autonomous test authoring, Touchstone agentic validation, self-healing live DOM |

---

## Open-Source AI QA Agents & Testing Frameworks

Open-source agents and developer libraries for automated test synthesis, adversarial LLM evaluation, and self-healing pipelines:

| Project | License | Capabilities & Focus | Current Status |
|:---|:---|:---|:---|
| **[Ghost (ghosttest)](https://github.com/ghosttest/ghost)** | MIT | Autonomous Python test generation and self-healing: monitors files, creates pytest test suites, feeds execution traces back to LLMs, and auto-patches code until green. Multi-provider (Groq, OpenAI, Anthropic, Ollama). | Active (v0.2+) |
| **[Agentic QA](https://pypi.org/project/agentic-qa/)** | Open Source | Multi-agent red-team validation for RAG and LLM applications: synthesizes adversarial scenarios, assesses outputs, and computes semantic safety scores using 5 LangGraph agents. | Active |
| **[TestTeller](https://pypi.org/project/testteller/)** | Open Source | RAG-driven test generation agent creating E2E, integration, and technical tests from documentation and source repositories. Integrates Gemini, OpenAI, Claude, and Ollama. | Active |
| **[Voylla](https://pypi.org/project/voylla/)** | Open Source | AI test case generator supporting Python, Java, and JavaScript with automated CI/CD triggers and multi-model LLM routing. | Active (v0.2+) |
| **[Agentic QE Fleet](https://github.com/agentic-qe/fleet)** | Open Source | 11 agent + 9 skills quality engineering plugin for Claude Code and coding agents (`aqe init`), orchestrating specialized testing personas across platforms. | Active |
| **[lionagi-qe-fleet](https://pypi.org/project/lionagi-qe-fleet/)** | Open Source | 15 specialized QA agents (test generator, flaky test hunter, security scanner, regression sentinel) with multi-model routing and stateful test memory. | Active (v1.1+) |

---

## Notable Adjacent Tools (Reframed)

- **[Qodo (formerly CodiumAI)](https://www.qodo.ai/)** — Shifted focus in 2026 to AI-assisted code review, PR quality gating, and integrity checks; legacy standalone unit test generation commands have been deprecated.
- **[Augment Code](https://www.augmentcode.com/)** — AI-powered software developer workspace and context-aware coding platform (acquired by Harness in October 2026), rather than a standalone QA agent.

---

## Contributing

Contributions, updates, and corrections are welcome! Please submit a PR or issue following the existing tabular structure.
