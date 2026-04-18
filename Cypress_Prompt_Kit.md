AI-POWERED LEARNING PROMPT KIT

**CYPRESS**

**JavaScript Edition**

*From Manual Tester to Cypress SDET --- Let AI Teach You the Right Way*

✅ Learn concepts from scratch

✅ Write code independently and with AI

✅ Build a full Cypress framework

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
<p>- Goal: become job-ready using Cypress with JavaScript</p>
<p>- Available study time per day: [30 mins / 1 hour / 2 hours]</p>
<p>Create a structured 8-10-week learning roadmap covering:</p>
<p>1. JavaScript fundamentals for testers (only what I need)</p>
<p>2. Cypress with JavaScript core concepts and architecture</p>
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

Cypress runs inside the browser --- a completely different architecture from Selenium. These prompts explain it clearly.

|                                         |
|-----------------------------------------|
| **PHASE 2A --- JavaScript for Cypress** |

**Prompt 2A-1: JavaScript Basics for Cypress Testers**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a JavaScript instructor teaching a manual QA engineer.</p>
<p>Teach me only the JavaScript I need to write Cypress tests. Practical only.</p>
<p>Cover: variables (let/const), functions, promises vs callbacks,</p>
<p>objects, arrays, modules (require/import), error handling.</p>
<p>Rules: testing analogies, one example each.</p>
<p>Start with variables. Wait for 'next' before continuing.</p></td>
</tr>
</tbody>
</table>

|                                        |
|----------------------------------------|
| **PHASE 2B --- Cypress Core Concepts** |

**Prompt 2B-1: How Cypress Works --- Architecture Explained**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are an expert Cypress trainer.</p>
<p>Explain how Cypress works under the hood to a manual QA engineer.</p>
<p>Cover:</p>
<p>1. Why Cypress runs INSIDE the browser — key difference from Selenium/Playwright</p>
<p>2. What the Cypress Event Loop means for test writing</p>
<p>3. Automatic waiting in Cypress — how it works and default timeouts</p>
<p>4. cy.get() vs Playwright locators — key differences</p>
<p>5. Cypress command chaining — how it differs from regular JavaScript</p>
<p>6. What Cypress cannot do (same-origin limitation, multiple domains)</p>
<p>After each concept: one interview Q&amp;A.</p>
<p>Format: Concept → Explanation → Interview Q&amp;A</p></td>
</tr>
</tbody>
</table>

**Prompt 2B-2: Selectors and Commands in Cypress**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Cypress trainer.</p>
<p>Teach me selectors and key commands in Cypress.</p>
<p>Cover: cy.get() with CSS selectors, cy.contains(), cy.getByText(),</p>
<p>data-cy attributes (best practice), cy.find(), cy.within().</p>
<p>Key commands: cy.visit(), cy.type(), cy.click(), cy.select(),</p>
<p>cy.intercept(), cy.request(), cy.fixture().</p>
<p>For each: what it does, code example, when to use.</p>
<p>Why data-cy attributes are the recommended Cypress locator strategy.</p></td>
</tr>
</tbody>
</table>

**Prompt 2B-3: Network Interception with cy.intercept()**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Cypress network testing expert.</p>
<p>Teach me cy.intercept() — one of Cypress's most powerful features.</p>
<p>Cover:</p>
<p>1. What cy.intercept() does and how it differs from Playwright's page.route()</p>
<p>2. Intercepting and asserting on API calls made by the UI</p>
<p>3. Stubbing API responses to control what the UI renders</p>
<p>4. Testing how the UI handles API errors</p>
<p>5. cy.wait('@alias') — waiting for intercepted requests</p>
<p>Show complete code examples for each.</p>
<p>Real-world scenario: how to test a search feature that calls an API.</p></td>
</tr>
</tbody>
</table>

**03 WRITE CODE --- INDEPENDENTLY AND WITH AI**

**Prompt 3A-1: Your First Cypress Test**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Cypress JavaScript trainer.</p>
<p>Guide me through writing my first Cypress test from scratch.</p>
<p>Use https://the-internet.herokuapp.com/login.</p>
<p>Step 1: npm install cypress. Step 2: folder structure.</p>
<p>Step 3: Complete test file, every line explained.</p>
<p>Step 4: Run with npx cypress open and npx cypress run.</p>
<p>Give me 3 variations to try myself — no answers.</p></td>
</tr>
</tbody>
</table>

**Prompt 3B-1: AI-Assisted Cypress Test Writing**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior Cypress SDET acting as my coding partner.</p>
<p>I describe a scenario in plain English. You write the complete Cypress test,</p>
<p>explain every line, point out edge cases, suggest improvements.</p>
<p>My scenario: [DESCRIBE HERE]. Use https://www.saucedemo.com if unspecified.</p>
<p>After writing ask: negative tests? Page Object pattern? cy.intercept()?</p></td>
</tr>
</tbody>
</table>

**04 BUILD A FULL CYPRESS FRAMEWORK**

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
<td><p>You are a Principal SDET expert in Cypress.</p>
<p>Guide me through building a production-ready Cypress framework.</p>
<p>Cover: folder structure (exact tree), cypress.config.js for environments,</p>
<p>Page Object pattern in Cypress, custom commands, fixtures for test data,</p>
<p>cy.session() for authentication, GitHub Actions CI/CD, Cypress Dashboard.</p>
<p>Show complete structure. Top 3 Cypress framework mistakes?</p></td>
</tr>
</tbody>
</table>

**Prompt 4-2: Cypress vs Playwright --- Know Both for Interviews**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior SDET expert in both Cypress and Playwright.</p>
<p>Teach me how to compare Cypress and Playwright in interviews.</p>
<p>Cover key differences:</p>
<p>1. Language support — Playwright wins here (Python, Java, C#)</p>
<p>2. Architecture — in-browser vs WebSocket</p>
<p>3. Same-origin restriction in Cypress — what it means practically</p>
<p>4. Parallel execution — Playwright free, Cypress requires paid Cloud</p>
<p>5. Time-travel debugging in Cypress — genuine advantage</p>
<p>6. When would you choose Cypress over Playwright?</p>
<p>7. When would you choose Playwright over Cypress?</p>
<p>Give me the interview answer for: 'We use Cypress. Would you be comfortable</p>
<p>working with it? How does it compare to Playwright?'</p></td>
</tr>
</tbody>
</table>

**Prompt 4-3: CI/CD Integration**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a DevOps and Cypress expert.</p>
<p>Build a GitHub Actions workflow for my Cypress project.</p>
<p>Include: trigger on PR and push, Node.js setup, npm ci,</p>
<p>run Cypress headless, upload screenshots and videos on failure.</p>
<p>Show complete .github/workflows/cypress.yml with comments.</p>
<p>Top 3 CI failure reasons for Cypress tests?</p></td>
</tr>
</tbody>
</table>

**05 INTERVIEW PREPARATION**

These prompts prepare you for Cypress interview questions from junior to senior level.

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
<p>Conduct a mock Cypress interview with me at junior SDET level.</p>
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
<p>Conduct a senior-level Cypress mock interview.</p>
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
<p>I am transitioning to automation using Cypress and preparing for interviews.</p>
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
<p>Teach me how to answer AI-related questions in a Cypress SDET interview.</p>
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
<td><p>You are a senior SDET who uses AI daily in Cypress workflows.</p>
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

*These prompts are your complete Cypress curriculum. Run them in order*
