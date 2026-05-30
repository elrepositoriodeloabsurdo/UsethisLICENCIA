# Changelog

All notable changes to LicenseAgent are documented here.

## [0.1.0] — 2025-05-03

### Added
- Initial release
- Single-file browser app (zero install, zero dependencies)
- Three input modes: paste code, upload files, GitHub URL
- Claude Sonnet AI-powered license analysis
- 20+ license templates (MIT, Apache 2.0, GPL, AGPL, LGPL, MPL, BSD, ISC, Unlicense, CC, BSL, SSPL, RAIL, Proprietary)
- Dependency compatibility scoring (green / yellow / red)
- License metrics: permissiveness, IP protection, enterprise adoption, patent coverage, project fit
- Download LICENSE file directly from browser
- Chilean legal context notes (Ley 19.628 / Ley 21.719) for LegalTech projects
- Dark theme with VibeCodingChile aesthetic
- Fully responsive mobile layout

### Architecture
- Powered by Anthropic Claude Sonnet via `/v1/messages`
- No backend, no database, no cookies — fully client-side
- Apache 2.0 licensed

---

[0.1.0]: https://github.com/vibecodingchile/license-agent/releases/tag/v0.1.0
