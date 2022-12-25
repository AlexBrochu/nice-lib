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
