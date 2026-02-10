# Governance Process

This repository follows Hollow House Institute governance principles.

## Change Control

All changes must:
1. Be proposed via commit or pull request
2. Be reviewed against governance constraints
3. Receive explicit human approval if affecting:
   - Interaction definitions
   - Lock state
   - Canonical checksums

## Lock Discipline

Locked files are declared in `LOCK_MANIFEST.md`.

Changes to locked files require:
- Human authority approval
- Regeneration of checksums
- Updated lock manifest

## Escalation

If governance constraints conflict with implementation goals:
- Governance takes precedence
- Execution must stop until resolved
