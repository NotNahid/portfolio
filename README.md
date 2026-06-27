# Not Nahid Portfolio - Astro Migration

This is a migration of the Not Nahid portfolio from raw HTML/CSS to Astro.js.

## Project Structure

- `src/pages/`: Contains the individual pages (index, works, info, labs, social).
- `src/layouts/`: Contains `MainLayout.astro`, the shared wrapper for all pages.
- `src/components/`: Contains reusable components like `Navigation.astro` and `Star3D.astro`.
- `src/styles/`: Contains the global CSS.

## Features

- **100% Visual Consistency**: The site looks exactly the same as the original.
- **DRY (Don't Repeat Yourself)**: Shared headers, footers, and navigation are now centralized.
- **Zero JavaScript**: Astro ships zero JS by default, maintaining the high performance of the original site.
- **Improved Maintainability**: Changing a navigation link now only requires one edit.

## Commands

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the static site for deployment.
