# cli

# stress cli test, my notebook max response  
stress -i 8 -c 4 -m 35 -t 20


# Telegram ubuntu   

sudo add-apt-repository ppa:atareao/telegram  
sudo apt-get update  
sudo apt-get install telegram  



# i3-wm Adicionar autostart no i3-wm
exec terminator
exec-always nm-applet

# Firefox Developer  
sudo add-apt-repository ppa:ubuntu-mozilla-daily/firefox-aurora  
sudo apt-get update  
sudo apt-get install firefox  

# xz uncompress files.
unxz my_archive.tar.xz

# xrandr - video settings

xrandr --output HDMI-1

xrandr —output HDMI-2 —mode 1600x900 —left-of HDMI-1  
phpcs -n —standard=../ruleset.xml —report=summary application/modules/ 

# phpcbf

phpcbf —standard=PSR2 application/modules/default/controllers 

# nextcloud 
sudo add-apt-repository ppa:nextcloud-devs/client  


# oh my zsh  
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"  

# docker 
sudo gpasswd -a $USER docker  
docker build -t [name_foo] .   
docker rmi [image_name]  
docker exec -it [foo] bash  
docker inspect [foo]   

# git
git add .
git commit -S -m "texto"
git push

git config --global user.signingkey XXXXXXXXX


# GPG import secret key
gpg --import zzz-secret-gpg.key



# zsh-syntax-highlighting  
 git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting  
  plugins=( [plugins...] zsh-syntax-highlighting)  
   source ~/.zshrc
   
   # Javascript
npm install -g eslint

# ssh + ssh keys    
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"  

ssh-add  

ssh-add ~/.ssh/ec2.pem > /dev/null 2>&1

# CPU temperature
sudo apt-get install lm-sensors 
sudo sensors-detect
sensors

