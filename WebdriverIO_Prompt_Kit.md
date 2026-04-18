AI-POWERED LEARNING PROMPT KIT

**WEBDRIVER IO**

**JavaScript Edition**

*From Manual Tester to WebdriverIO SDET --- Let AI Teach You*

✅ Learn concepts from scratch

✅ Write code independently and with AI

✅ Build a full WDIO framework

✅ Prepare for SDET interviews

✅ AI concepts in testing

**00 HOW TO USE THIS KIT**

Each prompt in this kit is designed to make an AI tool --- ChatGPT or Claude --- act as your personal trainer. The prompts are structured so the AI gives you a clear plan, teaches step by step, and adapts to your pace.

- Copy the prompt exactly as written

- Paste it into ChatGPT (GPT-4o) or Claude (Claude Sonnet or higher)

- Read the output carefully --- ask follow-up questions freely

- Work through the sections in order for best results

- You do not need any other resource --- these prompts are your complete curriculum

|                                                                                                                    |
|--------------------------------------------------------------------------------------------------------------------|
| *Pro tip: Use Claude for longer explanations and framework design. Use ChatGPT for code generation and debugging.* |

|                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------------|
| *Important: Always tell the AI your current skill level. The prompts already include this --- do not remove that line.* |

**01 YOUR LEARNING ROADMAP**

Start here. This prompt generates your personalised learning roadmap before you write a single line of code. Save the output --- it becomes your study plan.

**ROADMAP PROMPT --- Run this first**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are an expert SDET trainer with 15 years of experience.</p>
<p>I am a manual QA engineer transitioning into automation. My background:</p>
<p>- [X] years of manual testing experience</p>
<p>- Familiar with: [JIRA / test cases / regression testing / etc.]</p>
<p>- Programming knowledge: [none / basic / intermediate]</p>
<p>- Goal: become job-ready using WebdriverIO with JavaScript</p>
<p>- Available study time per day: [30 mins / 1 hour / 2 hours]</p>
<p>Create a structured 8-10-week learning roadmap covering:</p>
<p>1. JavaScript fundamentals for testers (only what I need)</p>
<p>2. WebdriverIO with JavaScript core concepts and architecture</p>
<p>3. Writing my first tests</p>
<p>4. Framework design and best practices</p>
<p>5. CI/CD integration</p>
<p>6. Interview preparation</p>
<p>7. AI concepts in testing for 2025/2026</p>
<p>For each week provide:</p>
<p>- Topic focus</p>
<p>- What I will be able to do by end of week</p>
<p>- 2-3 practice tasks</p>
<p>- Free resources to use</p>
<p>Format as a clean table then a detailed week-by-week breakdown.</p>
<p>Adjust timeline based on my daily study time.</p>
<p>Be specific — this is my actual study plan, not a generic template.</p></td>
</tr>
</tbody>
</table>

|                                                                                                 |
|-------------------------------------------------------------------------------------------------|
| *Once the AI generates your roadmap, save it. Screenshot it. This is your complete study plan.* |

**02 LEARN CONCEPTS FROM SCRATCH**

WebdriverIO is built for enterprise JavaScript teams. It uses WebDriver protocol with a modern async API.

|                                           |
|-------------------------------------------|
| **PHASE 2A --- WebdriverIO Architecture** |

**Prompt 2A-1: How WebdriverIO Works**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are an expert WebdriverIO trainer teaching a manual QA engineer.</p>
<p>Explain how WebdriverIO works to a manual tester.</p>
<p>Cover:</p>
<p>1. What WebdriverIO is and how it differs from Selenium and Playwright</p>
<p>2. WebDriver protocol vs Chrome DevTools Protocol in WDIO</p>
<p>3. WDIO test runner — what it manages automatically</p>
<p>4. Sync vs async WDIO — which version to use in 2025</p>
<p>5. Browser object and element interactions</p>
<p>6. wdio.conf.js — the central configuration file</p>
<p>After each concept: one interview Q&amp;A.</p>
<p>Format: Concept → Explanation → Interview Q&amp;A</p></td>
</tr>
</tbody>
</table>

**Prompt 2A-2: Setup and First WebdriverIO Test**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a WebdriverIO expert.</p>
<p>Walk me through setting up WebdriverIO from scratch.</p>
<p>Step 1: npm init wdio — the interactive setup wizard</p>
<p>Step 2: Key choices in the wizard (Mocha vs Jasmine, Chrome, spec reporter)</p>
<p>Step 3: First login test with complete code and explanation</p>
<p>Step 4: Run with npx wdio wdio.conf.js from terminal</p>
<p>Step 5: Read the test output</p>
<p>Show complete test. Give me 3 variations to try myself.</p></td>
</tr>
</tbody>
</table>

|                                     |
|-------------------------------------|
| **PHASE 2B --- WDIO Core Concepts** |

**Prompt 2B-1: Selectors, Commands, and Waits**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a WebdriverIO trainer.</p>
<p>Teach me selectors, commands, and waits in WebdriverIO.</p>
<p>SELECTORS: $() and $$(), CSS, XPath, ARIA, text-based.</p>
<p>KEY COMMANDS: browser.url(), $().click(), $().setValue(), $().getText(),</p>
<p>browser.waitUntil(), $().waitForDisplayed(), $().waitForClickable().</p>
<p>WAITS: implicit vs explicit in WDIO, waitUntil custom conditions.</p>
<p>Show real examples. Top 3 WDIO wait mistakes?</p></td>
</tr>
</tbody>
</table>

**Prompt 2B-2: Page Object Model in WebdriverIO**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a WebdriverIO POM expert.</p>
<p>Build a complete POM for login + dashboard in WebdriverIO.</p>
<p>Step 1: Page class structure in WDIO</p>
<p>Step 2: LoginPage with selectors as getters</p>
<p>Step 3: DashboardPage</p>
<p>Step 4: Mocha test using both pages</p>
<p>Step 5: WDIO POM vs Playwright POM — key differences</p>
<p>Show all code. Give practice exercise.</p></td>
</tr>
</tbody>
</table>

**03 WRITE CODE --- INDEPENDENTLY AND WITH AI**

**Prompt 3A-1: AI-Assisted WebdriverIO Test Writing**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior WebdriverIO SDET acting as my coding partner.</p>
<p>I describe a scenario in plain English. Write the complete WDIO test,</p>
<p>explain every line, point out edge cases, suggest improvements.</p>
<p>My scenario: [DESCRIBE HERE]. Use https://www.saucedemo.com if unspecified.</p>
<p>After writing ask: negative tests? POM? API testing with WDIO?</p></td>
</tr>
</tbody>
</table>

**04 BUILD A FULL WEBDRIVERIO FRAMEWORK**

**Prompt 4-1: Framework Architecture**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Principal SDET expert in WebdriverIO.</p>
<p>Guide me through building a production-ready WDIO framework.</p>
<p>Cover: folder structure (exact tree), wdio.conf.js for multiple environments,</p>
<p>Page Object pattern, shared fixtures, Allure reporter,</p>
<p>parallel execution in WDIO, GitHub Actions CI/CD.</p>
<p>Show complete structure. Top 3 WDIO framework mistakes?</p></td>
</tr>
</tbody>
</table>

**Prompt 4-2: CI/CD Integration**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a DevOps and WebdriverIO expert.</p>
<p>Build a GitHub Actions workflow for my WDIO project.</p>
<p>Include Node.js setup, npm ci, run WDIO headless,</p>
<p>upload Allure report as artifact, show pass/fail summary.</p>
<p>Show complete .github/workflows/wdio.yml with comments.</p>
<p>Top 3 CI failure reasons for WebdriverIO?</p></td>
</tr>
</tbody>
</table>

**05 INTERVIEW PREPARATION**

These prompts prepare you for WebdriverIO interview questions from junior to senior level.

**Prompt 5-1: Mock Interview --- Junior Level**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior SDET interviewer at a product company.</p>
<p>Conduct a mock WebdriverIO interview with me at junior SDET level.</p>
<p>Rules:</p>
<p>- Ask one question at a time</p>
<p>- Wait for my answer before giving feedback</p>
<p>- After my answer: tell me what was good, what was missing, give the ideal answer</p>
<p>- Ask 10 questions total</p>
<p>Include: 3 conceptual, 3 practical scenario, 2 comparison, 2 code-reading questions.</p>
<p>Start now. Ask your first question.</p></td>
</tr>
</tbody>
</table>

**Prompt 5-2: Mock Interview --- Senior SDET Level**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Principal Engineer interviewing for a Senior SDET role.</p>
<p>Conduct a senior-level WebdriverIO mock interview.</p>
<p>Focus on: framework architecture decisions, performance and scalability,</p>
<p>CI/CD pipeline design, flaky test management, test strategy, mentoring.</p>
<p>Rules: one question at a time, wait for answer, give structured feedback.</p>
<p>8 questions total. Begin.</p></td>
</tr>
</tbody>
</table>

**Prompt 5-3: Salary Negotiation for Automation Roles in India**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a career coach specialising in QA and SDET roles in India.</p>
<p>I am transitioning to automation using WebdriverIO and preparing for interviews.</p>
<p>My profile:</p>
<p>- [X] years manual testing experience</p>
<p>- Transitioning to automation</p>
<p>- Target role: [SDET / Automation Engineer / Senior QA]</p>
<p>- Target city: [Chennai / Bangalore / Hyderabad / Remote]</p>
<p>Provide:</p>
<p>1. Current market salary range for my profile in India (2025/2026 data)</p>
<p>2. Exact words to say when asked for expected CTC</p>
<p>3. How to handle an offer below my expectation</p>
<p>4. What NOT to say in salary discussions</p>
<p>5. How to negotiate when moving from manual to automation roles</p></td>
</tr>
</tbody>
</table>

**06 AI CONCEPTS AND AI-ASSISTED TESTING**

AI concepts are increasingly asked in 2025 and 2026 SDET interviews. These prompts prepare you to answer them and use AI to work faster.

**Prompt 6-1: AI in Testing --- Interview Answer Framework**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are an expert on AI in software testing.</p>
<p>Teach me how to answer AI-related questions in a WebdriverIO SDET interview.</p>
<p>Cover these with ideal interview answers:</p>
<p>1. How is AI changing test automation in 2025/2026?</p>
<p>2. How do you use AI tools like ChatGPT or Claude in daily testing work?</p>
<p>3. What is visual AI testing and which tools support it?</p>
<p>4. How would you test an AI-powered feature as an SDET?</p>
<p>5. What is self-healing test automation and how does it work?</p>
<p>For each: concept → interview answer → specific tool to name → the one line that impresses.</p>
<p>Format: Question → Concept → Answer → Key Line</p></td>
</tr>
</tbody>
</table>

**Prompt 6-2: Generate Tests from Requirements Using AI**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior SDET who uses AI daily in WebdriverIO workflows.</p>
<p>Teach me to generate tests from user stories using AI.</p>
<p>Walk through your complete workflow:</p>
<p>Step 1: Turn a user story into testable requirements</p>
<p>Step 2: Exact prompt to generate test cases from the story</p>
<p>Step 3: Exact prompt to turn test cases into automation code</p>
<p>Step 4: How to review and validate AI-generated code</p>
<p>Step 5: What AI gets wrong most often and how to catch it</p>
<p>Live example using this user story:</p>
<p>'As a user, I want to reset my password so I can regain</p>
<p>access to my account if I forget my credentials.'</p>
<p>Show: user story → test cases → automation code.</p>
<p>Then ask me to try with a story of my own.</p></td>
</tr>
</tbody>
</table>

**Prompt 6-3: Build Your AI-Assisted Daily Testing Workflow**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior SDET who integrates AI into daily work.</p>
<p>Build a practical AI-assisted workflow for my daily testing tasks.</p>
<p>Cover:</p>
<p>1. Using ChatGPT/Claude for test case generation</p>
<p>- The exact prompt structure that works</p>
<p>- What to provide and what AI cannot figure out alone</p>
<p>2. Using AI for professional bug report writing from rough notes</p>
<p>3. Using AI for test data generation</p>
<p>4. Using AI for automation code review — finding anti-patterns</p>
<p>5. The daily AI habits of a productive SDET in 2025</p>
<p>End with: the one AI skill every QA engineer should master first.</p></td>
</tr>
</tbody>
</table>

**YOU HAVE EVERYTHING YOU NEED.**

*These prompts are your complete WebdriverIO curriculum. Run them in order. Take your time.*
