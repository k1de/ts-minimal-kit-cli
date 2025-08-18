# ts-minimal-kit-cli

CLI installer for TypeScript minimal kits:
[ts-minimal-kit](https://github.com/k1de/ts-minimal-kit)
and
[ts-minimal-kit-web](https://github.com/k1de/ts-minimal-kit-web)

## Install

```bash
npm install -g ts-minimal-kit-cli
```

## Usage

### Minimal TypeScript kit template

```bash
ts-minimal-kit my-project
```

Installs [ts-minimal-kit](https://github.com/k1de/ts-minimal-kit): minimal TypeScript template with strict typing.

### Minimal TypeScript Web kit template

```bash
ts-minimal-kit-web my-project
```

Installs [ts-minimal-kit-web](https://github.com/k1de/ts-minimal-kit-web): TypeScript web framework with server + UI skeleton.

## What happens

Both commands will:

-   Clone the template
-   Remove git history
-   Initialize new repository
-   Install dependencies
-   Update TypeScript to latest
-   Open in VS Code (if available)

## Requirements

-   Node.js >= 18.0.0
-   Git
-   npm

## Template comparison

### 🎯 ts-minimal-kit

**Minimal TypeScript project:**

-   Strict typing enabled
-   ES modules support
-   Source maps for debugging
-   Declaration files
-   Modern ESNext features
-   Node.js types included

**Structure:**

```
my-project/
├── src/
│   └── app.ts          # Main application
├── dist/               # Compiled files
├── package.json        # Dependencies
└── tsconfig.json       # TypeScript config
```

[more info](https://github.com/k1de/ts-minimal-kit)

### 🚀 ts-minimal-kit-web

**Full-stack web framework:**

-   HTTP server with API support
-   Client UI framework (zero dependencies)
-   TypeScript strict mode
-   SPA routing support
-   Component library

**Structure:**

```
my-project/
├── src/
│   ├── server/         # Server-side code
│   │   ├── app.ts      # Main server
│   │   └── router.ts   # API routes
│   └── client/         # Client-side code
│       └── index.ts    # Client app
├── public/             # Static files
│   ├── index.html      # Main HTML
│   └── styles.css      # Base styles
├── dist/               # Compiled server
└── example/            # Example implementation
```

**UI Components:**

-   Cards, sections, modals
-   Forms, inputs, buttons
-   Tables, lists, grids
-   Tabs, progress bars
-   Alerts, toasts, badges

[more info](https://github.com/k1de/ts-minimal-kit-web)

ISC © tish
