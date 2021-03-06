## A Simple Nodejs API Boilerplate

## Features

- ES6 features/modules
- ES7 async/await
- Configuration management by [dotenv](https://www.npmjs.com/package/dotenv)
- Logging by [winston](https://www.npmjs.com/package/winston)
- Tests by [supertest](https://www.npmjs.com/package/supertest) and [jest](https://jestjs.io)

---

## Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node) or [Yarn](https://yarnpkg.com/en/docs/install)
- [MongoDB](https://www.mongodb.com/download-center/community)

## Installation

1. Clone the project `git clone https://github.com/andydev404/nodejs-api-boilerplate.git`.
2. Install dependencies `yarn install` or `npm install`
3. Create a `.env` file in the root like the `.env.example` file.
4. For dev you need to have mongodb db locally.

---

## Scripts

### DEV

```bash
npm run dev
```

### Testing

```bash
npm run test
```

---

## Todo

- [x] Test routes
- [x] Docker
