

# Typescript Starter Setup v4.6.2

created date for this project-folder: 2022Mar18


<br>
<br>
<br>


```
nvm use v16.12.0

npm init -y

touch README.md .gitignore index.ts

```


<br>
<br>
<br>


```npm install typescript --save-dev```
- install ts as dev-dependecies
- current ts version as of this folder creation is v4.6.2


<br>
<br>
<br>


at index.ts
```typescript
const greet = () => {
    console.log('hello world!');
}

greet()
```


<br>
<br>
<br>


```npx tsc```
- mag print yung common commands ng tsc

- see [commonTSCommands.md](./commonTSCcommands.md) on this project folder


<br>
<br>
<br>


```tsc --init```
- to initialize tsconfig.json


<br>
<br>
<br>


to compile: ```tsc```
- the index.ts will compile to index.js
- pwede din ilagay sa script ng package.json

<br>
<br>
<br>


outputs index.js:

```javascript

"use strict";
var greet = function () {
    console.log('hello world!');
};
greet();

```


<br>
<br>
<br>


```tsc --watch```
- to auto compile while coding
- pwede din ilagay sa script ng package.json


<br>
<br>
<br>


