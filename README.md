# MiyaraHub `.github`

Org-level repo for MiyaraHub Technologies. Hosts the **organization
profile README** at [`profile/README.md`](profile/README.md), which is
what renders on [github.com/MiyaraHub](https://github.com/MiyaraHub).

This repo intentionally has no code — it's a brand surface, not a project.

## What lives here

- `profile/README.md` — the public organization landing page
- `profile/*.png` / `*.jpg` — banner + per-app icons referenced from the
  README via raw GitHub URLs

## What does NOT live here

- App source code (proprietary, in private per-app repos)
- Workflow templates / SECURITY.md / FUNDING.yml — may land here later
  if there's a clear org-wide use, but none today

## Updating the landing page

Edit `profile/README.md`, commit, push. GitHub re-renders within a few
seconds. If image references break, raw GitHub URLs are pinned to the
`main` branch, so anything pushed there shows up.
