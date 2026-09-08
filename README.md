# tabnap

MV3 extension playground: page reading-time estimator

Small but I use it weekly.

## Highlights

- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- No remote calls, everything stays local
- Manifest V3, service worker based

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
