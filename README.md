# Typescript Starter Template

A simple starter template for building small web projects with TypeScript.
This setup includes a basic HTML file, a TypeScript entry file, automatic compilation, and a lightweight development server.

## 📁 Project Structure

```plaintext
/
├── dist/
│   └── index.js   # Compiled JavaScript
├── src/
│   └── index.ts   # Main TypeScript file
├── index.html     # Main HTML file
├── tsconfig.json  # TypeScript configuration
└── package.json   # Project dependencies

```

## 🚀 Getting Started

### 1. Install Dependencies

Run the following command once after cloning the repo:

```
npm install
```

### 2. Start TypeScript Compiler (Watch Mode)

This will automatically recompile your TypeScript whenever you save:

```
tsc -w
```

### 3. Start the Development Server

This opens the project in your browser using **lite-server**:

```
npm start
```

## 🛠 How It Works

- `index.ts` (inside src) compiles into `index.js` inside dist.

- You can edit your TypeScript files freely, and the watch mode will rebuild on every save.

- lite-server automatically refreshes your browser when you update files.

## 📌 Requirements

Node.js and npm installed

TypeScript compiler installed globally or locally (`tsc`)
