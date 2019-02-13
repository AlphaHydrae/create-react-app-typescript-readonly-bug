# [Create React App](https://github.com/facebook/create-react-app): Default linter and/or linting configuration cannot parse TypeScript's readonly modifier

See https://github.com/facebook/create-react-app/issues/6420

```
git clone https://github.com/AlphaHydrae/create-react-app-typescript-readonly-bug.git && \
  cd create-react-app-typescript-readonly-bug && \
  npm ci && \
  ./node_modules/eslint/bin/eslint.js src/App.tsx
```
