# Contributing to LicenseAgent

First off — thank you. Every contribution, from fixing a typo to adding a new license template, helps make LicenseAgent better for developers everywhere.

## Ways to contribute

### 🐛 Bug reports
Open an issue using the [Bug Report template](.github/ISSUE_TEMPLATE/bug_report.md). Include:
- What you pasted/uploaded
- What license was recommended
- What you expected instead
- Browser + OS

### 💡 Feature requests
Open an issue using the [Feature Request template](.github/ISSUE_TEMPLATE/feature_request.md).

High-priority areas:
- Additional package manager support (Hex, NuGet, CocoaPods, pubspec.yaml)
- More license templates (EUPL-1.2, CERN-OHL, custom proprietary)
- Translations of the UI (currently ES/EN)
- CI/CD integrations (GitHub Actions, GitLab CI, Bitbucket Pipelines)

### 📝 License templates
Add or improve license templates in `/examples/`. Each example folder should contain:
```
examples/your-scenario/
├── input.txt          # Sample project input (package.json, etc.)
├── expected.json      # Expected agent output (for testing)
└── README.md          # Scenario description
```

### 🔧 Code contributions

1. Fork the repo
2. Create a branch: `git checkout -b feat/your-feature`
3. Make your changes to `index.html` (single-file architecture — keep it that way)
4. Test locally by opening `index.html` in a browser with your Anthropic API key
5. Open a PR against `main`

## Code style

- Single-file HTML — no build step, no bundler, no npm install
- CSS variables for all colors (see `:root` block)
- `DM Mono` + `Syne` typography — don't introduce new fonts
- No external dependencies beyond Google Fonts
- Comments in English (code) or Spanish (inline notes) — both welcome

## Commit convention

```
feat: add CocoaPods dependency detection
fix: handle empty package.json gracefully  
docs: improve RAIL license description
refactor: extract license scoring to separate function
```

## License

By contributing, you agree your contributions are licensed under Apache 2.0.

---

Built with ❤️ in Santiago, Chile 🇨🇱
