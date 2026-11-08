# Awesome-AI-Driven-Test-Case-Generation

# Awesome-AI-Driven-Test-Case-Generation
**Top AI Driven Test Case Generation (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Requirement-to-Test Generation, Agentic Test Authoring, Self-Healing Scripts & Self-Hosted RAG Testing Agents*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI-Driven Test Case Generation**. These tools enable QA teams to turn requirements, user stories, and production journeys into structured test cases—automatically identifying edge cases, generating executable scripts, and reducing manual authoring time from hours to minutes.

**Examples** include BrowserStack Test Case Generator, Qodo (formerly CodiumAI), Katalon Run with AI, testRigor, aqua cloud AI Copilot, Qase AI, Testmo AI, Functionize Architect, Testim Copilot, and Tricentis Tosca AI (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted test generation, RAG-based test authoring, and open agent frameworks. **Critical note**: True open-source AI test case generation is sparse—**TestTeller** is the most complete open-source RAG agent for generating E2E, integration, and technical tests from documentation and code . **Healwright** and **playwright-self-healing-framework** address the adjacent problem of keeping generated tests stable. No open-source project matches BrowserStack's 90% faster test creation with 91% accuracy, but for teams wanting model transparency and data ownership, the building blocks exist.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **BrowserStack Test Case Generator**
  **AI agent that converts requirements into test cases**. **Features**: Analyzes PRDs and user stories to generate context-aware test cases; identifies edge cases and validates business logic; claims **90% faster test creation**, **91% accuracy**, and **92% coverage**; Currys reports **4X test coverage increase** using BrowserStack AI . **Pricing**: Bundled with BrowserStack AI; **Automate $99/month** includes AI agents . **Free tier**: No free tier for AI agents; trial available. **Best for**: teams already on BrowserStack wanting AI test generation integrated with their testing platform—**trade-off**: requires BrowserStack subscription; AI agents tied to Automate plan.

- **Qodo (formerly CodiumAI)**
  **AI test generation and code quality platform**. **Features**: **Qodo Gen** generates unit test suggestions at function level, identifies boundary values and exception cases; **Qodo Merge** analyzes PRs for bugs and quality issues; rebranded from CodiumAI with expanded capabilities . **Pricing**: **Free tier** available; paid plans for teams; enterprise pricing varies . **Free tier**: Yes. **Best for**: developers wanting unit test generation inside their IDE—**trade-off**: focused on unit tests, not end-to-end; enterprise setup complexity noted by reviewers.

- **Katalon Run with AI**
  **Agentic test generation and execution** within Katalon platform. **Features**: **Run with AI** (beta)—write a test in plain language, an autonomous agent executes it against your live app, then returns a ready-to-run Katalon Studio script; handles private/internal apps via secure tunnel; responsive viewport testing with `set_viewport`; **True Production Insights** generates test cases from real user journeys . **Pricing**: **Studio Enterprise $229/seat/month**; AI features included in platform tiers . **Free tier**: Katalon Studio free; platform paid. **Best for**: teams wanting requirement-to-script automation in one session—**trade-off**: Run with AI is beta; full flow including auto-save to cloud repository still coming.

- **testRigor**
  **Generative AI test automation** with plain English authoring. **Features**: Build and maintain automated tests using free-flowing plain English; cloud-based with third-party integrations . **Pricing**: **Paid plans only**; pricing available upon request; no free tier . **Free tier**: No permanent free tier. **Best for**: teams wanting plain English test authoring without coding—**trade-off**: no public pricing; desktop testing only in paid versions.

- **aqua cloud AI Copilot**
  **Test case generation from requirements**. **Features**: Create single or multiple test cases from a linked requirement or context; set max test steps (3–12 or any); choose positive or negative path for single cases; AI generates both positive and negative paths for multiple cases; generated cases link as dependent items covering the requirement . **Pricing**: Quote-only. **Free tier**: Not specified. **Best for**: teams wanting structured requirement-to-test-case generation—**trade-off**: requires aqua cloud platform.

- **Qase AI**
  **AI features within Qase test management**. **Features**: **Generates manual test cases from requirements or linked Jira/GitHub issues**; analyzes automation readiness; converts manual tests to automated scripts; exports to Playwright, Cypress, Selenium; runs in Qase cloud; **credit-based**—all AI actions consume credits from monthly pool, no rollover . **Pricing**: AI enabled by default on paid plans; credits reset monthly . **Free tier**: No free AI on free tier; paid plans only. **Best for**: teams on Qase wanting AI test generation within their test management workflow—**trade-off**: credits are consumable and expire; data not used for model training.

- **Testmo AI**
  **AI test case generation from requirements** (beta). **Features**: Generate structured, reviewable test cases directly from requirements inside Testmo; **available to all users across all plans**; human-in-the-loop—AI suggests, you review and refine; canonical output formats (Text, Steps, BDD); automatic traceability—cases tagged as AI-generated and linked to requirements; control generation of **10–60 test cases per request**; admin can disable AI features . **Pricing**: Included in all Testmo plans; no separate AI add-on . **Free tier**: Testmo free tier available with AI. **Best for**: teams wanting AI generation without a separate purchase—**trade-off**: beta; generation is probabilistic by nature.

- **Functionize Architect**
  **Chrome extension for rapid test creation**. **Features**: Models every action as you click through your app; creates self-healing tests; dynamic test editing; randomized data generation; custom extensions for pre/post conditions; API calls, database verification, email/text validation . **Pricing**: **14-day free trial**; quote-only after . **Free tier**: Trial only. **Best for**: teams wanting click-through test capture with self-healing—**trade-off**: requires Chrome extension; trial-limited.

- **Testim Copilot (Tricentis)**
  **Generative AI within Testim editor**. **Features**: **Generate**—custom test steps from text description; **Explain**—clarifies JavaScript code; **Fix**—analyzes and suggests corrections; no external tools needed . **Pricing**: Add-on to Testim; quote-only. **Free tier**: Trial available. **Best for**: teams on Testim wanting AI assistance in test authoring—**trade-off**: generative AI is an add-on; complex features still require coding.

- **Tricentis Tosca AI**
  **Agentic test automation** for enterprise. **Features**: **Agentic Test Automation**—autonomously generates tests from natural language requests; early users cut test creation from **40 minutes to 5**; **AI Chat** converts Jira requirements to manual test cases; **MCP Services** connects your own AI models; **AI Workspace** for governance; on-premises deployment coming . **Pricing**: Quote-only; AI credits tracked via AI Chat . **Free tier**: None. **Best for**: enterprises wanting governed agentic test generation—**trade-off**: enterprise complexity; credit consumption.

## Open-Source GitHub Projects

- **TestTeller**
  **RAG-based test generation agent** (PyPI package) — **the most complete open-source AI test case generator** found in this research . **Features**: **Generates multiple test types**—End-to-End (E2E) user journeys, Integration tests (API contracts), Technical tests (performance, security, resilience), and Mocked System tests; **comprehensive scenario coverage**—happy paths, negative/edge cases, failure/recovery, security/performance; **ingests multi-format documentation** (PDF, Word, Excel, Markdown, text, source code); **analyzes code from GitHub repos** (public and private) or local folders; **RAG pipeline** using Google Gemini 2.0 Flash and text-embedding-004; **outputs Markdown documentation and structured test cases** . **Tech stack**: Python 3.11+, ChromaDB, Google Gemini API . **Deploy**: `pip install testteller`; `testteller generate`; Docker Compose available . **Trade-off**: **Gemini-dependent**—requires Google API key; ChromaDB for vector storage; newer project with limited community validation. **Best for**: developers wanting an open-source RAG agent that generates comprehensive test cases from documentation and code—especially those already using Google Gemini.

- **Healwright**
  **Self-healing Playwright selector repair engine** (open source, PyPI) — **the most focused open-source tool for keeping AI-generated tests stable** . **Features**: **Automatic broken locator detection** during test runs; **token-efficient DOM snapshots**; **similarity heuristic repairs**—ID, class, attribute, and text similarity scores; **FastMCP server** for IDE agent integration; **live verification** in headless Chromium before applying patches; CLI for test runs and patch management . **Tech stack**: Python, Playwright . **Deploy**: `uv run healwright test` . **Trade-off**: **Heuristic-based, not LLM**—uses similarity scoring; requires Playwright test suite. **Best for**: teams generating tests with AI that then break on UI changes—Healwright repairs selectors deterministically without LLM costs.

- **playwright-self-healing-framework**
  **Deterministic self-healing for Playwright** (open source, TypeScript) — **the most transparent open-source self-healing implementation** . **Features**: **Semantic fingerprint**—captures tag, id, classes, attributes, visible text, label, parent/sibling context; **six weighted sub-scores**; **threshold-based acceptance** (default 0.6); **full JSON audit trail** for every healing decision; **offline and deterministic**—no API keys, no LLM calls . **Tech stack**: TypeScript, Playwright, Vitest . **Deploy**: npm/TypeScript project . **Trade-off**: **Playwright-specific**; threshold tuning required. **Best for**: teams wanting explainable self-healing for generated tests—especially those uncomfortable with LLM unpredictability.

### Additional Strong Open-Source Options

- **CANVAS (canvas-heal)** — Semantic intent-based self-healing for UI tests (MIT, PyPI). Confidence-gated resolver (auto-heal above 0.92, needs confirmation 0.75–0.92), pytest plugin, Playwright and Selenium support, audit log exportable as JUnit XML; evaluated on real migrations—6/7 intents auto-healed in ShopEasy checkout redesign . **Note**: **Self-healing layer, not test generation**—it keeps generated tests stable. **Best for**: teams wanting research-validated self-healing with confidence gates.
- **Yewo** — AI-powered E2E testing agent for mobile (open source, alpha, PyPI). Natural language journeys, Appium-driven, secret masking, security rule auditing, coverage declarations . **Note**: **Alpha software**—not production-hardened; Appium dependency. **Best for**: teams wanting AI-driven mobile test generation with security rule auditing.

**Frameworks for building custom systems**: Combine **TestTeller** for RAG-based test generation with **Healwright** or **playwright-self-healing-framework** for selector stability—creating a layered open-source AI test generation stack. **None of these match BrowserStack's 90% faster creation with 91% accuracy or Katalon's agentic requirement-to-script loop**, but for teams wanting model transparency and data ownership, the options are functional.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI test generation platforms handling application requirements and test data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.
- **The "requirement-to-test agent" vs. "unit test generator" vs. "self-healing repair" vs. "RAG generation" distinction is critical.** **BrowserStack, Katalon Run with AI, aqua cloud, Qase, Testmo, Functionize, and Tosca** are **requirement-to-test agents**—they convert requirements or click-throughs into structured test cases . **Qodo** is a **unit test generator**—it focuses on function-level tests inside the IDE . **Healwright, playwright-self-healing-framework, and CANVAS** are **self-healing repair**—they keep existing tests stable, not generate new ones . **TestTeller** is **RAG generation**—it builds tests from documentation and code using retrieval . **Choose based on whether you need requirement-driven generation, unit tests, test stability, or RAG-based authoring.**
- **BrowserStack's Test Case Generator claims 90% faster creation, 91% accuracy, and 92% coverage**—with Currys reporting 4X test coverage increase . **The trade-off**: requires BrowserStack Automate ($99/month) or higher; AI agents are bundled, not standalone .
- **Testmo AI is available on all plans**—including free tier—with no separate AI add-on . **The trade-off**: beta; generation is probabilistic; 10–60 cases per request . **For teams wanting AI generation without a purchase decision, Testmo is the most accessible commercial option.**
- **Katalon Run with AI is in beta**—the agent executes plain-language tests against live apps and returns a script in one session, but auto-save to cloud repository is still coming . **The trade-off**: beta status; Katalon Studio Enterprise at $229/seat/month for full platform .
- **Qase AI uses a credit pool**—all AI actions consume credits that expire monthly with no rollover . **Model your generation volume before committing**; data is not used for model training .
- **Tricentis Tosca's Agentic Test Automation cut test creation from 40 minutes to 5** for early users—but it is enterprise-grade with AI credits and complex deployment . **The trade-off**: on-premises AI coming; governance via AI Workspace .
- **TestTeller is the only functional open-source AI test generator**—it ingests docs and code, generates E2E/integration/technical/mocked tests, and outputs structured Markdown . **The trade-off**: Gemini API dependency; newer project with limited validation. **For teams wanting open-source RAG generation, it is the starting point.**
- Self-hosted open-source solutions require proper infrastructure (Python for TestTeller, Google Gemini API key, ChromaDB), security hardening, and ongoing maintenance. **Test generation tools process application requirements and source code**—ensure your deployment meets your organization's security and IP protection requirements before processing production assets.

---

**Made for QA engineers, test automation leads, and organizations building transparent AI test generation solutions.**
Let's make AI-Driven Test Case Generation more open, data-driven, and requirement-aware.
