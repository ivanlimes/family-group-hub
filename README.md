# Family Group Hub v1.1.0

A standalone HTML prototype for a shared family dashboard.

This build is intended as a **working prototype** and **GitHub-ready static package**. It runs in the browser with **no install step** and stores data locally in the browser using localStorage.

## What this version does

- Manage household tasks
- Track payments
- View calendar items
- Switch between family members
- Rename family members
- Save data locally between refreshes
- Export and import local data
- Use light and dark mode

## Important limitation

This is **not yet a real-time multi-user app**.

It does **not** currently include:

- shared cloud sync
- household logins for multiple users
- Supabase-backed persistence
- push notifications
- live cross-device updates

Right now, this is the clean prototype lane: fast to test, easy to share, and useful for validating layout and behavior before porting to a full app stack.

## Files in this package

- `index.html` — the full standalone app
- `README.md` — this file
- `CHANGELOG.md` — version notes
- `VERSION.txt` — current version marker
- `.gitignore` — basic repo hygiene

## Run locally

### Option 1
Double-click `index.html`.

### Option 2
Open `index.html` in Chrome manually.

## Put it on GitHub

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Keep `index.html` in the repo root.
4. Commit the files.

## Publish with GitHub Pages

For a quick hosted prototype:

1. Open the GitHub repository.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
5. Save.

GitHub Pages should then publish the prototype as a static website.

## Recommended next move

Use this build as the **behavior source of truth**.

Then choose one path:

### Path A — Keep polishing the prototype
Best for layout, UX, wording, spacing, and workflow refinement.

### Path B — Port this into the real app stack
Best for login, shared household syncing, database storage, and notifications.

## Version naming

This package is labeled **v1.1.0** because it is the first cleaned working prototype package after the rename and event-wiring fixes.
