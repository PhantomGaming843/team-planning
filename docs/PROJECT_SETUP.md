# Project Setup (Once per repo)

## A) Create the Repo
1. On GitHub, **New repository** → name `team-planning` → Public or Private.
2. Add README and MIT License.

## B) Create a Projects Board (not “classic”)
1. Go to **Projects** (top nav) → **New project** → **Board** (or **Table**)
2. Add fields:
   - `Status` (Single select): `Todo, In Progress, Blocked, In Review, Done`
   - `Priority` (Single select): `High, Medium, Low`
   - `Target Sprint` (Text or iteration)
3. Add views: `Board` (group by `Status`), `Backlog` (table, sort by Priority), `This Sprint` (filter by Target Sprint).

## C) Auto‑add Issues to the Project
1. In the Project → **Workflows** → enable **Auto‑add to project**.
2. Optional rules: if label = `priority: high`, set `Priority=High`.

## D) Labels (create in Repo → Issues → Labels)
- `todo` (gray)
- `in-progress` (blue)
- `blocked` (red)
- `review` (purple)
- `done` (green)
- `priority: high` (red), `priority: med` (orange), `priority: low` (yellow)
- `meeting` (teal), `question` (pink)

## E) Branch Protection (recommended)
1. Settings → Branches → Add rule for `main`.
2. Require PR review, dismiss stale approvals, require status checks (if any).

## F) Enable Discussions (optional)
Repo → Settings → General → **Features** → check **Discussions**.
