# ts-minimal-kit-cli

CLI installer for [ts-minimal-kit](https://github.com/k1de/ts-minimal-kit): minimal TypeScript template with strict typing and clean setup.

## Install

```bash
npm install -g ts-minimal-kit-cli
```

## Usage

```bash
ts-minimal-kit my-project
```

This will:
- Clone the template
- Remove git history  
- Initialize new repository
- Install dependencies
- Update TypeScript and add @types/node
- Open in VS Code (if available)

## Requirements

- Node.js >= 12.0.0
- Git
- npm

## What you get

Minimal TypeScript project:
- Strict typing enabled
- ES modules support (modern import/export)
- Source maps for debugging
- Declaration files for libraries
- Modern ESNext features
- Node.js types included (@types/node)

## Template structure

```
my-project/
├── src/
│   └── app.ts          # Main application file
├── dist/               # Compiled files (auto-created)
├── .gitignore          # Ignored files
├── package.json        # Project settings
├── tsconfig.json       # TypeScript configuration
└── README.md           # Project readme
```

## Available scripts

- Watch and compile: `npm run dev`
- Build: `npm run build`
- Run: `npm run start`
- Build and run: `npm run build:start`
- Clean: `npm run clean`

ISC © tish