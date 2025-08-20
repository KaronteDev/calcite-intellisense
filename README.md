# Calcite Intellisense for VS Code

This extension provides autocomplete and suggestions for Calcite Design System components in HTML.

## Instructions for local installation

1.  Open Visual Studio Code.
2.  Run `View -> Command Palette -> Extensions: Install from VSIX...`.
3.  Select the generated `.vsix` file or run from terminal:

```
npm install -g vsce
vsce package
code --install-extension calcite-intellisense-1.0.0.vsix
```

## Contents

*   **Snippets:** available for Calcite components (`.vscode/calcite.code-snippets`)
*   **IntelliSense support:** attributes, properties, and documentation (`custom-data/vscode-data.json`)

---

## Run from the VS Code environment.

### Start debugging

1.  Go to the ‘Run and Debug’ tab (Ctrl+Shift+D).
2.  Choose the configuration called ‘Extension: Run’.
3.  Press ▶ ‘Start Debugging’.

This will open a **new VS Code window with your extension temporarily loaded** (development host mode), where you can test IntelliSense and snippets in .html files.

Translated with DeepL.com (free version)