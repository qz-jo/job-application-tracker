# Job Application Tracker

A lightweight, privacy-friendly web app for tracking job applications without needing an account or backend.

## Problem it solves

When applying to multiple jobs, it becomes easy to forget which companies you applied to, the exact job title, application date, current status, job link, and follow-up notes. This app keeps everything in one simple dashboard.

## Features

- Add, edit, and delete job applications
- Track status: Applied, Interview, Offer, Rejected
- Search by company or position
- Filter by status
- Dashboard statistics
- Local browser storage
- JSON export/import backups
- Light and dark mode
- Responsive design

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`

No frameworks, backend, database, or API keys are required.

## Run locally

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Privacy

Application data stays in the browser unless the user explicitly exports a JSON backup.

## Future improvements

- Follow-up reminders
- CSV export
- Kanban board
- Cloud sync and authentication
- Response-rate analytics

## License

MIT
