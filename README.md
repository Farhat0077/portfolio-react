# Farhat Hamraz Portfolio

React portfolio project using Vite, Tailwind CSS, Framer Motion, React Router, and Lucide icons.

## Requirements

Install a current Node.js LTS release (which includes npm) from https://nodejs.org/.

## Install and run on Windows

Open Command Prompt or the VS Code terminal in this project folder, then run:

```bash
npm install
npm run dev
```

Open the local URL Vite prints in the terminal.

## Build for production

```bash
npm run build
npm run preview
```

## Troubleshooting

- Use `npm`, not `nmp`.
- If Windows says `npm` is not recognized, install Node.js LTS and restart the terminal (or VS Code). Verify with `node -v` and `npm -v`.
- The React plugin is pinned to the Vite 6-compatible `@vitejs/plugin-react` 4.x line to avoid the peer-dependency conflict with plugin-react 6.x.
- If a previous failed install left a partial dependency tree, close the dev server, delete `node_modules` and `package-lock.json` if present, then run `npm install` again.


## Recent refinements

- Updated the interface to a clean black, white, and cool-gray palette with restrained soft accents.
- Removed the duplicate DesignerUp project card.
- Replaced dead `#` project links with working links to the developer GitHub profile where a dedicated live demo URL was not provided. These links do not claim to be direct links to individual repositories.
- Kept Vite and the React plugin on compatible major versions.


## Single-page layout
All portfolio sections are now on one scrolling page. The navigation uses section anchors for Home, About, Work, Education, Bookshelf, Tech Stack, and Contact.
