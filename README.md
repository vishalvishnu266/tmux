
sudo apt update

sudo apt install tmux fish htop copyq git vim  ranger -y

sudo apt install default-jdk maven -y

sudo apt install build-essential nodejs -y

sudo apt install graphviz

ohmyzsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
plugins=(git vi-mode z extract fzf zsh-autosuggestions zsh-syntax-highlighting)




fish

cd ~

git clone https://github.com/oh-my-fish/oh-my-fish

cd oh-my-fish

bin/install --offline

omf install z

omf install extract


git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf

~/.fzf/install



 vim ~/.config/fish/config.fish
 
 alias idea='bash /home/vishal/idea-IC-203.6682.168/bin/idea.sh'
 
 
 
 
 
 
sudo rm /etc/apt/preferences.d/nosnap.pref
sudo apt update
sudo apt install snapd
sudo snap install postman
sudo snap install intellij-idea-community --classic
sudo snap install code --classic


sudo usermod -aG docker $USER

newgrp docker

# TERMINAL THEME
sudo apt-get install dconf-cli uuid-runtime
# clone the repo into "$HOME/src/gogh"
mkdir -p "$HOME/src"
cd "$HOME/src"
git clone https://github.com/Mayccoll/Gogh.git gogh
cd gogh/themes

# necessary on ubuntu
export TERMINAL=gnome-terminal

# install themes
./gruvbox-dark.sh 
./gruvbox.sh  

