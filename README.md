simple service menu for dolphin
clear cached items on arch plasma 5 or 6 
simply right click in dolphin 
click clear cached items and enter your password
the script will do the rest
all commands used are given below 
or you can check the scripts file your self in a text editor application such as kate

How to install:
download the tar.gz and unpack to the follow locations depending on your plasma version


Dolphin -> Preferences -> Services -> Download New Services... ...or 
For kde5 move the downloaded clearcacheditemsarch.desktop file to ~/.local/share/kservices5/ServiceMenus (create the folder if it's missing) 
move the downloaded scripts.sh file to ~/.local/share/kservices5/ServiceMenus (create the folder if it's missing) 
Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable". 
or use $ chmod +x ./clearcacheditemsarch.desktop 
and use $ chmod +x ./scripts.sh

For kde6 move the downloaded clearcacheditemsarch.desktop file 
to ~/.local/share/kio/servicemenus/ (create the folder if it's missing) 
move the downloaded scripts.sh file to ~/.local/share/kio/servicemenus/ (create the folder if it's missing) 
Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable". 
or use $ chmod +x ./clearcacheditemsarch.desktop 
and use $ chmod +x ./scripts.sh

commands used in this menu are 
sudo pacman -Sc
sudo rm -rf /var/cache/ 
sudo rm -rf /tmp 
sudo rm -rf /root/.cache/ 
sudo rm -rf /home/lancaster/.local/share/Trash 
sudo rm -rf /root/.local/share/Trash/

