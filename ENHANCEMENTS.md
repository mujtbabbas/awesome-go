# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/avelino/awesome-go>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, credit, and a Contents entry for it.

- Added this changelog (ENHANCEMENTS.md).
- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation; upstream workflows — tests.yaml running the
  real Go test suite, run-check, pr-quality-check, site-deploy — kept as-is,
  so no additional code CI was needed).

- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).
- Dependabot: upstream already ships .github/dependabot.yml covering
  github-actions and gomod with weekly grouping — verified and kept
  exactly as-is (no duplicate added).

- Licence recorded: the LICENSE file in tree is the full MIT text
  ("The MIT License (MIT)", Copyright (c) 2014 Thiago Avelino), preserved
  exactly as-is.

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of avelino/awesome-go at upstream commit
  c75e96a0762f3c65e58c27defa219f8c271d4ccd (upstream HEAD dated 2026-10-19).

- Fork history severed; all 108 files and the MIT licence (LICENSE)
  preserved as-is.

- Notes: 2 upstream symlinks preserved as symlinks (.cursorrules ->
  AGENTS.md, .github/copilot-instructions.md -> AGENTS.md; the second is
  a broken relative link upstream, preserved unchanged). A connector
  snapshot push cannot carry symlinks.

- 5 tracked Go files under .github/scripts/ (check-pr-diff, check-quality)
  are ignored by upstream's own .gitignore; they were force-added so this
  baseline matches the upstream tree file-for-file.

- 48 binary files (site fonts in ttf/woff/woff2 and favicon/logo images
  under tmpl/assets/) are part of the baseline; a connector snapshot push
  cannot carry binaries.
