# Changelog

Entries were first kept by date; the version numbers below were assigned afterwards, in date order.

## 0.5.0

- Add `AGENTS.md` with agent instructions; `CLAUDE.md`, `CODEX.md`, `GEMINI.md` symlink to it

## 0.4.0

- Add pre-flight inventory, interactive type selection, and `--yes` flag
- Replace progress files with `manifest.json` for pull state tracking

## 0.3.0

- Refactor to incremental writes, curl_cffi for Cloudflare bypass, and checkpoint/resume

## 0.2.0

- Add featured image downloading with `--images` flag
- Add REST API probe and route-based type discovery
- Add `--type` flag for pages and custom post type support
- Add category/tag preservation, YAML frontmatter, and `--split` mode
- Self-bootstrapping script: zero-setup single-command experience
- Refactor repo: add Python exporter, restructure for general use

## 0.1.0

- Initial commit with working prototype
