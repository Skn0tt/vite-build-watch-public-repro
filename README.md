1. `npm ci`
2. `npx vite build --watch`
3. edit contents of `public/foo`

expected: `dist/foo` contains updated content

actual: `dist/foo` contains content old content from when `npx vite build --watch` was started