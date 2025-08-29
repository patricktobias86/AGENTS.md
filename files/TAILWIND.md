# Tailwind CSS snippets

## Frontend Framework
```markdown
## Frontend Framework
- Styling uses Tailwind CSS v4.
  - Import Tailwind in `client/styles.css` via `@import 'tailwindcss';`.
  - Define design tokens in a `@theme` block in `client/styles.css` (e.g., `--color-piPurple`, `--z-6`, `--shadow-btn`). These become usable as utilities like `bg-piPurple`, `z-6`, `shadow-btn`.
  - Add small component styles under `@layer components` and any custom utilities under `@layer utilities`.
  - PostCSS plugin must be `@tailwindcss/postcss` (see `postcss.config.js`).
```

## Code Style
```markdown
## Code Style
- Use **2 spaces** for indentation in all CSS files.
```
