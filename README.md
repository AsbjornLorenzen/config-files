# config-files
Personal config files

Install iterm2: <br/>
```
brew install --cask iterm2
```

Install oh-my-zsh: <br/>
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Install powerlevel10k: <br/>
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

Install zsh plugins:
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```


Reload:

```
source ~/.zshrc
```

Clone this repo to the home directory, and create symlinks to the repo:

```
ln -sf ~/config-files/.zshrc ~/.zshrc
ln -sf ~/config-files/aerospace.toml ~/.config/aerospace/aerospace.toml
```


Install the following using brew:
fzf <br/> fd    <br/> bat    <br/> delta    <br/> tldr    <br/> thefuck    <br/> eza    <br/> delta 

