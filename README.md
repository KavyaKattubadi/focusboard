# FocusBoard

A responsive task dashboard built with React and Vite, based on the supplied FocusBoard Figma reference.

## Features
- Create, edit and delete tasks (with delete confirmation)
- Required task-title validation
- Status updates: To do, In progress and Completed
- Case-insensitive title search
- Status tabs and priority filter work together
- Live task statistics and completion progress
- Three-slide Focus Notes carousel with arrows and indicators
- Saves tasks in browser localStorage
- Responsive layouts for mobile, tablet and desktop

## Run locally
Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To create a production build, run `npm run build`; the output is in `dist/`.

## Notes
This is a frontend-only demo. Tasks are stored in the current browser and are not synced between devices. No backend, login, database or external API is used.