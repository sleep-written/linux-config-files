# Linux config files

This repository contains some configuration files sed by me in my developer environment. Fell free to use these files to yow own environment.

## [vim](https://www.vim.org/)

- Install __vim:__
    ```bash
    sudo apt install vim
    ```
- Install [plug:](https://github.com/junegunn/vim-plug)
    ```bash
    curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
        https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    ```

- Copy [this file](./.vimrc) to your __home__ directory.
- Open vim, and then, execute this command:
    ```
    :PlugInstall
    ```

<br />

## [zsh](https://zsh.sourceforge.io/)

- Install __zsh:__
    ```bash
    sudo apt install zsh
    ```
- Install [oh my zsh](https://ohmyz.sh/):
    ```bash
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```
- Copy [this file](./.zshrc) to your __home__ directory.
- Install [powerlevel10k:](https://github.com/romkatv/powerlevel10k)
    ```bash
    git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    ```
- Copy [this file](./.p10k.zsh) to your __home__ directory.