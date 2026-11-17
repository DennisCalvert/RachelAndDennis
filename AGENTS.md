# Agent instructions

Cursor, Codex, and ChatGPT read this file. Follow it for every task in this repository.

## Repository

This is a static site. There is no package manager, build step, or test suite.

- `index.html` is the Rachel and Dennis wedding page.
- `las-vegas-day-trips.html` is the Beyond Las Vegas guide.
- Keep styles and scripts inline in those pages.
- Photos are remote URLs or Wikimedia Commons lookups. Keep the source and license note when a photo is shown.

Preview from the repository root:

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

Open `/` and `/las-vegas-day-trips.html`.

## Ship on main

After a task is done, commit the work and push it directly to `main`.

- Stay on `main`. Do not open a feature branch or a pull request.
- Stage only the files for the task.
- Write a short commit message that says what changed.
- Push with `git push origin main`.
- Do not force-push, and do not commit secrets.

Leave the work uncommitted only when the task is incomplete or the user asked to hold the change.
