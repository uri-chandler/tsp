# **TypeScript & VS Code - Project Starter Kit**

This repository has a very basic TypeScript project setup that I use from time to time.

It includes the following:

- TypeScript
- Jest
- ESLint for TypeScript
- Prettier
- Recomended accompanying VS Code extensions

## **VS Code Setup**

1. The Jest extension is configured to automatically run `src/**/*.spec.ts` files on-save.

2. The **Save And Run Ext** extension is configured to restart the debugger for any `src/**/*.ts` files  on-save *(ignoring `src/**/*.spec.ts` files)*.  

    > This behavior can be controlled by enabling/disabling the extension using **`Cmd + Shift + P`**

## **NPM Scripts**

1. Start the app using

   ```shell
   npm start
   ```

2. Run tests using

   ```shell
   npm test
   ```
