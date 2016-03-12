##Installing zsh and oh my zsh

sudo apt-get install -y zsh

chsh -s $(which zsh)

sudo apt-get install -y wget

sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

cp custom.zsh-theme ~/.oh-my-zsh/themes/custom.zsh-theme

vim ~/.zshrc

> Updating theme to the custom theme

source ~/.zshrc

- Reload session
