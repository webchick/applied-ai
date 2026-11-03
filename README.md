# Applied AI Field Guide

A public, personal-first cookbook of practical AI recipes, experiments, patterns, and small applications. Written for future me and anyone who wants to reproduce the work.

**Status:** early-stage learning notebook. Drafts are labeled, and results are not claims of production readiness.

## Browse

- [Recipes](docs/recipes/index.md): repeatable instructions
- [Experiments](docs/experiments/index.md): hypotheses, observations, and failures
- [Projects](docs/projects/index.md): working applications and case studies
- [Patterns](docs/patterns/index.md): reusable approaches and tradeoffs

## Conventions

Every entry should say what problem it solves, what was actually tested, and what remains uncertain. Never publish employer-confidential information, private training material, credentials, or personal data. Recreate examples independently with public or synthetic data.

## Website

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). To preview locally:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

GitHub Actions deploys to GitHub Pages after Pages is configured to use **GitHub Actions** as its source. Expected URL: https://webchick.github.io/applied-ai/

## Contributing

For now this is a personal learning journal published in the open. Issues with corrections and ideas are welcome. A broader contribution theme and process may come later.

Code: MIT (`LICENSE-CODE`). Documentation: CC BY 4.0 (`LICENSE-DOCS`).
