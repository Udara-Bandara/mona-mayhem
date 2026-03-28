# Mona Mayhem — Copilot Instructions

## Project Overview
Mona Mayhem is a retro arcade-themed web app built with Astro v5. It compares GitHub contribution graphs of two users in a "battle arena" style. The project is designed for workshops and demos with GitHub Copilot and VS Code, but these instructions focus on the codebase itself (not the workshop content).

## Build & Development
- **Install dependencies:**
  ```sh
  npm ci
  ```
- **Start dev server:**
  ```sh
  npm run dev
  ```
- **Build for production:**
  ```sh
  npm run build
  ```
- **Preview production build:**
  ```sh
  npm run preview
  ```

## Astro Best Practices
- Use [Astro components](https://docs.astro.build/en/core-concepts/astro-components/) for UI structure and composition.
- Place pages in `src/pages/` and API endpoints in `src/pages/api/`.
- Use the [@astrojs/node](https://docs.astro.build/en/guides/integrations-guide/node/) adapter for server output (see `astro.config.mjs`).
- Prefer [islands architecture](https://docs.astro.build/en/core-concepts/islands/) for interactivity.
- Keep static assets in `public/`.
- Use `npm run astro` for direct Astro CLI access.
- Follow the [Astro Style Guide](https://docs.astro.build/en/guides/style-guide/) for code consistency.

## Project Structure
- `src/pages/` — Main pages and API routes
- `public/` — Static assets
- `astro.config.mjs` — Astro configuration
- `package.json` — Scripts and dependencies
- `docs/` — Additional documentation and styles

## Links
- [Astro Documentation](https://docs.astro.build/)
- [@astrojs/node Adapter](https://docs.astro.build/en/guides/integrations-guide/node/)

---

**Note:** Workshop instructions and step-by-step guides are in the `workshop/` folder and are not relevant to agent instructions.
