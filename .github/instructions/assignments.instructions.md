# Assignments — contributor instructions

Purpose
- Describe the expected structure and conventions for assignment folders so contributors and teachers can add consistent content.

Folder structure
- Each assignment is a directory under `assignments/` named with a short slug (e.g., `python-basics`).
- Recommended files inside an assignment folder:
  - `README.md` — assignment description, learning objectives, and instructions for students.
  - `starter-code.py` (or language-appropriate starter files) — starter code students can download and run.
  - `data/` or assets — optional supporting files (datasets, images).

Content guidelines
- Keep learning outcomes clear and concise (3–5 bullets).
- Provide example input/output where relevant and include any test instructions.
- Prefer plain-language, student-friendly tone and accessible examples.

File naming and metadata
- Use kebab-case slugs (lowercase, hyphens). Avoid spaces and special characters.
- If an assignment needs attachments, list them in `README.md` and ensure paths are relative.

Testing & preview
- No build step required — local testing can be done by opening `index.html` in Live Preview / Live Server.

Adding a new assignment
1. Create `assignments/<slug>/` with the recommended files.
2. Add a short entry to `config.json` with `id`, `title`, `description`, `path`, and `dueDate`.
3. Open a PR with a descriptive commit message and checklist of manual verification steps.

Review checklist for maintainers
- Does the `README.md` state clear objectives and student-facing instructions?
- Are file names and paths correct in `config.json`?
- Do starter files run without syntax errors?

Thank you — follow these conventions to keep the course materials consistent and student-friendly.

---
applyTo: "assignments/**/*.md"
---

# Assignment Markdown Structure Guidelines

All assignment markdown files should follow these guidelines:

## 1. Template Usage

- Assignment markdown files must follow the structure in [`templates/assignment-template.md`](../../templates/assignment-template.md).
- The assignment must be created as a `README.md` file
- Do not remove or skip required sections from the template.

## 2. Section Guidance

The section headers should reflect the structure in the template, including the exact icon usage.

- **Title**: Replace `[Assignment Title]` with a short, descriptive name (e.g., `Python Basics`, `Loops and Conditionals`, `Functions and Modules`).
- **Objective**: Write 1-2 sentences summarizing what the student will learn or accomplish. Focus on the main skills or concepts.
- **Tasks**: For each task:
  - Use a specific, action-oriented task name
  - In the Description, clearly state what the student must do.
  - In Requirements, use bullet points to list the expected outcomes or features. Be specific and measurable
  - Provide example input/output in code blocks if helpful.

Do not include extra sections unless explicitly specified.
