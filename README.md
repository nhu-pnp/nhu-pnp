<h1 align="center">Hi, I'm Mia Pham 👋</h1>
<h3 align="center">QA Engineer · Test Automation with Playwright & BDD</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=nhu-pnp&style=flat&color=2ea44f" alt="Profile views">
</p>

---

### 🧪 About me

- **2+ years** as a QA Engineer on web applications — manual testing and test automation
- Build **BDD automation frameworks** with **Playwright + TypeScript + Gherkin** (`playwright-bdd`)
- Turn test cases from **Squash TM** into readable, traceable `.feature` scenarios (1 step in the TC = 1 Gherkin step)
- Run tests in **CI/CD with GitHub Actions**: smoke on every PR, full regression nightly, with HTML reports & traces
- Care about clean test code: **Page Object Model**, API-based test data setup, tagging, type checks and code style in CI
- 🌱 Currently learning: API testing with Playwright, visual testing, performance basics

### 🛠️ Tech stack

**Automation**
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Cucumber](https://img.shields.io/badge/BDD%20%2F%20Gherkin-23D96C?style=flat&logo=cucumber&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

**API & Tools**
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

**Test management**
![Squash TM](https://img.shields.io/badge/Squash%20TM-5C2D91?style=flat)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Testing skills:** test design (EP, BVA, decision table, state transition) · functional / regression / smoke testing · API testing · bug reporting & tracking · Agile/Scrum

### 📌 Featured project

#### [ae-bdd](https://github.com/nhu-pnp/ae-bdd) — BDD regression suite for [Automation Exercise](https://automationexercise.com)

![Playwright](https://img.shields.io/badge/Playwright-1.63-2EAD33?logo=playwright&logoColor=white)
![playwright-bdd](https://img.shields.io/badge/playwright--bdd-9.2-23D96C)
[![CI](https://github.com/nhu-pnp/ae-bdd/actions/workflows/main.yml/badge.svg)](https://github.com/nhu-pnp/ae-bdd/actions/workflows/main.yml)

```gherkin
@TC-SQUASH-154 @regression @smoke
Scenario: Verify user login successfully with valid credentials
  Given a registered account exists
  And user is on the signup and login page
  When user enters the registered email and correct password in the login form
  And user clicks the Login button
  Then the home page is displayed
  And the header shows the user's name
```

| What                 | How                                                                     |
| -------------------- | ----------------------------------------------------------------------- |
| Readable test specs  | Gherkin `.feature` files, each tagged with its Squash TM test case ID   |
| Maintainable code    | Page Object Model + reusable components, TypeScript strict type check   |
| Stable test data     | Accounts created & cleaned up via API instead of through the UI          |
| Flexible runs        | Tags `@smoke` / `@regression` / `@TC-SQUASH-xxx`, parallel workers      |
| CI/CD                | GitHub Actions: smoke on PR, nightly regression, manual run by tag      |
| Debugging            | HTML report, trace, screenshot & video on failure uploaded as artifacts |

Covered features: **Register** (signup, validation, password masking, defaults) · **Login** (valid / invalid credentials) · **Home page**

### 📊 GitHub stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=nhu-pnp&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nhu-pnp&layout=compact&hide_border=true" alt="Top languages">
</p>

---

<p align="center"><i>"Quality is never an accident; it is always the result of intelligent effort."</i></p>
