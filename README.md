# Chapter 0

## Knowledges

- Structured & Imperative programming
- HTTP, SQL, XML, JSON
- Mac user

## Requeriments

```sh
# Create an account on GitHub
https://github.com/

# Git config
git config --global core.editor "nano"
git config --global user.name "<name>"
git config --global user.email "<email>"

# Install Brew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# Install Brew recipes
brew tap homebrew/cask-versions
brew tap homebrew/services
brew tap homebrew/cask-fonts

# Install Mac App Store CLI
brew install mas

# Install Apps
brew cask install docker-toolbox
brew cask install github
brew cask install iterm2
brew cask install phpstorm
brew cask install postman
brew cask install visual-studio-code

# Install Tools
brew install htop
brew install tree
brew install watch
brew install wget
brew install zsh
brew install zsh-syntax-highlighting
brew install zsh-autosuggestions

# Install Apps
mas install 595191960 # CopyClip
mas install 1081413713 # GIF Brewery 3

# Apps to install manually
https://www.spectacleapp.com # Spectacle

# Download docker images
docker pull ubuntu
docker pull debian
docker pull php
docker pull php:7.1-cli
docker pull php:7.2-cli
docker pull php:7.3-cli
docker pull node
docker pull node:alpine
docker pull mysql
docker pull postgres
docker pull nginx
docker pull rabbitmq

# Create Private & Public SSH keys
mkdir -p ~/.ssh
chmod 700 ~/.ssh
cd ~/.ssh
ssh-keygen

# Create Developer directory
cd ~
mkdir -p Developer

# Set ZSH as default shell
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
