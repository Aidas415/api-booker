# 🚀 API Booker – Postman Test Automation

![CI Status](https://github.com/Aidas415/api-booker/actions/workflows/postman-actions.yml/badge.svg)

This project automates REST API testing using a [Postman](https://www.postman.com/) collection and [Newman](https://www.npmjs.com/package/newman), integrated into a CI/CD pipeline via GitHub Actions.

## 🌐 Target API

- **System**: [Restful Booker](https://restful-booker.herokuapp.com)
- **Environment**: `booker-env.postman.json`
- **Collection**: `postmanBooker` (Postman collection file)

## 🧬 Run Locally

1. Install [Node.js](https://nodejs.org/) (version 18 recommended)
2. Install Newman globally:
   ```bash
   npm install -g newman

## ▶️
- Run the tests:
npm run test

This command runs the postmanBooker collection using the booker-env.postman environment.

## ⚠️ Test Disclaimer

The project uses a public mock API designed for educational purposes. The API contains intentional bugs and inconsistencies — such as accepting invalid input, returning unexpected status codes, or allowing illogical data (e.g., checkout dates before check-in).
Some tests are expected to fail as part of the learning process. These failures are not due to incorrect test scripts, but rather reflect the API’s behavior and are left intentionally to highlight potential issues.


## ️ CI/CD with GitHub Actions

Tests are automatically triggered:
- On push to the main branch
- On pull_request to the main branch
Workflow file: .github/workflows/postman-actions.yml

## 📊 Test Reporting

You can enhance this setup by:
- Adding HTML or JSON reports via Newman reporters
- Integrating with services like Allure or ReportPortal
  
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

## 📜 License

This project is licensed under the ISC License.

## 👤 Author

Created by Aidas.  
Feel free to fork, contribute, or reach out — learning is better when shared!


