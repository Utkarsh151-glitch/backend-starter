# Backend Starter (work in progress)

**A Node.js backend I am building from scratch to learn backend development in JavaScript.**

![Node.js](https://img.shields.io/badge/Node.js-ES%20modules-339933?logo=node.js&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20progress-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Status

The project structure and tooling are set up; the application code is not written yet.

- `src/index.js`, `src/app.js` and `src/constants.js` are empty placeholders
- Data model sketch: [Eraser diagram](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj)

## Tooling in place

- ES modules (`"type": "module"`)
- `npm run dev` runs `src/index.js` with nodemon
- Prettier config (`.prettierrc`, `.prettierignore`)
- `.env.sample` for environment variables (copy to `.env`, which is git-ignored)
- `public/temp/` for temporary file uploads

## Getting started

```bash
npm install
cp .env.sample .env
npm run dev
```

## Project structure

```text
├── public/temp/       # temporary uploads (kept with .gitkeep)
├── src/
│   ├── index.js       # entry point (placeholder)
│   ├── app.js         # app setup (placeholder)
│   └── constants.js   # shared constants (placeholder)
├── .env.sample
└── .prettierrc
```

## Author

Utkarsh Vaibhav · [GitHub](https://github.com/Utkarsh151-glitch) · [LinkedIn](https://www.linkedin.com/in/utkarsh-vaibhav-76aa99300/)
