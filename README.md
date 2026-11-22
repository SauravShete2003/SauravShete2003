<!--
  HOW TO USE
  1. On GitHub, create a PUBLIC repository named exactly like your username (example: johndoe/johndoe).
  2. Tick "Add a README file", then replace its content with this file.
  3. Replace every [PLACEHOLDER] (name, links, username) and delete anything that is not true for you.
-->

<h1 align="center">Hi, I'm [Your Name] 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2F81F7&center=true&vCenter=true&width=700&lines=QA+Engineer+(Fresher);Manual+%2B+Automation+Testing;I+break+software+so+users+don't+have+to" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/[your-linkedin]"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:[your-email]"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open%20to-QA%20Internships-2EA44F?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Location-Pune%20%7C%20Remote-orange?style=for-the-badge"/>
</p>

---

## 🧪 About Me

I'm a fresher QA tester who enjoys finding the bug **before** the user does. I work on both sides of testing:

- **Manual testing:** test case design, functional and regression testing, bug reporting
- **Automation testing:** building maintainable frameworks with **Selenium + Java + TestNG** and **Playwright + TypeScript**
- Comfortable with **Docker**, **Maven**, and **Git/GitHub**
- Currently practising Java interview questions daily and looking for my first QA role

> 🎯 **Open to:** QA internships (manual + automation) in **Pune (on-site)** or **remote**

---

## 🛠️ QA Toolbox

| Area | Tools |
|---|---|
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white) |
| **UI Automation** | ![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) |
| **Test Frameworks** | ![TestNG](https://img.shields.io/badge/TestNG-FF6C37) ![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white) |
| **Reporting & Logs** | ![Extent Reports](https://img.shields.io/badge/Extent_Reports-0A7BBB) ![Log4j2](https://img.shields.io/badge/Log4j2-D22128?logo=apache&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) |
| **IDEs** | ![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?logo=eclipseide&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white) |

---

## 🚀 Featured Projects

### 1️⃣ OpenCart E-Commerce Automation Framework
**Selenium · Java · TestNG · Maven · Docker Selenium Grid**

A hybrid test automation framework for the [TutorialsNinja demo store](https://tutorialsninja.com/demo/index.php).

- ✅ **Page Object Model** design for reusable, maintainable page classes
- ✅ **Cross-browser** and **parallel-ready** execution on a **Docker Selenium Grid** (hub + nodes)
- ✅ **Data-driven testing** with external test data
- ✅ **Extent Reports** with screenshots on failure, plus **Log4j2** logging
- ✅ Separate **TestNG suites** for Master, Grouping (Sanity/Regression) and Grid runs
- ✅ Flows covered: registration, login, add to cart

🔗 [View repository]([link-to-your-repo])

### 2️⃣ OrangeHRM Test Automation (Manual + Automation)
**Playwright · TypeScript**

End-to-end testing of the [OrangeHRM demo](https://opensource-demo.orangehrmlive.com/) with written manual test cases and matching automation.

- ✅ Modules covered: **Login, PIM, Leave, Admin**
- ✅ Structured with `pages/`, `tests/` and `utils/` folders
- ✅ Manual test cases mapped to automated scripts

🔗 [View repository]([link-to-your-repo])

---

## 🏗️ Framework Structure (Selenium + Java)

```text
automation-framework
├── src/test/java
│   ├── pageObjects     # Page classes: locators + actions
│   ├── testCases       # TestNG test classes
│   └── utilities       # Extent reports, data providers, helpers
├── src/test/resources  # config.properties, log4j2.xml
├── testData            # External test data
├── reports             # Extent HTML reports
├── screenshots         # Failure screenshots
├── logs                # Log4j logs
├── master.xml          # Full regression suite
├── grouping.xml        # Sanity / Regression groups
├── grid-docker.xml     # Suite for the Docker Grid
├── docker-compose.yaml # Selenium Grid (hub + nodes)
└── pom.xml
```

**Run it:**
```bash
docker-compose up -d     # start Selenium Grid
mvn clean test           # run the suite
```

---

## 🐞 How I Report a Bug

```text
Title:        [Cart] Item count in header does not update after adding product
Environment:  Windows 11 | Chrome | Build/URL
Severity:     Medium     Priority: High
Steps:        1. Open home page  2. Click "Add to Cart" on MacBook  3. Check header cart
Expected:     Header shows "1 item(s)"
Actual:       Header still shows "0 item(s)"
Evidence:     Screenshot / video / console logs attached
```

---

## 🎯 What I'm Working On

- 🔧 Growing my Selenium and Playwright frameworks with more modules and cleaner reports
- ☕ Daily Java practice for QA interviews
- 🚀 Next on my roadmap: **CI/CD with GitHub Actions**

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=[your-github-username]&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=[your-github-username]&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 📫 Let's Connect

I'm actively looking for a **QA internship or entry-level QA role**. If you have an opening, or you just want to talk testing, reach out:

📧 [your-email] &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/[your-linkedin])

<p align="center"><i>"Quality is not an act, it is a habit."</i> ✨</p>
