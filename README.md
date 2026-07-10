# CTO Executive Portfolio Cockpit

A complete, standalone executive portfolio governance application for managing technology initiatives across Infrastructure, Mobile, Broadband, CDN, Enterprise Network, TV, AI, Innovation, Compliance, Budget, Corporate, HR, Revenue and future areas.

The application is built entirely with:

- HTML
- CSS
- Vanilla JavaScript
- Browser LocalStorage

No backend, database, external libraries, build process or installation is required.

## Main features

- Executive dashboard with KPIs and charts
- Activity management
- Category management
- Drag and drop
- Table, Kanban, Timeline and Roadmap views
- Global search and advanced filters
- Smart alerts
- Executive, weekly, monthly, quarterly and annual reports
- CSV, Excel-compatible and JSON export
- Browser print / PDF export
- Full backup and restore
- Light and dark themes
- Responsive interface
- Automatic LocalStorage persistence
- Keyboard shortcuts

## Run locally

Download the repository and open:

```text
index.html
```

in a modern browser.

No local server is required.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this project.
3. Open the repository settings.
4. Select **Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save the configuration.

The application will then be available through the GitHub Pages URL assigned to the repository.

## LocalStorage

All activities, categories, settings and timeline events are stored in the browser LocalStorage.

Important:

- Data is associated with the browser and device being used.
- Clearing browser data may remove the saved portfolio.
- Use the built-in Backup function regularly.
- The generated JSON backup can be restored from the application.

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| Ctrl / Cmd + N | New activity |
| Ctrl / Cmd + F | Global search |
| Ctrl / Cmd + K | Quick search |
| Ctrl / Cmd + S | Full backup |
| Ctrl / Cmd + E | CSV export |

## Project structure

```text
cto-executive-portfolio-cockpit/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Architecture

The application is structured into modular JavaScript sections:

- Configuration
- Utilities
- State and persistence
- Search and filters
- Metrics and alerts
- UI rendering
- Task actions
- Canvas charts
- Reporting
- Export, backup and restore

This structure makes the project suitable for later evolution into a full web application with APIs, authentication and a backend database.

## Browser compatibility

Recommended browsers:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Security and privacy

The application does not send data to external services.

All portfolio information remains in the browser unless the user exports or backs it up manually.

## License

Released under the MIT License.


## Public deployment

This repository includes a GitHub Actions workflow for automatic deployment to GitHub Pages.

See `DEPLOYMENT.md` for the complete procedure and information about LocalStorage limitations.
