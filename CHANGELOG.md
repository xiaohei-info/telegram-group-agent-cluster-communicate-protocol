# Changelog

All notable changes to this project will be documented in this file.

## 1.1.0 - 2026-05-24

### Added
- Open-source packaging for the Telegram group agent cluster coordination skill
- `config/skill-config.example.json` for local deployment templating
- `scripts/render_skill.py` to generate installable local skill output
- `scripts/audit_sensitive_strings.py` for local/sensitive-string audits
- Reviewer-backed pre-publication sanitization pass
- README guidance for rendering, installation, and publication hygiene
- `CONTRIBUTING.md` for future protocol/doc contributors

### Changed
- Reworked local role/bot roster content into config-driven rendered references
- Replaced deployment-specific identifiers with generic placeholders
- Rewrote several runtime notes to be deployment-generic rather than workspace-specific

### Security
- Removed real local bot handles, bot IDs, workspace names, and absolute local paths from the open-source package
- Performed a denylist audit before publication
- Performed an additional reviewer-style double check before making the repository public

## 1.0.0 - 2026-05-24

### Added
- Initial public extraction of the Telegram coordination protocol skill from a working Hermes deployment
