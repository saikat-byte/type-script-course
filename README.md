# Type script is better version of Javascript

# Type script is superset of Javascript

# Import TS features

```
1. Define data type
2. Interfaces
3. Decorators
4. Generics
5. Namespaces
6. Type Inference
7. Advance Features
8. Code quality
```

# TypeScript Setup Guide

This guide will help you install and set up **TypeScript** in your project step by step.

---

## 1. Install Node.js

TypeScript runs on Node.js, so install it first:

# 1. Download and install the **LTS version** of Node.js from [https://nodejs.org](https://nodejs.org).

# 2. Verify installation by running:

```
node -v
npm -v
```

# 3. Install TypeScript

```
mkdir my-ts-project
cd my-ts-project
npm init -y
npm install typescript --save-dev
npx tsc -v
```

# 4. Create a TypeScript Configuration File

```
Generate a tsconfig.json file:
npx tsc --init

{
  "compilerOptions": {
    "target": "ES6",
    "module": "commonjs",
    "outDir": "./dist",
    "rootDir": "./src",
    "strict": true
  }
}

```

# 4. Write Your First TypeScript File

```
Create a folder named src
Inside it, create index.ts
Add the following code:


function greet(name: string): string {
  return `Hello, ${name}!`;
}

console.log(greet("TypeScript"));

```

# 5 Compile TypeScript to JavaScript

```
This compiles all .ts files into .js files inside the dist folder.
npx tsc

Run the compiled JavaScript:
node dist/index.js
```

# 6. ✅ You are now ready to code in TypeScript!

```

---

Would you like me to also add a **"Recommended VS Code Extensions"** section in the README for better TypeScript development (IntelliSense, linting, formatting)?


```
