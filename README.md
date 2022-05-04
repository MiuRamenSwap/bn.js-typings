# bn.js-typings

BN.js typings that allow natural imports.

## Install

```sh
yarn install --dev bn.js-typings
```

## Usage

First, you need to make sure that our package is included in your `tsconfig.json` file.

```json
"include": [
  "./lib/**/*.ts", 
  "./node_modules/bn.js/index.d.ts"
]
```

Copy to index.d.ts to under node_moduls (./node_modules/bn.js/)


Then use it simply like this:

```typescript
import { BN } from "bn.js"
```
