# Installation

[🔙](../README.md)

## Make sure you have Node.js installed.

```bash
node --version
v16.13.0
npm --version
8.1.0
npx --version
8.1.0
```

## Initalize the project.

```bash
npm init -y
```

## Install TypeScript

```bash
# Node.JS packages are std ways to develop both frontend and backend using JavaScript.
# As we use TypeScript, we need to install it. This will install the tsc command.
npm i typescript
# Check the version of TypeScript
tsc -v
Version 4.6.4
# This will create a "tsconfig.json" file in the root of the project.
# It's used to store the TypeScript compiler options.
npx tsc --init --rootdir src --outdir dist
```

## Run

```bash
# TS not executable by default by Node.JS or Browser.
# To make it executable, we need to compile it.
npx tsc --watch
# The --watch flag will automatically compile the TypeScript files as they are changed.

# Run the index.js file within the lib folder.
node dist/index.js
```
