# Copilot instructions for this repository

Project summary
- Educational website for a high-school Computer Science course. Contains a static site (`index.html`, `assets/`) and assignment starter code in `assignments/`.

Primary goals
- Keep HTML semantic and accessible.
- Keep CSS simple and responsive; prefer utility classes in `assets/css/styles.css`.
- JavaScript should be modular, ES6+, and unobtrusive; put scripts in `assets/js/`.
- Python starter code should follow PEP8 and include simple comments and docstrings.

Files to focus on
- `index.html`, `assets/css/styles.css`, `assets/js/script.js`, `assignments/`, `templates/assignment-template.md`

Coding conventions
- HTML: semantic elements, sensible alt text for images, no inline styles when avoidable.
- CSS: concise rules, prefer classes over ids for styling, mobile-first breakpoints.
- JS: small functions, descriptive names, return values instead of global state when possible.
- Python: follow PEP8, include type hints where helpful, keep functions small and testable.

Behavior when making changes
- Produce complete, runnable snippets and update related files (e.g., update `index.html` and `assets/js/` together if needed).
- When adding new files, include a short one-line summary at the top and update `README.md` if the change affects usage.

Testing and preview
- No build step required. Use VS Code Live Preview / Live Server for local testing (`.devcontainer` includes `ms-vscode.live-server`).

Commit and PR guidance
- Commit messages: short imperative prefix (e.g., "Add", "Fix", "Refactor") followed by a concise description.
- When proposing larger changes, include a brief summary of intent and any manual test steps.

If unsure
- Prefer small, incremental changes and ask for clarification before large refactors.

Thank you — be concise and follow the project's existing style.

## Project Description

This project is an educational website for sharing homework assignments and coding exercises with students. Students can browse, view, and download assignments directly from the portal.

### Project Structure

- [`assignments/`](../assignments/) Each homework assignment is stored in its own subfolder with a consistent structure.
- [`templates/`](../templates/) Reusable templates for new content
- [`assets/`](../assets/) Contains the website assets including CSS, JavaScript, images, and configuration files
- [`index.html`](../index.html) The main website page that serves as a static portal for browsing and viewing assignments. Content is configurable via [`config.json`](../config.json) file to dynamically generate assignment lists and details.

### Project Guidelines

- Maintain consistent styling across all pages
- Keep file and folder names descriptive and organized

### Educational Standards

When generating content for this project:

- **Learning-focused**: All content should be designed with clear learning objectives and appropriate difficulty levels
- **Student-friendly**: Use clear, encouraging language that motivates students

### Testing the Instructions with Copilot

To test these custom instructions in Copilot, ask Copilot a prompt such as:

```
Briefly explain this project to me
```

Copilot should reference the repository purpose, structure, and educational standards above in its response.
