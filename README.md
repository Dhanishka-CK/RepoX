#  RepoX



Any GitHub repo. Fully understood. In minutes.

RepoX transforms overwhelming codebases into interactive, AI-explained visual maps — so you can explore, learn, and contribute to any repository without the usual confusion.

## What RepoX Does
Most GitHub repos are a maze. Dozens of folders, hundreds of files, zero guidance. RepoX fixes that.
Paste any GitHub URL. RepoX builds you a live, interactive graph of the entire codebase, explains every file in plain English (or ELI5 if you want), and generates a personalized learning path so you always know what to read next.

## Features

- **Repository Visualization** - Interactive D3.js graph showing file structure and relationships
- **AI-Powered Explanations** - Get explanations for any file using Gemini AI (with ELI5 mode)
- **Learning Path Generation** - AI generates personalized learning paths for any codebase
- **Progress Tracking** - Track your learning progress with interactive checklists
- **Trending Repos** - Discover trending repositories from the week
- **Repo History** - Quick access to recently explored repositories

## Tech Stack

- **Frontend:** TypeScript, Vite, D3.js
- **AI:** Google Gemini API (via Cloudflare Worker)
- **Hosting:** Cloudflare Pages + Workers
- **APIs:** GitHub REST API, OSS Insight API


## Project Structure

```
repox/
├── src/
│   ├── main.ts           # Main application entry
│   ├── style.css         # Base/global styles
│   ├── app.css           # Component styles
│   ├── components/       # UI components (FileTree, Graph)
│   ├── services/         # API services (GitHub, Gemini)
│   ├── state/            # State management
│   └── types/            # TypeScript type definitions
├── worker/               # Cloudflare Worker (Gemini API proxy)
├── public/               # Static assets
├── dist/                 # Production build output
├── index.html            # HTML entry point
└── package.json
```

---






