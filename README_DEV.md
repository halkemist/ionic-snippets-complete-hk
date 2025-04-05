## Test local

#### Requirements

- VSCode

#### VSCE package installation (global)

```bash
npm install -g @vscode/vsce
```

#### Generate the .vsix extension file

```bash
vsce package
```

#### Installe the extension

```bash
code --install-extension extension-file-name.vsix
```

NB: You need to uninstall the current extension to test a new version