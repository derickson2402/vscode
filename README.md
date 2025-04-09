# VS Code config profiles

Collection of vscode settings I use for various languages. You can add them as a git submodule. It's like installing a code package, but git is your package manager. You can pull upstream updates whenever and however you want, or fork completely.

## Installation

All you need to do is add this repo as a git submodule, targeting the branch for whatever language or toolchain you want.
For example, to do golang development:

```bash
git submodule add --branch lang/golang https://github.com/derickson2402/vscode .vscode
```
