# NPM Module Boilerplate

This is a boilerplate for npm modules which includes the following configurations:
- Babel
  - preset-env
  - Module Resolver plugin
- Eslint:
  - Custom Rules
  - Import resolver babel module plugin
- NPM
  - For usage as github package
- VSCode
  - Autocompletition with configured module resolvers on Babel and Eslint

## Usage
In order to use this boilerplate run:

```bash
export MY_MODULE_NAME=<<my-module-name>>
git clone https://github.com/bermann/npm-module-boilerplate $MY_MODULE_NAME
cd $MY_MODULE_NAME
rm -rf .git
git init
```

The above script will clone this repo and create a new repo for your project.

---
**NOTE**

Remember to update the name under `package.json` and the user/organization under `.npmrc`

---