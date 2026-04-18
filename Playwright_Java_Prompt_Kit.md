**PLAYWRIGHT**

**Java Edition**

*From Selenium Java to Playwright Java --- Let AI Guide Your Transition*

✅ Understand key differences from Selenium

✅ Write code independently and with AI

✅ Build a full Maven framework

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
<p>- Goal: become job-ready using Playwright with Java</p>
<p>- Available study time per day: [30 mins / 1 hour / 2 hours]</p>
<p>Create a structured 8-10-week learning roadmap covering:</p>
<p>1. Java fundamentals for testers (only what I need)</p>
<p>2. Playwright with Java core concepts and architecture</p>
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

If you already know Selenium Java, Playwright Java will feel familiar --- but with important differences. These prompts focus on what changes.

|                                                   |
|---------------------------------------------------|
| **PHASE 2A --- Playwright Java vs Selenium Java** |

**Prompt 2A-1: Key Differences --- Selenium Java to Playwright Java**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior SDET expert in both Selenium Java and Playwright Java.</p>
<p>I know Selenium Java. Teach me Playwright Java by contrast.</p>
<p>For each concept show: Selenium Java way → Playwright Java way</p>
<p>1. Browser launch — no more ChromeDriver setup</p>
<p>2. Finding elements — Locator vs findElement + By</p>
<p>3. Waits — auto-waiting vs manual explicit waits</p>
<p>4. Assertions — Playwright Assertions vs TestNG/JUnit assertions</p>
<p>5. Screenshots and videos — built-in vs third-party</p>
<p>6. Page Object Model — what changes in Playwright Java</p>
<p>7. Maven dependency — what to add to pom.xml</p>
<p>For each: show Selenium Java code first, then Playwright Java equivalent.</p>
<p>Highlight what is better and what is different in Playwright.</p></td>
</tr>
</tbody>
</table>

|                                             |
|---------------------------------------------|
| **PHASE 2B --- Playwright Java Essentials** |

**Prompt 2B-1: Playwright Java Setup and First Test**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Playwright Java expert.</p>
<p>Walk me through setting up Playwright Java from scratch.</p>
<p>Step 1: Maven project setup — pom.xml with playwright dependency</p>
<p>Step 2: Install Playwright browsers — the Java way</p>
<p>Step 3: First test — Playwright vs Selenium syntax comparison</p>
<p>Step 4: Run with Maven from terminal</p>
<p>Step 5: HTML report with Playwright trace viewer</p>
<p>Show complete pom.xml and first test file.</p>
<p>Comment every line. What would this test look like in Selenium? Compare.</p></td>
</tr>
</tbody>
</table>

**Prompt 2B-2: Playwright Java Locators and Assertions**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Playwright Java trainer.</p>
<p>Teach me locators and assertions in Playwright Java.</p>
<p>LOCATORS:</p>
<p>- page.getByRole(), getByText(), getByLabel(), getByTestId()</p>
<p>- How these work in Java syntax</p>
<p>- Why these are better than CSS/XPath for maintenance</p>
<p>- When to still use CSS selectors</p>
<p>ASSERTIONS — Playwright Assertions:</p>
<p>- assertThat(locator).isVisible()</p>
<p>- assertThat(locator).hasText()</p>
<p>- assertThat(page).hasURL()</p>
<p>- assertThat(locator).isEnabled()</p>
<p>Show Java syntax for each. Compare to TestNG/JUnit assertions.</p>
<p>Why are Playwright assertions better for UI testing?</p></td>
</tr>
</tbody>
</table>

**Prompt 2B-3: playwright.config equivalent in Java**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Playwright Java expert.</p>
<p>In TypeScript we have playwright.config.ts.</p>
<p>In Java, configuration is done differently. Teach me how.</p>
<p>Cover:</p>
<p>1. Browser launch options in Java (headless, viewport, timeout)</p>
<p>2. BrowserContext options (baseURL, storageState)</p>
<p>3. How to manage configuration for multiple environments in Java</p>
<p>4. TestNG xml for cross-browser parallel execution with Playwright Java</p>
<p>5. How to generate Allure or ExtentReport with Playwright Java</p>
<p>Show complete Java configuration setup.</p>
<p>Compare complexity vs playwright.config.ts.</p></td>
</tr>
</tbody>
</table>

**03 WRITE CODE --- INDEPENDENTLY AND WITH AI**

**Prompt 3A-1: AI-Assisted Playwright Java Code Writing**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a senior Playwright Java SDET acting as my coding partner.</p>
<p>I will describe a scenario in plain English.</p>
<p>Write the complete Playwright Java test, explain every line,</p>
<p>point out edge cases, suggest improvements.</p>
<p>My scenario: [DESCRIBE YOUR SCENARIO HERE]</p>
<p>Use https://www.saucedemo.com if I do not specify a site.</p>
<p>After writing, ask:</p>
<p>- Do I want negative test cases?</p>
<p>- Do I want this converted to Page Object Model?</p>
<p>- Do I want TestNG data-driven variations?</p></td>
</tr>
</tbody>
</table>

**Prompt 3B-1: Debug My Failing Playwright Java Test**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are an expert Playwright Java debugger.</p>
<p>Failing code: [PASTE HERE]</p>
<p>Error: [PASTE HERE]</p>
<p>Identify cause, explain why, show fix, prevent in future.</p>
<p>Trace Viewer tip: how would I use Playwright Trace Viewer to debug this?</p></td>
</tr>
</tbody>
</table>

**04 BUILD A FULL PLAYWRIGHT JAVA FRAMEWORK**

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
<td><p>You are a Principal SDET expert in Playwright Java.</p>
<p>Guide me through building a production-ready Playwright Java Maven framework.</p>
<p>Cover:</p>
<p>1. Maven project folder structure — exact tree</p>
<p>2. pom.xml — Playwright + TestNG + Allure dependencies</p>
<p>3. Page Object Model in Playwright Java</p>
<p>4. ThreadLocal for parallel-safe Page instances</p>
<p>5. TestNG parallel configuration</p>
<p>6. Allure reporting integration</p>
<p>7. GitHub Actions CI/CD</p>
<p>Show complete structure. Explain every file.</p>
<p>Top 3 Playwright Java framework mistakes?</p></td>
</tr>
</tbody>
</table>

**Prompt 4-2: POM in Playwright Java**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Playwright Java POM expert.</p>
<p>Build a complete POM for login + dashboard in Playwright Java.</p>
<p>Step 1: BasePage class with common Playwright methods</p>
<p>Step 2: LoginPage with Playwright locators (no PageFactory)</p>
<p>Step 3: DashboardPage</p>
<p>Step 4: TestNG test using both pages</p>
<p>Step 5: Why no PageFactory is needed in Playwright Java — lazy locators</p>
<p>Show all code with comments.</p>
<p>Compare this POM to Selenium Java POM — what is simpler in Playwright?</p></td>
</tr>
</tbody>
</table>

**Prompt 4-3: Tracing and Debugging in Playwright Java**

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><em>COPY THIS PROMPT → Paste into ChatGPT or Claude</em></td>
</tr>
<tr class="even">
<td><p>You are a Playwright Java debugging expert.</p>
<p>Teach me all debugging and tracing capabilities in Playwright Java.</p>
<p>Cover:</p>
<p>1. Playwright Trace Viewer — how to enable and use</p>
<p>2. Screenshots on failure — how to configure in Java</p>
<p>3. Video recording — configuration and use case</p>
<p>4. Headed vs headless mode for debugging</p>
<p>5. Console log capture in Playwright Java</p>
<p>6. How to debug tests that fail in CI but pass locally</p>
<p>Show complete configuration for all debugging features.</p>
<p>The key line: what makes Playwright Trace Viewer irreplaceable?</p></td>
</tr>
</tbody>
</table>

**05 INTERVIEW PREPARATION**

These prompts prepare you for Playwright Java interview questions from junior to senior level.

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
<p>Conduct a mock Playwright Java interview with me at junior SDET level.</p>
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
<p>Conduct a senior-level Playwright Java mock interview.</p>
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
<p>I am transitioning to automation using Playwright Java and preparing for interviews.</p>
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
<p>Teach me how to answer AI-related questions in a Playwright Java SDET interview.</p>
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
<td><p>You are a senior SDET who uses AI daily in Playwright Java workflows.</p>
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

*These prompts are your complete Playwright Java curriculum. Run them in order.*
