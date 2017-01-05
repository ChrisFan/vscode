> This is a fork of [`vscode`](https://github.com/microsoft/vscode)

## development

install dependencies
```bash
./scripts/npm.sh install
```

start compile server
```bash
gulp watch
```

start electron
```bash
./scripts/code.sh
```

debug
```bash
./scripts/code.sh --remote-debugging-port=9222
```

## monaco

setup monaco
```bash
npm run monaco-editor-setup
```

build monaco
```bash
gulp editor-distro
```

## changelogs

- add monaco.languages.registerTokensProvider

## todos

- [ ] use webpack to build monao-editor-core