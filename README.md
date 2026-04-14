# vscode-haskell-nsis

[![License](https://img.shields.io/github/license/idleberg/vscode-haskell-nsis?color=blue&style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/github/v/release/idleberg/vscode-haskell-nsis?style=for-the-badge)](https://github.com/idleberg/vscode-haskell-nsis/releases)
[![Build](https://img.shields.io/github/actions/workflow/status/idleberg/vscode-haskell-nsis/default.yml?style=for-the-badge)](https://github.com/idleberg/vscode-haskell-nsis/actions)

Snippets for [Haskell NSIS](https://hackage.haskell.org/package/nsis)

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install haskell-nsis`

### Packaged Extension

Download the package extension from the the [release page](https://github.com/idleberg/vscode-haskell-nsis/releases) and install it from the command-line:

```bash
$ code --install-extension haskell-nsis-*.vsix
```

Alternatively, you can download the packaged extension from the [Open VSX Registry](https://open-vsx.org/) or install it using the [`ovsx`](https://www.npmjs.com/package/ovsx) command-line tool:

```bash
$ ovsx get idleberg.haskell-nsis
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```powershell
# Windows Powershell
cd $Env:USERPROFILES\.vscode\extensions

# Windows Command Prompt
$ cd %USERPROFILE%\.vscode\extensions
```

```bash
# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `haskell-nsis`:

```bash
$ git clone https://github.com/idleberg/vscode-haskell-nsis haskell-nsis
```

## License

This work is license under [The MIT License](LICENSE).
