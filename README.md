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

| Platform | Description | Pricing | Free Tier / Limits |
| --- | --- | --- | --- |
| **BrowserStack Test Case Generator** | AI agent that converts requirements into test cases; analyzes PRDs/user stories, edge case identification, script generation. | Bundled with BrowserStack AI; Automate starts at $99/mo | No free tier for AI agents (trial available) |
| **Qodo (formerly CodiumAI)** | AI test generation and code quality platform; unit test suggestions (Qodo Gen) and PR bug analysis (Qodo Merge). | Developer free; Teams from $19/user/mo; Enterprise custom | Free tier available (individual developers) |
| **Katalon Run with AI** | Agentic requirement-to-script execution against live applications; auto-generates runnable Katalon Studio scripts. | Studio Enterprise $229/seat/mo; platform tiers | Free version of Katalon Studio (limited features; AI on paid) |
| **testRigor** | Generative AI automated testing using free-flowing plain English authoring. | Custom quote-only | No permanent free tier (trial available) |
| **aqua cloud AI Copilot** | Requirement-to-test case generation with positive/negative test paths and dependency linking. | Quote-only | Not specified (trial available upon request) |
| **Qase AI** | Generates manual test cases from requirements, converts manual to automated (Playwright, Cypress, Selenium). | Included in paid plans (credit-based monthly pool) | No free AI on free tier (paid plans only) |
| **Testmo AI** | Human-in-the-loop requirement test case generation (Text, Steps, BDD) with requirement traceability. | Included across all plans; no add-on fee | Free tier available with AI included (10–60 cases/request) |
| **Functionize Architect** | Smart test recorder & creator with self-healing, dynamic editing, and randomized data generation. | Quote-only | 14-day free trial |
| **Testim Copilot (Tricentis)** | Generative AI within Testim editor to generate custom steps, explain code, and repair tests. | Add-on to Testim; quote-only | Free trial available |
| **Tricentis Tosca AI** | Enterprise agentic test automation generating tests from natural language and Jira requirements. | Enterprise quote-only (credit consumption) | None |

### Platform Deep-Dives

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

- **[Shortest](https://github.com/antiwork/shortest)** [![GitHub stars](https://img.shields.io/github/stars/antiwork/shortest?style=social&color=white)](https://github.com/antiwork/shortest/stargazers)

  **QA via natural language AI tests**. **Features**: End-to-end AI test execution framework running natural language instructions directly via Playwright; self-improves and learns from execution traces; integrates with GitHub Actions for automated regression pipelines. **Tech stack**: TypeScript, Playwright, Anthropic Claude. **License**: MIT. **Best for**: QA engineers wanting natural language driven E2E test execution.

- **[Qodo-Cover](https://github.com/qodo-ai/qodo-cover)** [![GitHub stars](https://img.shields.io/github/stars/qodo-ai/qodo-cover?style=social&color=white)](https://github.com/qodo-ai/qodo-cover/stargazers)

  **AI-powered automated test generation and coverage enhancement tool**. **Features**: Analyzes existing repository codebases, detects missing code coverage branches, and automatically generates valid unit test suites to increase test coverage; integrates directly into CI/CD pipelines. **Tech stack**: Python, LLM orchestration. **License**: AGPL-3.0. **Best for**: automated unit test suite generation and code coverage improvement in CI/CD.

- **[Pynguin](https://github.com/se2p/pynguin)** [![GitHub stars](https://img.shields.io/github/stars/se2p/pynguin?style=social&color=white)](https://github.com/se2p/pynguin/stargazers)

  **The PYthoN General UnIt Test geNerator**. **Features**: Automated unit test generation framework for Python programs; applies search-based software testing and mutation testing algorithms to generate comprehensive pytest suites with high branch coverage. **Tech stack**: Python, AST analysis. **License**: LGPL-3.0 / MIT. **Best for**: automated Python unit test generation without manual scripting.

- **[Munk AI](https://github.com/chaxiu/munk-ai)** [![GitHub stars](https://img.shields.io/github/stars/chaxiu/munk-ai?style=social&color=white)](https://github.com/chaxiu/munk-ai/stargazers)

  **Self-improving AI testing engine across Android, iOS, and Web**. **Features**: Autonomous testing agent executing multi-platform test journeys; automatically detects UI changes, plans test paths, and refines execution strategies over time. **Tech stack**: Python, Computer Vision, Appium/Playwright. **License**: Apache-2.0. **Best for**: cross-platform mobile and web automated exploration and test scenario generation.

- **[Scenario](https://github.com/langwatch/scenario)** [![GitHub stars](https://img.shields.io/github/stars/langwatch/scenario?style=social&color=white)](https://github.com/langwatch/scenario/stargazers)

  **Agentic testing framework for agentic codebases**. **Features**: End-to-end conversational and multi-turn scenario simulation for AI agents; validates agent decisions, tool calls, and output safety against multi-step user scenarios. **Tech stack**: TypeScript / Python, LLM evaluators. **License**: Apache-2.0. **Best for**: testing and validating LLM agents and multi-agent workflows.

- **[Randoop](https://github.com/randoop/randoop)** [![GitHub stars](https://img.shields.io/github/stars/randoop/randoop?style=social&color=white)](https://github.com/randoop/randoop/stargazers)

  **Automatic unit test generation for Java**. **Features**: Feedback-directed random test generation for Java classes; automatically creates regression tests and error-revealing unit tests (JUnit) to capture bugs and contract violations. **Tech stack**: Java. **License**: Apache-2.0. **Best for**: enterprise Java unit test generation and regression suite creation.

- **[TestPilot](https://github.com/githubnext/testpilot)** [![GitHub stars](https://img.shields.io/github/stars/githubnext/testpilot?style=social&color=white)](https://github.com/githubnext/testpilot/stargazers)

  **Test generation using Large Language Models** by GitHub Next. **Features**: Explores adaptive LLM prompt orchestration to generate automated JavaScript and TypeScript unit test suites with assertion synthesis; researches AI-driven test completeness. **Tech stack**: TypeScript, OpenAI API. **License**: MIT. **Best for**: AI-driven JavaScript/TypeScript unit test generation research.

- **[Chromogen](https://github.com/open-source-labs/Chromogen)** [![GitHub stars](https://img.shields.io/github/stars/open-source-labs/Chromogen?style=social&color=white)](https://github.com/open-source-labs/Chromogen/stargazers)

  **UI-driven Jest test-generation tool for React state management**. **Features**: Automatically records state modifications (Recoil selectors and Zustand store hooks) during manual user interactions and outputs Jest unit and integration tests. **Tech stack**: JavaScript/TypeScript, Jest, React. **License**: MIT. **Best for**: front-end developers generating tests from React UI interaction.

- **[Agentic-Playwright](https://github.com/idavidov13/agentic-playwright)** [![GitHub stars](https://img.shields.io/github/stars/idavidov13/agentic-playwright?style=social&color=white)](https://github.com/idavidov13/agentic-playwright/stargazers)

  **Production-grade Playwright + TypeScript scaffold for agentic testing**. **Features**: Ready-to-use testing harness designed specifically for autonomous AI coding agents to author, run, and self-validate Playwright test suites. **Tech stack**: TypeScript, Playwright. **License**: MIT. **Best for**: developers orchestrating AI agents to generate and execute Playwright end-to-end tests.

- **[UTBotJava](https://github.com/UnitTestBot/UTBotJava)** [![GitHub stars](https://img.shields.io/github/stars/UnitTestBot/UTBotJava?style=social&color=white)](https://github.com/UnitTestBot/UTBotJava/stargazers)

  **Automated unit test generation and precise code analysis for Java**. **Features**: Combines symbolic execution with machine learning to generate high-coverage JUnit test cases and pinpoint subtle edge-case bugs and security vulnerabilities. **Tech stack**: Java, Kotlin, Z3 solver. **License**: Apache-2.0. **Best for**: in-depth Java unit test generation and formal verification.

- **[TestGPT](https://github.com/fayez-nazzal/TestGPT)** [![GitHub stars](https://img.shields.io/github/stars/fayez-nazzal/TestGPT?style=social&color=white)](https://github.com/fayez-nazzal/TestGPT/stargazers)

  **AI companion that writes unit tests on your behalf**. **Features**: Automated CLI tool analyzing source code files and generating comprehensive unit tests with mocks and edge case coverage. **Tech stack**: Python, OpenAI API. **License**: MIT. **Best for**: rapid unit test scaffolding using LLMs.

- **[write-the](https://github.com/Wytamma/write-the)** [![GitHub stars](https://img.shields.io/github/stars/Wytamma/write-the?style=social&color=white)](https://github.com/Wytamma/write-the/stargazers)

  **AI-powered documentation and test generation tool**. **Features**: CLI tool that analyzes source code to synthesize documentation, docstrings, and executable unit tests using LLMs. **Tech stack**: Python, LLMs. **License**: MIT. **Best for**: simultaneous test generation and documentation synthesis.

- **[TestTeller](https://github.com/iAviPro/testteller-agent)** [![GitHub stars](https://img.shields.io/github/stars/iAviPro/testteller-agent?style=social&color=white)](https://github.com/iAviPro/testteller-agent/stargazers)

  **RAG-based test generation agent** (PyPI package: `testteller`). **Features**: **Generates multiple test types**—End-to-End (E2E) user journeys, Integration tests (API contracts), Technical tests (performance, security, resilience), and Mocked System tests; comprehensive scenario coverage (happy paths, edge cases, failure/recovery); ingests multi-format documentation (PDF, Word, Excel, Markdown, code); RAG pipeline powered by Google Gemini and ChromaDB; outputs structured Markdown and test scripts. **Tech stack**: Python 3.11+, ChromaDB, Google Gemini API. **License**: Open Source / PyPI. **Best for**: teams wanting an open-source RAG agent generating test cases directly from specification documents and code.

- **[Healwright](https://github.com/amrsa1/healwright)** [![GitHub stars](https://img.shields.io/github/stars/amrsa1/healwright?style=social&color=white)](https://github.com/amrsa1/healwright/stargazers)

  **Self-healing Playwright selector repair engine**. **Features**: Automatic broken locator detection during test runs; token-efficient DOM snapshots; similarity heuristic and AI-assisted repairs; FastMCP server for IDE agent integration; live verification in headless Chromium before saving patches. **Tech stack**: Python, Playwright, FastMCP. **License**: MIT / PyPI. **Best for**: keeping AI-generated Playwright tests stable across UI refactors.

- **[Yewo](https://github.com/yewohq/yewo)** [![GitHub stars](https://img.shields.io/github/stars/yewohq/yewo?style=social&color=white)](https://github.com/yewohq/yewo/stargazers)

  **AI-driven mobile E2E testing agent**. **Features**: Natural language test journey generation for iOS and Android; Appium-driven execution; sensitive data masking and security rule auditing. **Tech stack**: Python, Appium. **License**: Open Source / PyPI. **Best for**: AI-driven mobile test case generation and execution.

- **[playwright-self-healing-framework](https://github.com/darkokos21/self-healing-framework-playwright)** [![GitHub stars](https://img.shields.io/github/stars/darkokos21/self-healing-framework-playwright?style=social&color=white)](https://github.com/darkokos21/self-healing-framework-playwright/stargazers)

  **ML-powered self-healing test automation framework for Playwright**. **Features**: Captures semantic element fingerprints (tag, id, classes, attributes, visible text); evaluates candidates using ML ranking algorithms; threshold-based acceptance; generates confidence-based reports. **Tech stack**: TypeScript, Playwright, FastAPI, Python, scikit-learn. **License**: MIT. **Best for**: transparent, ML-ranked self-healing for Playwright test automation.

- **[CANVAS (canvas-heal)](https://github.com/mandavillivijay/CANVAS)** [![GitHub stars](https://img.shields.io/github/stars/mandavillivijay/CANVAS?style=social&color=white)](https://github.com/mandavillivijay/CANVAS/stargazers)

  **Semantic intent-based self-healing for UI tests** (PyPI: `canvas-heal`). **Features**: Confidence-gated resolver (auto-heal above 0.92, human confirmation 0.75–0.92); pytest plugin; supports Playwright and Selenium; audit logs exportable as JUnit XML. **Tech stack**: Python, pytest, Playwright/Selenium. **License**: MIT. **Best for**: research-validated, confidence-gated self-healing for web test suites.

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
