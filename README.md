# Hi there 👋 I'm Landysh Khusaenova

Aspiring AI Engineer | Transitioning from QA into LLM apps & GenAI workflows

---

## 👩‍💻 About Me
- 🤖 Aspiring AI Engineer transitioning into LLM applications and GenAI workflows
- 🎓 M.Sc. Engineering Physics · Software Engineering @ Masterschool (2025–2026)
- 🛠️ Building with Python · LangChain · OpenAI API · RAG · Autogen · HuggingFace
- 🧪 QA background in API testing and test automation
- 🌍 Multilingual: Russian · German (B2) · English
- 📍 Based in Germany, open to remote opportunities

---

## 🛠️ Tech Stack

### 🧪 Testing & Automation
Cypress, Postman, Swagger, DevTools, Jira, Zephyr

### 💻 Programming Languages
JavaScript, Python, SQL

### ⚙️ CI/CD & Tools
Jenkins, GitLab CI, Git

### 🔧 Backend Development
Flask, Jinja

### 🗄️ Databases
SQLite, PostgreSQL

### 🤖 AI / LLMs
OpenAI API, Gemini, Claude, Prompt Engineering, LLM Integration

---

## 🚀 Featured Projects

### 🎬 MoviWebApp — Flask Movie Manager
A full-stack web app built with Flask and SQLAlchemy for managing users and their favorite movies.

- **API Integration:** Fetches movie details (title, director, year, poster, IMDb rating) via OMDb API
- **Architecture:** Layered structure with separated models, data manager, and helpers
- **Validation:** Two-level data validation — model layer (SQLAlchemy) + controller layer (Flask)
- **Error Handling:** Custom 404/500 pages, flash messages, defensive programming
- **Tech:** Python 3, Flask, SQLAlchemy 2.0, SQLite, Jinja2, REST API
- 🔗 [View on GitHub](https://github.com/landuska/MoviWebApp)

---

### 📚 book_alchemy — Flask Library Manager
A full-stack web app for managing a personal library of books and authors,
built with clean architecture and strict data integrity.

- **API Integration:** Auto-fetches book covers from Google Books API via ISBN
- **Smart Cleanup:** Automatically removes authors with no remaining books
- **Architecture:** "Skinny Controller, Fat Model" — validation lives in the model layer
- **Validation:** Two-level defensive programming (SQLAlchemy `@validates` + Flask `try/except`)
- **Features:** Search by title, sort by author/year, 1–10 rating system
- **Tech:** Python 3, Flask, SQLAlchemy 2.0 (Mapped typing), SQLite, Google Books API
- 🔗 [View on GitHub](https://github.com/landuska/book_alchemy)

---

### 🧪 Herokuapp — REST API Testing Suite (Postman)
Comprehensive automated API test collection for a multi-role web application,
covering the full user lifecycle and task management workflows.

- **Auth Testing:** JWT Bearer token flow — registration, login, and token extraction for 3 roles (Admin, Teacher, Student)
- **Role-Based Coverage:** Tests scoped per role with dynamic variables (`{{token}}`, `{{myAdminToken}}`)
- **CRUD Coverage:** Full Create / Read / Update (PUT & PATCH) / Delete for Users and Tasks
- **Happy & Sad Paths:** Positive flows + negative cases (bad requests, invalid credentials)
- **Assertions:** Status codes, response time thresholds, header presence, and field-level value checks
- **Dynamic Data:** Environment variables store IDs and tokens across requests for chained test flows
- **Tech:** Postman, REST API, JWT, JSON
- 🔗 [View on GitHub](https://github.com/landuska/Herokuapp)

---

### 🎄 E2E Test Automation — Secret Santa App (Cypress)
Full end-to-end test suite for a real-world Secret Santa web application,
simulating a complete multi-user gift exchange workflow.

- **Multi-User Scenario:** Orchestrates 4 user roles in sequence — box creator + 3 participants
- **Full Flow Coverage:** Box creation → invite link generation → participant registration → wishlist submission → gift drawing
- **Custom Commands:** Reusable `cy.userLogin()` and `cy.creatingUsersCard()` for clean, DRY test code
- **Dynamic Data:** Faker.js generates random box names and wishes per test run
- **Page Object Pattern:** UI selectors managed via JSON fixture files per page
- **API Cleanup:** Automated `DELETE` request after tests to reset app state
- **Tech:** Cypress, JavaScript, Faker.js, REST API (JWT auth)
- 🔗 [View on GitHub](https://github.com/landuska/Cypress)

---

## 📈 Goals for 2026
- Land a role as an AI Engineer or LLM Application Developer
- Build and deploy a production-ready AI-powered application
- Deepen expertise in GenAI workflows, RAG systems, and LLM integration

---

## 📫 Contact
- GitHub: [@landuska](https://github.com/landuska)
- Open to QA / Automation / AI Engineering opportunities

---

⭐️ Thanks for visiting my profile!
