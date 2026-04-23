# Copilot instructions for this repository

Summary
- This is a small static web project for a course (Ingeniería II). Primary entry is index.html at repository root. Uses Bootstrap via CDN and simple assets under img/.

Build, test, and lint commands
- No build/test/lint scripts are present in this repository.
- How to run a single test: there are no test frameworks configured. If tests are added later, document the test runner (e.g., npm, pytest) and an example single-test command (e.g., npm test -- tests/file.test.js).

High-level architecture
- Single-page static website: index.html is the main page.
- Assets: img/ stores images used by pages (example: Club_Atlético_River_Plate_logo.svg.webp).
- Scripts: js/ is the intended location for JavaScript files; currently empty or unused.
- Styling: Bootstrap is pulled from CDN in index.html; no local CSS directory is present in the repo snapshot.

Key conventions and repository-specific notes
- Language: project content is predominantly Spanish; Copilot should prefer Spanish phrases when editing content unless an English change is explicitly requested.
- Entry points: look for index.html at the repo root and any HTML files in top-level folders (README references html/ and css/ folders though they may be absent).
- Asset paths: images use the img/ folder. Use relative paths when modifying HTML.
- Bootstrap: index.html relies on Bootstrap CDN; avoid adding conflicting local Bootstrap copies unless intentionally migrating to a local dependency.
- Minimal/no build tooling: assume edits will be used directly in the browser unless a package.json or build config appears later.

Where to look next
- README.md contains a short description and expected folder layout (html/, css/, js/, assets/). If files aren't present, look for student-submitted branches or later commits.
- No AI assistant config files were found (CLAUDE.md, .cursorrules, AGENTS.md, etc.). If adding one, document intent clearly at the top of that file and reference this copilot-instructions.md.

If changes are made
- If the project is converted to a Node/npm-based workflow, add package.json and document npm scripts here (build, test, lint) and update this file with single-test examples.

MCP servers
- This is a static web project. Would you like assistance configuring an MCP server for browser testing (Playwright) or visual regression? Reply with which you'd prefer.

## Recomendaciones
- Cada vez que ingreses un nuevo código, inserta un comentario en español que explique las etiquetas utilizadas
- los ejemplos y el contenido en general necesito que esten en español
