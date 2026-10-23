# Changelog

All notable changes to this standalone edition of awesome-go are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, credit, and a Contents entry for it.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's workflows — `tests.yaml` running the real Go test suite, run-check, pr-quality-check, site-deploy — were kept as-is, so no additional code CI was needed.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Dependabot: upstream already ships `.github/dependabot.yml` covering github-actions and gomod with weekly grouping — verified and kept exactly as-is (no duplicate added).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [avelino/awesome-go](https://github.com/avelino/awesome-go) at upstream commit `c75e96a0762f3c65e58c27defa219f8c271d4ccd` (upstream HEAD dated 2026-10-19).
- Fork history severed; all 108 files and the MIT licence (`LICENSE`) preserved as-is, including the 48 binary site assets and the 2 upstream symlinks.
