# ServiceDesk — IT Support, Field Service & Helpdesk Manager

A single-file, offline-friendly service desk system for support agencies, IT teams, and field technicians. Manage support tickets, on-site field service jobs, clients, agents, and a knowledge base — all from one bilingual (Bangla / English) dashboard.

**[View Live Demo →](#)** *(replace with your GitHub Pages demo link)*

---

## Features

- **Ticket Management** — log, assign, prioritize (Urgent/High/Medium/Low), and track tickets through Open → In Progress → Resolved → Closed
- **Field Service Jobs** — schedule on-site visits with date, location, assigned technician, and status
- **Client Management** — store contact info and see each client's full ticket history
- **Agent Management** — track team members and their current ticket load
- **Knowledge Base** — save reusable solutions and troubleshooting guides, organized by category
- **Reports Dashboard** — resolution rate, tickets by status, tickets by agent
- **Day / Night theme** — toggle between light and dark mode
- **No backend required** — runs entirely in the browser using LocalStorage; no server, database, or account needed
- **Responsive** — works on desktop, tablet, and mobile

## Getting Started

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. That's it — demo data loads automatically on first run

No build step, no dependencies, no installation.

## Tech Stack

- HTML5, CSS3 (custom properties for theming), vanilla JavaScript
- Browser LocalStorage for data persistence
- Google Fonts (Space Grotesk, Inter, Hind Siliguri, JetBrains Mono)

## Data & Privacy

All data is stored locally in your browser's LocalStorage. Nothing is sent to any server. Clearing your browser data will reset the app; use the **Reset Demo Data** button in the sidebar to restore the sample dataset at any time.

## Important

This is a front-end, browser-based application. It does not include a hosted backend, cloud database, user authentication, or server-side ticket synchronization.

Your data persists in the browser until you clear site data or use the Reset Demo Data button — it does **not** auto-reset on its own, so it's safe for real day-to-day use. (The separately hosted live demo does reset nightly, so visitors always see a clean sample dataset — that behavior is not present in this package.)

## License

See `LICENSE` file.

## Support

Built and maintained by UpComing Solution. For customization, bulk licensing, or a hosted/multi-user version with a real backend, get in touch.
