# Awesome-Autonomous-AI-QA-Testing-Agents

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **most entries in your list have no vendor-published pricing**, and the open-source side is a set of early-stage libraries, not autonomous QA platforms.



## The data problems



**Applitools Autonomous pricing is not vendor-published.** The Merito reseller page describes the **Test Units** model—shared between Eyes and Autonomous, with unlimited users and executions—but explicitly says "Request Applitools pricing" . A separate competitive analysis lists **Applitools Autonomous at $969/mo** , but that is a third-party figure, not Applitools' own rate card. **Do not present it as vendor-confirmed.**



**mabl is quote-only.** Its Japanese pricing page describes credit-based cloud runs (500 credits/month minimum), unlimited local runs, and a 14-day trial, but **no dollar figures** . A competitive analysis confirms "Contact sales" .



**Testim (Tricentis) is enterprise-only.** Vendr lists "Testim Copilot" as a product but provides no price . A pricing comparison lists **Testim at $450/month** as a third-party estimate .



**Virtuoso QA is entirely custom-priced.** Both Professional and Enterprise tiers are "Contact Us!"; the page confirms **no free plan** .



**Functionize has published a consumption-based model**—billed on production test cases created over 12 months, not runs—but **no dollar figures** . A separate page lists Individual from **$20/mo** and Team from **$40/mo** , but this conflicts with the consumption model described in the blog. Treat as indicative.



**QA Wolf has the most transparent pricing in the category.** **$1 per web run, $2 per mobile/desktop run**, with unlimited AI usage, 100% parallelization, no user limits, and 3 free retries per run . A separate estimate places contracts at **$60K–$250K+/year** for managed service .



**BrowserStack AI Agents** are bundled into Test Companion plans; the pricing page shows tiers ($39, $150, $249) but does not isolate AI agent pricing .



**CodiumAI is now Qodo, and it no longer generates tests.** Qodo's own docs confirm **legacy v1 commands including test generation were removed in 2026 without direct replacements** . It is now an AI code review platform starting at **$30/month** . **Do not list CodiumAI/Qodo as a test generation agent.**



**Augment AI is a coding platform, not a QA agent.** It starts at **$20/month Standard** and **$100/month Business** (flat for up to 50 seats), with token-based LLM billing plus a **40% service fee** . It was **acquired by Harness on October 8, 2026** .



**Katalon Studio AI** is part of Katalon's Professional plan at **$1,000/seat/year for the first 3 seats** (~$84/seat/month), including AI agents for test automation, failure analysis, and self-healing .



## Open-source: what actually exists



| Project | License | What it actually does | Status |

|---|---|---|---|

| **Ghost (ghosttest)** | MIT | Autonomous Python test generation + self-healing: watches files, generates pytest suites, feeds failures back to LLM, patches tests until green. Multi-provider (Groq, OpenAI, Anthropic, Ollama)  | v0.2.0 |

| **Agentic QA** | Open source (PyPI) | Multi-agent red-team testing for RAG/LLM systems: generates adversarial test cases, executes, judges, refines. 5 LangGraph agents  | Active |

| **TestTeller** | Open source (PyPI) | RAG agent generating E2E/integration/technical tests from docs and code. Supports Gemini, OpenAI, Claude, Ollama  | Active |

| **Voylla** | Open source (PyPI) | AI test case generator for Python/Java/JavaScript. Multi-provider, CI integration  | v0.2.2 |

| **Agentic QE Fleet** | Open source (GitHub) | 11 agents + 9 skills plugin for Claude Code; 60 agents + 86 skills via `aqe init`; works with 11 coding platforms  | Active |

| **lionagi-qe-fleet** | Open source (PyPI) | 15 specialized QA agents (test-generator, security-scanner, flaky-test-hunter, etc.) with multi-model routing and persistence  | v1.1.2 |



**None of these are production-grade replacements for mabl or QA Wolf.** They are developer libraries and agent frameworks you integrate into your own pipeline. Ghost is the closest to "autonomous test generation + self-healing" , but it is Python-only and v0.2.0.



## What I recommend



**Split into three honest categories:**



**1. Autonomous QA Platforms** (proprietary, mostly quote-only):

- **QA Wolf** — $1–$2/run, no user limits, 3 free retries 

- **Katalon** — $1,000/seat/year (first 3 seats) 

- **Applitools** — Test Units model, request pricing 

- **mabl** — quote-only, 14-day trial 

- **Testim** — enterprise-only 

- **Virtuoso QA** — custom-only, no free plan 

- **Functionize** — consumption-based on test cases created 

- **BrowserStack** — bundled with Test Companion 



**2. Not QA Agents (remove or reframe):**

- **Qodo (CodiumAI)** — test generation removed in 2026; now code review 

- **Augment AI** — coding platform, acquired by Harness 



**3. Open-Source Agent Libraries:**

- **Ghost** (MIT) — Python test generation + self-healing 

- **Agentic QA** — RAG/LLM red-team testing 

- **TestTeller** — RAG-based test generation from docs 

- **Agentic QE Fleet** — 11-agent plugin for Claude Code 



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Applitools or mabl pricing, list Qodo as a test generator after its removal, or claim any open-source library replaces a managed QA platform.
