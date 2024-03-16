# My Neovim Config file

## Introduction

My personal neovim config. I have kept it as small as i can, it's a single file.

## Installation

### Install Neovim

This targets the lated neovim version
['stable'](https://github.com/neovim/neovim/releases/tag/stable) and latest
['nightly'](https://github.com/neovim/neovim/releases/tag/nightly) of Neovim.
If you are experiencing issues, please make sure you have the latest versions.

### Install External Dependencies

> **NOTE**
> [Backup](#FAQ) your previous configuration (if any exists)

External Requirements:
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
- A [Nerd Font](https://www.nerdfonts.com/)
- If want to write Typescript, you need `npm`
- If want to write Golang, you will need `go`
- etc.

Neovim's configurations are located under the following paths, depending on your OS:

| OS | PATH |
| :- | :--- |
| Linux, MacOS | `$XDG_CONFIG_HOME/nvim`, `~/.config/nvim` |
| Windows (cmd)| `%userprofile%\AppData\Local\nvim\` |
| Windows (powershell)| `$env:USERPROFILE\AppData\Local\nvim\` |

### Install The Config

Clone the repo:

<details><summary> Linux and Mac </summary>

```sh
git clone https://github.com/codemonkey76/neovim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

</details>

<details><summary> Windows </summary>

If you're using `cmd.exe`:

```
git clone https://github.com/codemonkey76/neovim-config.git %userprofile%\AppData\Local\nvim\
```

If you're using `powershell.exe`

```
git clone https://github.com/codemonkey76/neovim-config.git $env:USERPROFILE\AppData\Local\nvim\
```

</details>

### Post Installation

Start Neovim

```sh
nvim
```

That's it! Lazy will install all the plugins you have. Use `:Lazy` to view
current plugin status.

### Recommended Steps

[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo
(so that you have your own copy that you can modify) and then install. You
can install it on your machine using the methods above.

> **NOTE**
> Your fork's url will be something like this: `https://github.com/<your_github_username>/neovim-confg.git`

