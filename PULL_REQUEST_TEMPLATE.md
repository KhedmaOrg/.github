## What and why
<!-- One short paragraph. Why this change, not only what. -->

## Linked issue
<!-- Closes #123 | Refs #123 | No issue: <reason> (checked by CI) -->

## How it was tested
- [ ] Unit
- [ ] Integration
- [ ] Manual or e2e (describe)

## Risk
- Risk level: low / medium / high
- High means: migrations, auth, payments, infra, permissions. High needs a written rollback below and the label `risk: high`.

## Rollout plan
<!-- Feature flag? Which environments? Order? -->

## Rollback plan
<!-- How to undo this in one step. -->

## Screenshots (UI changes)

## Checklist
- [ ] PR title follows Conventional Commits (`type(scope): summary`)
- [ ] Branch name follows the convention
- [ ] Tests added or updated
- [ ] Docs updated
- [ ] DB migration is backward compatible (expand and contract)
- [ ] Feature flag state decided
- [ ] Security impact considered
- [ ] Analytics and monitoring considered
- [ ] Under about 400 changed lines (or explained)
