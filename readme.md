# React NPM package boilerplate

Boilerplate for building a react component as NPM package.

⚡️ Build NPM modules for your ReactJS project incredibly fast.

✅ ES5, ES6 compatible

✅ ReactJS ^16.6.1

------------

### ➡️ How to start?

1. **Clone** project into your working directory using 

ssh: `git clone git@github.com:bllago/react-npm-package-boilerplate.git` 

or

https: `git clone https://github.com/bllago/react-npm-package-boilerplate.git`

2. Switch to the **react-npm-package-boilerplate** directory 

`cd react-npm-package-boilerplate`

3. Run 

`npm install`

or

`yarn install`

4. Open react-npm-package-boilerplate **/src/index.js** in your favorite IDE and start work on your awesome NPM package

------------

### ➡️ How to change GIT remote origin?

1. Run `git remote remove origin`
2. Run `git remote add origin <link_to_your_repo_here>`

------------

### ➡️ How to build component?

1. Just run `npm run build` or `yarn build`. After that, you will see generated **index.js** file in your root folder *(react-npm-package-boilerplate/)*

------------

### ➡️ How to test component locally?

1. Get your NPM package (project) path. Run `pwd` in your terminal and copy path

2. Create test project. Run:

`npx create-react-app my-test-project`

3. Swith to the **my-test-project** directory:

`cd my-test-project`

4. Run:

`yarn add <paste copied path here>`

5. Import component

`import Component from 'react-npm-package-boilerplate'`

`<Component />`

6. Success

------------

### ➡️ How to add peerDependencies?

1. Open **package.json** file, find "peerDependencies" section and add dependencies there

------------

### ➡️ How to publish NPM package

Step 1: Use `publishConfig` option in your package.json

`"publishConfig": { "registry": "https://npm.pkg.github.com/" }`

Step 2: Authenticate

`$ npm login --registry=https://npm.pkg.github.com/`

`Step 3: Publish`

$ npm publish

------------

### ➡️ Troubleshooting

[How to handle peer dependencies when developing modules](https://dev.to/yvonnickfrin/how-to-handle-peer-dependencies-when-developing-modules-18fa "How to handle peer dependencies when developing modules")

------------

### ➡️ Contribution

If you're reading this, you're awesome! Thank you for helping us make this project great. Here are a few guidelines that will help you along the way.

[Contributor covenant](https://www.contributor-covenant.org/ "Contributor covenant")

[How to contribute to an open-source project on Github](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

------------

### ➡️ Inspired by

[Manoj Singh Negi](https://medium.com/@manojsinghnegi)

------------

### ➡️ License

This project is licensed under the terms of the MIT license.