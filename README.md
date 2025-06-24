# Study Notifications Dashboard

A modern web dashboard for generating and managing Data Transfer Agreement (DTA) notifications for research studies.

![screenshot](docs/screenshot.png)

---

## Features

### Core Dashboard

* Displays study metadata in responsive card grid.
* Country & status filters, multi-select, and bulk operations.
* Generates fully-formatted notification text with deadlines and compliance details.
* One-click copy-to-clipboard.

### Quick-Win Enhancements (coming next)

* 🔍 **Search bar** and **sort controls** (code in progress)
* 📤 **Export selected studies** to CSV / JSON
* 🌙 **Dark-mode toggle**

### Advanced Road-Map

* ✉️ Email template & mail-to integration
* 📝 Re-usable notification template library
* 🕒 Activity tracking / audit history

---

## Project Structure

```
Notifications/
├── index.html                     # GitHub Pages entry – redirects to main dashboard
├── study_notifications_dashboard.html  # Full dashboard application
├── README.md
└── docs/ (optional)               # Assets such as screenshots
```

*`index.html`* is a lightweight redirect so GitHub Pages serves the app at
`https://logic06183.github.io/Notifications/`.

---

## Getting Started Locally

1. Clone the repository
2. Open `study_notifications_dashboard.html` in your browser

No build step is required – the app is **pure HTML/JS**.

---

## Deploying to GitHub Pages

1. Push to the **main** branch
2. Ensure **Pages** is enabled under *Settings → Pages → Branch: main / root*.
3. Visit **https://logic06183.github.io/Notifications/**

GitHub Pages detects `index.html`, then instantly redirects to the full dashboard.

---

## Contributing

Pull requests are welcome! Please open an issue first to discuss major changes.

---

## License

MIT
