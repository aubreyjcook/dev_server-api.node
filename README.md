# dev_server-api.node

Development of a server api in node for general use cases, particularly under consideration for bot development by developer AJC.

## Purpose

This project is intended to develop a server api in node for general use cases, particularly under consideration for bot development. The project is developed and maintained by developer AJC with the intention of being deployed on self-configured servers for personal use.

## To-dos

- [ ] Select a license.
- [ ] Send ChatGPT project outline.
- [ ] Config Node via NPM.
- [ ] Config Node runner.

## Init-Config Log

**Server Init Config**
```
PS C:\Users\user\Code\repos\personal\dev_server-api.node> node -v
v20.15.0
PS C:\Users\user\Code\repos\personal\dev_server-api.node> npm -v
10.8.3
PS C:\Users\user\Code\repos\personal\dev_server-api.node\server> npm init -y
PS C:\Users\user\Code\repos\personal\dev_server-api.node\server> npm install express morgan express-rate-limit helmet dotenv

added 76 packages, and audited 77 packages in 4s

16 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS C:\Users\user\Code\repos\personal\dev_server-api.node\server> npm install --save-dev jest nodemon eslint supertest
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported

added 370 packages, and audited 447 packages in 23s

69 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```