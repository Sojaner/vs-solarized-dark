# Solarized Dark VS Tokens

Solarized Dark VS Tokens is a VS Code theme that keeps the workbench and terminal on Solarized Dark while using the JetBrains Visual Studio Dark palette for syntax highlighting and semantic tokens.

## What it combines

- Workbench colors: VS Code Solarized Dark
- Token colors: JetBrains Rider/IntelliJ Visual Studio Dark scheme
- Semantic tokens: mapped from the same JetBrains scheme for stronger C# and XML coverage

## Included language tuning

- C#: classes, interfaces, enums, structs, methods, extension methods, attributes, preprocessor directives, labels
- Razor: tag names, attributes, embedded transitions, quoted values, control keywords
- XML/HTML: tag names, punctuation, attributes, attribute values, namespace-qualified names

## Use in an Extension Development Host

1. Open this folder in VS Code.
2. Press F5.
3. In the new Extension Development Host window, open the Command Palette.
4. Run `Preferences: Color Theme`.
5. Select `Solarized Dark (VS Tokens)`.

## Package the extension

1. Install `vsce` if needed: `npm install -g @vscode/vsce`
2. From this folder, run: `vsce package`
3. Install the generated `.vsix` with `Extensions: Install from VSIX...`

## Notes

- The extension is licensed under MIT.
- If you want marketplace publishing, also add repository, homepage, and issue tracker metadata that points to your actual project.