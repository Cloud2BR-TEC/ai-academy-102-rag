# Deployment and Publish

## Local Validation

```sh
python -m pip install --upgrade pip
pip install mkdocs mkdocs-material pymdown-extensions
mkdocs build --strict
mkdocs serve
```

## Publish To GitHub Pages

1. Push changes to `main`.
2. Wait for `Deploy GitHub Pages` workflow completion.
3. Validate links, preview buttons, and download actions.

## Quality Checklist

- All local media paths resolve.
- No raw HTML printed as plain text.
- Preview links open in browser tabs.
- Download links are explicit and optional.
