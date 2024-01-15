# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Simple Import Sort;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @thasmorato/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@thasmorato/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @thasmorato/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@thasmorato/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @thasmorato/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@thasmorato/eslint-config/node"
}
```
