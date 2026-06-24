# AGENTS.md

Guidance for cloud agents and automated development environments working in this repository.

## Repository type

This is a **GitHub profile README** repository (`WhatsYourWhy/WhatsYourWhy`). It contains a single tracked file, `README.md`, which renders on https://github.com/WhatsYourWhy.

There is **no application code**, package manifest, Docker setup, database, or test suite in this repo. Linked projects (Hardstop, Lumina-Pro, Biological-Data-OS, etc.) live in separate repositories.

## Cursor Cloud specific instructions

### Services

| Service | Required? | Notes |
|---------|-----------|-------|
| *(none)* | No | Nothing to start, build, or deploy from this repo |
| GitHub profile rendering | External | README displays on GitHub after push to `main` |

### Lint / validate

Default markdownlint rules flag intentional GitHub-profile HTML (`<div>`, `<details>`, badges). Use a relaxed config or skip strict lint unless you are standardizing the README format.

Recommended checks for README edits:

```bash
# Structure smoke test (no repo config required)
python3 -c "
from pathlib import Path
import re, sys
t = Path('README.md').read_text()
assert 'Choose your path' in t and t.count('github.com/WhatsYourWhy/') >= 5
print('README structure OK')
"

# Optional: markdownlint with profile-friendly disables
npx --yes markdownlint-cli README.md \
  --disable MD013 MD033 MD041 MD040 MD060 MD022
```

### Preview locally

```bash
npx --yes marked -i README.md -o /tmp/readme-preview.html
python3 -m http.server 8080 --directory /tmp
# open http://localhost:8080/readme-preview.html
```

### Working on linked applications

To develop or test a real product, clone the target repo (for example `Hardstop`, `Lumina-Pro`, or `Biological-Data-OS`) into a separate workspace and follow that repo's README.

### Git workflow

- Primary branch: `main`
- Changes are validated by rendering on GitHub; there is no CI in this repository.
