# config-files
Personal config files

Install iterm2: \n
```brew install --cask iterm2```\n

Install oh-my-zsh: \n
```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

Install powerlevel10k: \n
```git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k```

Install zsh plugins:
```git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions``` \n
```git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting``` \n

Reload: \n
```source ~/.zshrc```\n

Clone this repo to the home directory, and create symlinks to the repo:
```ln -sf ~/config-files/.zshrc ~/.zshrc``` \n
```ln -sf ~/config-files/aerospace.toml ~/.config/aerospace/aerospace.toml```\n


Install the following using brew:
fzf \n fd \n bat \n delta \n tldr \n thefuck \n eza \n delta 

