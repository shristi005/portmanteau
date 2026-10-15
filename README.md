# Portmanteau

Portmanteau is a calm, local-first packing-list planner for trips, college, hackathons, work, and everyday outings.

## Features

The current build establishes the responsive application shell and visual design system:

- Create, edit, duplicate, and delete packing lists
- Add, edit, remove, and check off packing items
- Track progress with filters for all, packed, and unpacked items
- Sort lists by name or recent updates
- Persist packing lists in a versioned browser `localStorage` key
- Responsive mobile navigation, forms, dialogs, empty states, and notifications
- Warm, nature-inspired colour tokens and accessible focus states

## Technology

- React 18 with JavaScript
- Vite
- Bootstrap 5 for layout utilities
- Lucide React for interface icons
- CSS custom styling

## Getting started

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

## Persistence

Lists are stored under `portmanteau:v1:lists` in the browser's `localStorage`. Storage is specific to the current browser and device; it does not sync across devices or provide online backup.

## Limitations

This project does not use an account, backend, external API, AI service, or remote database. Clearing browser site data removes the locally stored lists and templates.

## Screenshots

Screenshots can be added here after the interactive application is complete.