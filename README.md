# vitalityacademies.health

Standalone site for Vitality Academies. Independent repo, its own deployment.

Context: part of the DeBry / Vitality world (the physical "home base" brand:
facility, programs, community), but a separate property with its own domain.
Self-contained; shares no code with the Vitality CRM/Convex build.

## Deploy
GitHub Pages (org Ooak21) + custom domain via `CNAME` (vitalityacademies.health).
NOTE: this domain carries Google Workspace email. When DNS is pointed at Pages,
PRESERVE the existing MX records (only the apex A / www CNAME change).
Static for now: edit and push to `main`, Pages auto-deploys.
