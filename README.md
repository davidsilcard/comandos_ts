# comandos_ts

```js

npm init -y
mkdir src
touch src/index.ts
npm i typescript tsx tsup -D
npx tsc --init

{
"compilerOptions": {
"target": "ES6",
"module": "CommonJS",
"outDir": "./dist",
"strict": true,
"esModuleInterop": true
}
}

  "scripts": {
    "dist": "tsup src",
    "start:dev": "tsx --env-file=.env src/server.ts",
    "start:watch": "tsx --env-file=.env watch src/server.ts",
    "start:dist": "npm run dist && --env-file=.env node dist/server.cjs"
  },

touch .gitignore
node modules/
.env

```
