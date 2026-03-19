# Contributing

Thanks for taking the time to contribute!

## Development setup

Prerequisites: Node.js + npm

```bash
npm ci
```

## Packaging (VSIX)

```bash
npm run package
```

Install the generated `.vsix` in VS Code:

- **Extensions** → `…` → **Install from VSIX…**

## Updating screenshots

This repo uses `ff-devtools.png` for the README preview. If you update colors, please also refresh the screenshot:

1. Open VS Code
2. Select the theme you changed
3. Take a screenshot (recommended: editor + sidebar + a few tokens visible)
4. Replace `ff-devtools.png` and ensure the README still looks good on GitHub

## Theme changes

- Keep `themes/ff-devtools-*.json` valid JSON
- Prefer minimal diffs for color tweaks (one intent per PR)
- If you add new tokens, please test both Dark and Light

## Reporting bugs

Please include:

- VS Code version
- OS
- Which theme (Dark/Light)
- A screenshot and/or `Developer: Inspect Editor Tokens and Scopes` output (when applicable)

