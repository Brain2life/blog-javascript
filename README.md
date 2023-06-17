# What is Babel js?

Original article at: 

## Tested on:
[Node v20.2.0](https://nodejs.org/en)

## Commands:
1. Install dependencies:
```shell
npm install --save-dev @babel/core @babel/cli
npm install --save-dev @babel/preset-env
```
2. Configure `.babelrc` file:
```
{
  "presets": ["@babel/preset-env"]
}
```
3. Run Babel CLI:
```shell
npx babel script.js --out-file compiled.js
```