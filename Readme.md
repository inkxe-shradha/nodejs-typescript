## NodeJs with TypeScript

Here in this Basic Project Initialization we are going to integrate the Node.js with typescripts.

## Installation

- It required [Node.js](https://nodejs.org/) v18 to run.
- It required [TypeScript](https://www.typescriptlang.org/) v4.7.3+ to work smoothly
- We need to config the **(tsconfig.json)** to let the typescript to define it's rules and configurations

```sh
npm install / yarn add
yarn start
```

### tsconfig.json

(Compiler Options)

- **Module** -> CommonJs(required method) to NodeNext(Help to generate ES Modules)
- **moduleResolution** -> NodeNext (Which determine to find typescript will find that code we are in for)
- **target** -> ES2020 (Deploy for the morder browser understanding)
- **sourceMap** -> used for mostly mapping the typescript code into javascript so that it will be easy for debugging
- **outDir** -> for compiling the lastly javascript code
