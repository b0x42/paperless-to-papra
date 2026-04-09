# Development Notes

Run `pnpm run build` and commit `dist/` whenever you change the source code before pushing. The built `dist/` is committed to the repo because `npm install -g github:...` is broken on npm 11 and doesn't run build steps reliably.
