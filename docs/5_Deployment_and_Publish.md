# Deployment and Publish

This repository publishes the 102 reference site only. Application implementation is maintained in the upstream repositories.

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

## Upstream Repositories (Clone And Setup There)

```sh
git clone https://github.com/Cloud2BR-MSFTLearningHub/Agentic-DevOps-AI-Shopping.git
git clone https://github.com/Cloud2BR-MSFTLearningHub/Agentic-AI-Media-Assistant.git
```

After cloning, run setup from each repository README.

## Quality Checklist

- All local media paths resolve.
- No raw HTML printed as plain text.
- Preview links open in browser tabs.
- Download links are explicit and optional.
