# React-vite-library

Reference: https://articles.wesionary.team/react-component-library-with-vite-and-deploy-in-npm-579c2880d6ff


## How to create a new library?

- Fork the repo
- Replace `react-vite-library` everywhere by the name of your app

```bash
npm ci
npx husky install
```

## Development

```bash
npm run dev
```

## Publish

```bash
npm run build
npm version x.y.z
npm publish
```
