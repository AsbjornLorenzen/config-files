```
# Install aerospace:
brew install --cask nikitabobko/tap/aerospace

# Install iterm2:
brew install --cask iterm2

# Install oh-my-zsh:
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install powerlevel10k:
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

# Install zsh plugins:
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# Reload zsh configuration:
source ~/.zshrc

# Clone this repo to the home directory, and create symlinks to the repo:
ln -sf ~/config-files/.zshrc ~/.zshrc
ln -sf ~/config-files/aerospace.toml ~/.config/aerospace/aerospace.toml
mkdir ~/.config/aerospace
ln -sf ~/config-files/nvim ~/.config/nvim

# Install the following using brew:
brew install fzf fd bat delta tldr thefuck eza delta
```

# Set key repeat rate

defaults write -g InitialKeyRepeat -int 10
defaults write -g KeyRepeat -int 3
