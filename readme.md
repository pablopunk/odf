# Open Diff Files

<p align="center">
  Open all the changed files in the current git repo
</p>
<p align="center">
  <a href="https://www.npmjs.com/package/odf"><img src="https://img.shields.io/npm/dt/odf.svg" /></a>
</p>

## Install

### Globally with npm

```bash
npm install -g odf
```

### Execute directly with npx

```bash
npx odf nvim
```

### Install with homebrew

```bash
brew install pablopunk/brew/odf
```

## Usage

Use `odf [--pr] <editor>` to open all the modified files with the editor of your choice:

```shell
odf           # print all the modified files
odf --pr      # print all the modified files using origin/main as a base (i.e. all files you'd see on a PR)
odf atom      # open all the modified files with atom editor
odf vim       # open in vim (as buffers)
odf vim -p    # open in vim (as tabs)
odf nvim      # open in neovim
odf --pr nvim # open in neovim using origin/main as a base
```
## License

[__MIT license__](license)

## Author


| ![me](https://www.gravatar.com/avatar/fa50aeff0ddd6e63273a068b04353d9d?s=100) |
| ----------------------------------------------------------------------------- |
| © 2017 [Pablo Varela](http://pablo.life)                                      |
