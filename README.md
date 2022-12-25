# nice-lib

![npm (scoped)](https://img.shields.io/npm/v/@alexbrochu/nice-lib)
![npm bundle size](https://img.shields.io/bundlephobia/min/nice-lib)

Small library to test how to publish a lib in npm

# Install

```
npm install @alexbrochu/nice-lib
```

# Usage

```js
import {EventType, Test} from '@alexbrochu/nice-lib';

console.log(EventType);
console.log(Test.compute('hello'));
```

# Setup Typescript project

- Install typescript

```
npm i typescript --save-dev
```

- Compile typescript

```
npx tsc
```

- Using Google TypeScript Style to Lint and Correct Your Code

```
npm i gts --save-dev
npx gts init
```

https://www.digitalocean.com/community/tutorials/typescript-new-project

# How to link a package before sending it to npm repository?

This command will be link you node_modules package locally to your other project. Here I'm using @alexbrochu/nice-lib from my local environment

```
npm link @package/name
```

# Once tested you can use this command to bump the npm version and publis to npm repository

You have to login to npm before publishing
```
npm login
```

```
npm version [major-minor]
npm publish --access public # this will publish your package so it's available to everyone
```
