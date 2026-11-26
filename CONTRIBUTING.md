# Contributing to KhedmaOrg

Everything in this org is changed by pull request. Nobody pushes to `main` or `develop`, including the owners.

## Commits and PR titles (Conventional Commits)
`type(scope): summary`
- types: feat, fix, perf, refactor, test, docs, build, ci, chore, revert
- imperative mood, 72 characters max, no period
- breaking change: add `!` and a `BREAKING CHANGE:` footer
- footer links the work: `Refs #123` or `Closes #123`
- squash merge only, the PR title becomes the commit message

## Branches
- `feat/<issue>-<slug>`, `fix/<issue>-<slug>`, `chore/`, `docs/`, `refactor/`, `test/`, `ci/`, `perf/`
- `hotfix/<issue>-<slug>` from the production tag
- `release/x.y.z` for release hardening
- Repos with full branching: feature branches go to `develop`; `main` only receives `release/*` and `hotfix/*`
- Repos with trunk branching (config, docs, templates): feature branches go to `main`

## Pull requests
- Fill in the template. Keep it under about 400 changed lines.
- CI must be green (title, branch, linked issue, approval, tests).
- Approval must come from someone other than the author (the other owner). New commits dismiss earlier approval.
- High risk changes (migrations, auth, payments, infra, permissions) need a rollback plan and the label `risk: high`.

## Issues and backlog
Idea > Epic > Story > Task. Bugs, incidents and hotfixes have their own templates.
Priorities P0 to P3, severities S1 to S4. Status lives in the Roadmap project.
Definition of Ready: acceptance criteria, design link, estimate, owner, dependencies.
Definition of Done: merged, tests added, docs updated, verified on staging, flag state set, monitoring in place.

## Environments (current scope)
local, dev, staging. Pre-prod and prod are deferred and not set up yet.
