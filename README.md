# 🚀 API Booker – Postman Test Automation

![CI Status](https://github.com/Aidas415/api-booker/actions/workflows/postman-actions.yml/badge.svg)

This project automates REST API testing using a `Postman` collection and `Newman`, integrated into a CI/CD pipeline via GitHub Actions.

---

## 📖 Project Overview

- **Testing Tool:** [Postman](https://www.postman.com/) + [Newman](https://www.npmjs.com/package/newman)  
- **CI/CD Pipeline:** [GitHub Actions](https://docs.github.com/en/actions)  
- **Target API:** [Restful Booker](https://restful-booker.herokuapp.com) – a public API for practicing RESTful testing  
- **Purpose:** Educational project for learning automated API testing and CI/CD integration

## 🧩 Project Structure

> 📌 Icon meanings

- 📁 –  folder
- 📄 – file

```
├── 📄 postmanBooker (Postman collection)
├── 📄 booker-env.postman.json
├── 📄 package.json
├── 📁 .github
│   └── 📁 workflows
│       └── 📄 postman-ci.yml
└── 📄 README.md
```

## 🏁 Getting Started

1. Install Node.js  
2. Install Newman  
3. Run tests with:
```bash
npm run test
```
This command runs the postmanBooker collection using the booker-env.postman environment.

## 🔐 Environment Setup
- Uses `booker-env.postman.json` for environment variables
- No secrets required for public API

## ⚠️ Test Disclaimer
This API is intentionally buggy. Some test failures are expected and reflect real-world edge cases.

## ▶️ CI/CD with GitHub Actions
Tests run automatically on:
- Push to `main`
- Pull requests to `main`
Workflow file: [`postman-actions.yml`](https://github.com/Aidas415/api-booker/blob/main/.github/workflows/postman-actions.yml)

## 📜 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC).

## 👤 Author

Created by **Aidas Ambotas**  
📧 Email: aidasambotas@gmail.com  
🌐 GitHub: [github.com/Aidas415](https://github.com/Aidas415)