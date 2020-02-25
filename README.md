# .zshrc
my zsh setting

## Installation
```bash
// install zsh and oh-my-zsh
sudo apt install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"


// download powerlevel9k
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k


// download autojump
git clone https://github.com/wting/autojump wting/autojump
cd wting/autojump
./install.py


// download zsh-autosuggestion
git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions


//download zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

// download git open
git clone https://github.com/paulirish/git-open.git $ZSH_CUSTOM/plugins/git-open

// Finally remember download nerdfont-complete by yourself, and rename the username in zshrc's zsh export
```
