# Troubleshooting

## Build Fails On MkDocs Strict

- Confirm all nav entries exist.
- Confirm all referenced media files exist under docs.
- Confirm markdown blocks are properly closed.

## Link Opens Download Instead Of Preview

Use separate actions:

- Preview link: target normal browser page/image URL.
- Download link: explicit `download` attribute or ZIP artifact URL.

## Missing Logo/Favicon

Verify:

- `docs/assets/img/org-logo.png` exists.
- `mkdocs.yml` logo and favicon paths are correct.
