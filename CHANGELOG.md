# Changelog

## Earlier changes

- Add `AGENTS.md` with agent instructions; `CLAUDE.md`, `CODEX.md`, `GEMINI.md` symlink to it
- Add pre-flight inventory, interactive type selection, and `--yes` flag
- Replace progress files with `manifest.json` for pull state tracking
- Refactor to incremental writes, curl_cffi for Cloudflare bypass, and checkpoint/resume
- Add featured image downloading with `--images` flag
- Add REST API probe and route-based type discovery
- Add `--type` flag for pages and custom post type support
- Add category/tag preservation, YAML frontmatter, and `--split` mode
- Self-bootstrapping script: zero-setup single-command experience
- Refactor repo: add Python exporter, restructure for general use
- Initial commit with working prototype
