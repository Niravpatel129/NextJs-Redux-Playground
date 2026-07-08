# Next.js Redux Playground

A small Next.js learning playground for experimenting with the `pages/` router, basic React page structure, and local development workflow.

Despite the repository name, the current codebase is still a minimal Next.js app and does not yet include Redux wiring.

## Current scope

- Next.js app using the legacy `pages/` directory
- Simple homepage component
- Basic CSS module styling
- Local development, build, and start scripts

## Tech stack

- Next.js 10
- React 17
- CSS Modules

## Getting started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open the app locally:

```text
http://localhost:3000
```

## Available scripts

```bash
npm run dev      # Start the local development server
npm run build    # Build the app for production
npm run start    # Start the production build
```

## Project structure

```text
pages/
  index.js        # Main page
  api/            # API route examples, if present
styles/           # CSS module styles
public/           # Static assets
```

## Status

This repository is best treated as a lightweight Next.js practice sandbox. Add Redux setup, slices/store configuration, and example state-driven UI before using it as an actual Redux reference project.
