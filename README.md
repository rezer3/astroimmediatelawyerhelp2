# ImmediateLawyerHelp Astro Starter

## Install
```bash
npm install
```

## Run locally
```bash
npm run dev
```

## Build static output
```bash
npm run build
```
Output will be in `dist/`.

## Assets
Copy your current `/assets` folder into `public/assets/` so URLs like `/assets/styles.css` keep working.

## Add a new page
Create:
- `src/pages/personal-injury/index.astro` → builds to `/personal-injury/`

Use `SiteLayout.astro` and paste only the page body (everything between header and footer) into the `<SiteLayout> ... </SiteLayout>` slot.
