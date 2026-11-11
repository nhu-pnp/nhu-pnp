<h1 align="center">Hi, I'm Phạm Nguyễn Phương Như (Nhu) 👋</h1>
<h3 align="center">QA Engineer · AI & Playwright · ISTQB® CTFL</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/nhu-pnp/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:phuongnhu0801@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.credly.com/badges/308e2c9d-272f-4a54-a424-77070dbead93/public_url"><img src="https://img.shields.io/badge/ISTQB%C2%AE-CTFL%20Certified-005A9C?style=flat" alt="ISTQB CTFL"></a>
  <img src="https://komarev.com/ghpvc/?username=nhu-pnp&style=flat&color=2ea44f" alt="Profile views">
</p>

---

### 🧪 About me

- **2+ years** testing **Web and Mobile (Android, iOS)** apps in Enterprise SaaS, AI-integrated software, Healthcare and Education
- **AI-assisted testing with Claude**: requirements analysis, scenarios & edge cases, test cases/data, log & bug analysis and Playwright scripts — **cutting test preparation time by over 50%**
- **Test automation** with **Playwright (TypeScript) + BDD Cucumber/Gherkin** and Page Object Model
- **API testing** with Postman, **SQL** data verification, role-based permission and multi-tenant isolation testing
- Regression planning in **Agile/Scrum** and **V-Model** projects · **ISTQB® Certified Tester Foundation Level** (07/2025)

### 💼 Experience

**Manual Tester · Cleeksy** — _09/2025 – Present_ · Enterprise SaaS, AI-integrated software · Web & Mobile
- Test plans and E2E test design for B2B workflows; testing AI outputs for accuracy, consistency, response time and edge cases
- REST API testing with Postman, SQL checks, MISA / M-invoice integration testing, role-based & multi-tenant verification
- **AI-assisted Test Automation (~4 months):** converted manual cases and user stories into Gherkin scenarios and Playwright scripts, used Claude for step definitions, locators, refactoring and debugging with traces, ran automated regression and reported in Jira

**Manual Tester · EFE Technology** — _04/2024 – 08/2025_ · Social, Healthcare & Education · Web & Mobile
- Web & Mobile test cases/checklists incl. Android/iOS compatibility on real devices
- Regression plans and coverage before delivery; bug tracking in Jira; consistently met Agile sprint deadlines

### 🛠️ Tech stack

**Automation & AI**
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Cucumber](https://img.shields.io/badge/BDD%20%2F%20Gherkin-23D96C?style=flat&logo=cucumber&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Java](https://img.shields.io/badge/Java%20(basic)-ED8B00?style=flat&logo=openjdk&logoColor=white)

**API, Data & Performance**
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![MySQL](https://img.shields.io/badge/SQL%20%2F%20MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat&logo=apachejmeter&logoColor=white)
![Chrome DevTools](https://img.shields.io/badge/Chrome%20DevTools-4285F4?style=flat&logo=googlechrome&logoColor=white)

**Tools & Platforms**
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)

**Testing skills:** requirement/design analysis · test planning · test design (EP, BVA, decision table) · E2E, functional, regression, UI/UX, cross-platform, API & basic performance testing · role-based access & multi-tenant data isolation · STLC, Agile/Scrum, V-Model

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
| Stable test data     | Accounts created & cleaned up via API instead of through the UI         |
| Flexible runs        | Tags `@smoke` / `@regression` / `@TC-SQUASH-xxx`, parallel workers      |
| CI/CD                | GitHub Actions: smoke on PR, nightly regression, manual run by tag      |
| Debugging            | HTML report, trace, screenshot & video on failure uploaded as artifacts |

Covered features: **Register** (signup, validation, password masking, defaults) · **Login** (valid / invalid credentials) · **Home page**

### 🎓 Education & certification

- **ISTQB® Certified Tester Foundation Level** — 07/2025 · [verify on Credly](https://www.credly.com/badges/308e2c9d-272f-4a54-a424-77070dbead93/public_url)
- **Playwright Việt Nam** — Automation Testing with Playwright (TypeScript, locators/assertions, POM, API testing, reports)
- **IVietTech** — Manual Tester (API testing, SQL, performance, Web & Mobile testing)
- **Udemy** — JavaScript Programming
- **FPT University** — Hospitality (2018–2022), GPA 3.4/4.0
- 🌐 English **B2**: technical reading, written/spoken international teamwork

### 📊 GitHub stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=nhu-pnp&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nhu-pnp&layout=compact&hide_border=true" alt="Top languages">
</p>
