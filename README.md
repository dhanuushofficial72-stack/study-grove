# Study Grove

A lightweight, accessible study and assignment planner. No account, installation, or build step required.

## Use

Open `index.html` in a modern browser. Add assignments with course, due date, and priority; mark them complete; search and filter your plan. Use Export backup to save your assignments as JSON and Import backup to restore them.

Data stays in your browser's local storage. It does not sync across devices or browser profiles. Private browsing, moving the file, or clearing website data may remove access to saved tasks; keep backups. No analytics, third-party scripts, or network requests are included.

## Publish on GitHub

Create a repository named `study-grove` and upload `index.html`, `README.md`, and `LICENSE`. To serve it with GitHub Pages, choose the repository's main branch and root folder in Settings → Pages.

## Contribute

Open an issue describing the problem, steps to reproduce, and expected behavior. For changes, open a focused pull request with a description and manual verification steps. Useful future work includes editing assignments, course grouping, recurring study sessions, and calendar export.

## Manual checks

- Add assignments with different deadlines and priorities.
- Complete and uncomplete a task; verify counts and filters.
- Search by course and title; check both sorting choices.
- Reload and verify tasks persist.
- Export, add a task, then import the backup and verify restoration.
- Verify malformed backups are rejected.
- Navigate using only the keyboard and check the layout on a narrow screen.

## License

MIT. This is an initial project, with no claims about users, downloads, or eligibility for third-party programs.
