This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started


First, intall dependencies and devdependencies:

```bash
npm install
# or
yarn install
```

Second, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## ESLINT Setup

For Javascript\
[Possible logic errors in code](https://eslint.org/docs/latest/rules/#possible-problems)\
[Suggestions](https://eslint.org/docs/latest/rules/#suggestions)\
[Layout & formatting](https://eslint.org/docs/latest/rules/#layout--formatting)

For ReactJS\
[List of supported rules](https://www.npmjs.com/package/eslint-plugin-react)

For React hooks\
[Hooks](https://www.npmjs.com/package/eslint-plugin-react-hooks)

Default set of rules [.eslisntrc.json](https://github.com/abidwai/style-guide-demo/blob/main/.eslintrc.json)

```
{
  "extends": ["next/core-web-vitals", "eslint:recommended", "plugin:react/recommended"],
  "rules":{
    "array-callback-return": ["error", { "allowImplicit": true, "checkForEach": true }],
    "for-direction": "error",
    "getter-return": "error",
    "no-async-promise-executor":"error",
    "no-await-in-loop":"error",
    "no-cond-assign": "error",
    "no-const-assign": "error",
    "no-constant-binary-expression": "error",
    "no-dupe-else-if": "error",
    "no-dupe-keys": "error",
    "no-duplicate-imports": "error",
    "no-empty-pattern": "error",
    "no-ex-assign": "error",
    "no-fallthrough": "error",
    "no-func-assign": "error",
    "no-inner-declarations": "error",
    "no-obj-calls": "error",
    "no-promise-executor-return": "error",
    "no-prototype-builtins": "error",
    "no-self-assign": "error",
    "no-self-compare": "error",
    "no-setter-return": "error",
    "no-sparse-arrays": "error",
    "no-template-curly-in-string": "error",
    "no-undef": "error",
    "no-unexpected-multiline": "error",
    "no-unreachable": "error",
    "no-unreachable-loop": "error",
    "no-unsafe-finally": "error",
    "no-unsafe-negation": "error",
    "no-unsafe-optional-chaining": "error",
    "no-use-before-define": "error",
    "require-atomic-updates": "error",
    "use-isnan": "error",
    "arrow-body-style": ["error", "as-needed"],
    "block-scoped-var": "error",
    "consistent-return": "error",
    "eqeqeq": ["error", "always"],
    "no-confusing-arrow": "error",
    "no-empty": "error",
    "no-empty-function": "error",
    "no-whitespace-before-property": "error",
    "quotes": ["error", "double"],
    "semi": ["error", "always"],
    "react/button-has-type":"error",
    "react/react-in-jsx-scope":"off",
    "react/prop-types":"off"
  }
}
```
