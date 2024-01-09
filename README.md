# webpack-template

A simple template with Webpack, ESLint, & Prettier

# usage

1. Run the configurator for ESLint

`npm init @eslint/config`

2. Configure `eslint-config-prettier` by extending `.eslintrc` config

`extends: ["prettier"],`

https://github.com/prettier/eslint-config-prettier#installation

3. Get to work!

# optional stuff

1. Install `jest` for testing

- Run `npm install --save-dev jest`

- Add to `package.json`
```
{
  "scripts": {
    "test": "jest"
  }
}
```

- Add to `eslintrc` config
```
env: {
  "jest/globals": true,
}
```
