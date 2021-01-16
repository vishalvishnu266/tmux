
sudo apt update

sudo apt install tmux fish htop copyq git vim  ranger -y

sudo apt install default-jdk maven -y

sudo apt install build-essential nodejs -y

sudo apt install graphviz


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



