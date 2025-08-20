# Calcite Intellisense for VS Code

Esta extensión proporciona autocompletado y sugerencias para los componentes del sistema Calcite Design System en HTML.

## Instrucciones para instalar localmente

1. Abre Visual Studio Code.
2. Ejecuta `View -> Command Palette -> Extensions: Install from VSIX...`.
3. Selecciona el archivo `.vsix` generado o ejecuta desde terminal:

```bash
npm install -g vsce
vsce package
code --install-extension calcite-intellisense-1.0.0.vsix
```

## Contenido

- **Snippets:** disponibles para componentes Calcite (`.vscode/calcite.code-snippets`)
- **Soporte IntelliSense:** atributos, propiedades y documentación (`custom-data/vscode-data.json`)
