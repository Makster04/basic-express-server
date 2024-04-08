# Basic-Express-Server
* **Dev Deployment**= https://basic-express-server-1.onrender.com
* **Main Development**= https://basic-express-server-kh0q.onrender.com

## Getting Started

### Requirements
For development, you will only need Node installed in your environment. Please use the appropriate Editorconfig plugin for your Editor (not mandatory).

### Install
* `git clone git@github.com:Makster04/basic-express-server.git`
* `cd PROJECT`
* `npm install`

### Configure app
Any environment configuration steps.

### Start & watch
* `npm run dev`
* `npm start`

### Test
* `npm test`
* `npm test:watch`

## Architecture
* ├── .github
* │ ├── workflows
* │ │ └── node.yml
* ├── tests
* │ ├── server.test.js (integration test)
* ├── src
* │ ├── error-handlers
* │ │ ├── 404.js
* │ │ ├── 500.js
* │ ├── middleware
* │ │ ├── logger.js
* │ │ ├── validator.js
* │ └── server.js
* ├── .eslintrc.json
* ├── .gitignore
* ├── index.js
* ├── package.json
* └── README.md

## Languages & Tools
- JavaScript
- Node
- Express
- Cors
- Dotenv
- Jest
- Nodemon
- Supertest

## Change Log
- **0.0.1** (2020-12-14)
