# MyDotfiles-Public
-----------------------------------------------------
# Installation
[Homebrew](https://brew.sh/)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
[ZSH](https://formulae.brew.sh/formula/zsh#default)
```
brew install zsh
```
[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)

Oh My Zsh is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl`, `wget` or another similar tool.

| Method    | Command                                                                                           |
| :-------- | :------------------------------------------------------------------------------------------------ |
| **curl**  | `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |
| **wget**  | `sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`   |
| **fetch** | `sh -c "$(fetch -o - https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |

_Note that any previous `.zshrc` will be renamed to `.zshrc.pre-oh-my-zsh`. After installation, you can move the configuration you want to preserve into the new `.zshrc`._

Config OhMyZsh with 
```sh
vi ~/.zshrc
```

