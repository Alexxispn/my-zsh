# My Zsh

### Install ZSH

1. Update and Install

    ```bash
    sudo apt update && sudo apt install zsh
    ```

2. Make zsh our main shell

    ```bash
    chsh winvi -s /bin/zsh
    ```

3. Install Curl

    ```bash
    sudo apt install git curl -y 
    ```

4. Install OhMyZsh

    ```bash
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```


### Configuration ZSH

1. My zsh repo:

   [GitHub - alexxispn/my-zsh: this is my config for zsh](https://github.com/alexxispn/my-zsh)

2. Download & Set Powerlevel10k Theme:

    ```bash
    git clone [https://github.com/romkatv/powerlevel10k.git](https://github.com/romkatv/powerlevel10k.git)
    $ZSH_CUSTOM/themes/powerlevel10k
    ZSH_THEME="powerlevel10k/powerlevel10k"
    ```

3. Download MesloLGS NF Font (You need to install and Set on your Terminal):

   [dotfiles-public/MesloLGS NF Regular.ttf at master · romkatv/dotfiles-public](https://github.com/romkatv/dotfiles-public/blob/master/.local/share/fonts/NerdFonts/MesloLGS%20NF%20Regular.ttf)


### PLUGINS

1. Pluggin Autosuggestion:

    ```bash
    git clone https://github.com/zsh-users/zsh-autosuggestions
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

2. Pluggin Completions:

    ```bash
    git clone https://github.com/zsh-users/zsh-completions
    ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions
    ```

3. Pluggin Syntax-hihlighting:

    ```bash
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```

4. Pluggin Z:

    ```bash
    git clone [https://github.com/agkozak/zsh-z](https://github.com/agkozak/zsh-z)
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z
    ```

5. Autocomplete for Docker

   [](https://www.deploycontainers.com/2021/07/19/enable-docker-cli-autocomplete-on-linux/)

<br>

If you want yo know more about my WSL or my ZSH, I highly recommend you to visit Manz's Blog, he has a lot of good content about WSL and ZSH.

[Manz blog bout CLI & ZSH](https://terminaldelinux.com/terminal/)
