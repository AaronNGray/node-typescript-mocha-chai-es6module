# node-typescript-mocha-chai-es6module
Node.js & TypeScript + Mosha & Chai with ES6 Modules

```
npm install --save-dev esm
```

package.json
```
  "type": "module",
  "scripts": {
    "test": "mocha --require esm --require ts-node/register src/**/*.test.ts"
  },
```
