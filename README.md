# dotfiles

My shell and editor configs, managed with a tiny install script

Started as a weekend hack, grew on me.

## Features

- Bash prompt with git branch indicator
- One-command setup: ./install.sh
- Sane vim defaults, no plugins required
- Git aliases I actually use daily

## Getting started

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## How to use

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Project structure

```text
├── .github/
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .bashrc
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .vimrc
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Makefile
└── install.sh
```

## License

MIT licensed, see LICENSE.
