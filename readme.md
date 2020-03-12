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

### How to add peerDependencies?

1. Open **package.json** file, find "peerDependencies" section and add dependencies there

------------

### How to publish NPM package

Inside your root project in the terminal type

`npm adduser`

then npm will ask for your username, password, and email if you don’t have an account with npm go create one first.

After above command user npm login command so you will be logged in to npm

`npm login`

It will again ask for your account information provide it and after that, we are good to go.

To publish your npm module just type

`npm publish`

and you just published your first npm module

------------

### Troubleshooting

[How to handle peer dependencies when developing modules](https://dev.to/yvonnickfrin/how-to-handle-peer-dependencies-when-developing-modules-18fa "How to handle peer dependencies when developing modules")