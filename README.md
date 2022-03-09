# @tidio/typescript-config
Tidio typescript config

## Installation

To install use
```
yarn add -D @tidio/typescript-config
```

## Usage

Add `extends: "@tidio/typescript-config"` to your tsconfig.json. For example your `tsconfig.json` can look like this:

```json
{
    "extends": "@tidio/typescript-config",
    "compilerOptions": {
        "jsx": "react-jsx",
        "jsxImportSource": "@emotion/react",
        "moduleResolution": "node",
        "noEmit": true,
        "target": "es2021",
        "module": "ESNext",
        "baseUrl": ".",
    },
}
```