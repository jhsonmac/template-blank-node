# template-blank-node
Template nodeJs/typeScript em branco com Eslint e Prettier configurados 


```
{
  "name": "backend",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT",
  "scripts": {
    "build": "tsc",
    "dev:server": "ts-node-dev --transpileOnly --ignore-watch node_modules src/server.ts"
  },
  "devDependencies": {
    "@types/express": "^4.17.6",
    "@typescript-eslint/eslint-plugin": "^3.4.0",
    "@typescript-eslint/parser": "^3.4.0",
    "eslint": "6.8.0",
    "eslint-config-airbnb-base": "^14.2.0",
    "eslint-config-prettier": "^6.11.0",
    "eslint-import-resolver-typescript": "^2.0.0",
    "eslint-plugin-import": "2.21.2",
    "eslint-plugin-prettier": "^3.1.4",
    "prettier": "^2.0.5",
    "ts-node-dev": "^1.0.0-pre.49",
    "typescript": "^3.9.5"
  },
  "dependencies": {
    "express": "^4.17.1"
  }
}

```
