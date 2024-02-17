# My ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import plugin;

## Setup

### React (with Next.js)

Install dependencies:

```
npm i -D eslint @renanlido/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": [
    "@renanlido/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:

```
npm i -D eslint @renanlido/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@renanlido/eslint-config/react"
}
```

### Node.js

Install dependencies:

```
npm i -D eslint @renanlido/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@renanlido/eslint-config/node"
}
```

### Any similarity is no coincidence

Yes, it is based on [Rocketseat ESLint config](https://www.npmjs.com/package/@rocketseat/eslint-config), but, with my own spicy twist 🌶️😉😅.

### License

MIT - Feel free to use, share and modify.

### Acknowledgment ❤️

- [Rocketseat](https://rocketseat.com.br/)
- [diego3g](https://github.com/diego3g)
