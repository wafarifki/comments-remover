# Changelog

## [1.0.1] - 2026-01-13

### Added
- Support for removing CSS comments inside `<style>` tags in HTML files
- Support for removing JavaScript comments inside `<script>` tags in HTML files

### Improved
- More consistent empty line handling after comment removal
- Better behavior when processing mixed HTML, CSS, and JavaScript content

### Notes
- This update improves comment removal accuracy for embedded CSS and JavaScript in HTML files
- No changes to existing command or usage

---

## [1.0.0] - Initial Release

### Added
- Support for HTML comment removal
- Support for CSS block comment removal
- Safe JavaScript comment removal (block and single-line)
- PHP comment removal (`/* */`, `//`, `#`)
- Structure-preserving formatting
- Single empty-line normalization
- Command palette integration

### Notes
- Designed with safety-first logic
- No external dependencies
- Suitable for production code cleanup
