✅ Galutinė versija su badge ir papildomais patobulinimais
# 🧪 API Booker – Postman Test Automation

![CI Status](https://github.com/Aidas415/api-booker/actions/workflows/postman-actions.yml/badge.svg)

This project automates REST API testing using a [Postman](https://www.postman.com/) collection and [Newman](https://www.npmjs.com/package/newman), integrated into a CI/CD pipeline via GitHub Actions.

## 🌐 Target API

- **System**: [Restful Booker](https://restful-booker.herokuapp.com)
- **Environment**: `booker-env.postman.json`
- **Collection**: `postmanBooker` (Postman collection file)

## 🚀 Run Locally

1. Install [Node.js](https://nodejs.org/) (version 18 recommended)
2. Install Newman globally:
   ```bash
   npm install -g newman


- Run the tests:
npm run test


This command runs the postmanBooker collection using the booker-env.postman environment.

⚙️ CI/CD with GitHub Actions
Tests are automatically triggered:
- On push to the main branch
- On pull_request to the main branch
Workflow file: .github/workflows/postman-ci.yml
📊 Test Reporting
You can enhance this setup by:
- Adding HTML or JSON reports via Newman reporters
- Integrating with services like Allure or ReportPortal
📁 Project Structure

```
├── 📄 postmanBooker (Postman collection)
├── 📄 booker-env.postman.json
├── 📄 package.json
├── 📁 .github
│   └── 📁 workflows
│       └── 📄 postman-ci.yml
└── 📄 README.md
```

📜 License
This project is licensed under the ISC License.
👤 Author
Created by Aidas.
Feel free to fork, contribute, or reach out!

