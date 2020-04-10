# notes

1. Installed typescript and eslint
2. Need to run `typescript --init` so made a temporary `tsinit` npm script, but that didn't work, so had to `yarn global add typescript` then `typescript --init`, then realized it should've been `tsc --init`, then removed global install. End up with a `tsconfig.json`.
3. Enable `"jsx": "react",` in `tsconfig.json`
4. Touch a `.eslintrc.js` and add config from [`typescript-eslint`](https://github.com/typescript-eslint/typescript-eslint/blob/master/docs/getting-started/linting/README.md)
5. Touch a `.eslintignore` & add dist & node_modules
5. Create a folder to hold webpack stuff
6. yarn add react & stuff
