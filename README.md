
# Pasadena Fires Digital Archive

This repository is used to manage metadata, images, and documents related to the Pasadena Fires Digital Collection, including change tracking and version history.

## Purpose

To ensure transparency and accountability for updates to the collection by documenting:

- Metadata updates
- New file uploads
- Correction of archival records
- Structural changes in folder organization

## Changelog Automation

This repository uses **GitHub Actions** to generate a `CHANGELOG.md` automatically based on commit messages. Follow the Conventional Commits format when pushing updates.

### Commit Guidelines (Conventional Commits)

Use these prefixes in commit messages:

- `feat:` — for adding new content or metadata
- `fix:` — for correcting information
- `docs:` — for changes to documentation
- `style:` — for non-functional formatting
- `refactor:` — for restructuring metadata layout
- `chore:` — for updates that don't affect content

### Sample Commits

```bash
git commit -m "feat: add metadata for 2009 Altadena fire"
git commit -m "fix: correct date on image_002.jpg"
git commit -m "docs: update contributing guidelines"
