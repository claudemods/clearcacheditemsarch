Description:
clear cached items on arch plasma 5 or 6
simple script to clear cached items simply right click in dolphin and enter your password

How to install:

Dolphin -> Preferences -> Services -> Download New Services... ...or
For kde5
move the downloaded clearcacheditems.desktop file to ~/.local/share/kservices5/ServiceMenus (create the folder if it's missing)
move the downloaded scripts.sh file to ~/.local/share/kservices5/ServiceMenus (create the folder if it's missing) Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable". or use $ chmod +x ./clearcacheditems.desktop or use $ chmod +x ./scripts.sh

For kde6
move the downloaded clearcacheditems.desktop file to ~/.local/share/kio/servicemenus/ (create the folder if it's missing)
move the downloaded scripts.sh file to ~/.local/share/kio/servicemenus/ (create the folder if it's missing) Also use right click on the file > Properties > Permissions > And mark the checkbox next to the text "Is executable". or use $ chmod +x ./clearcacheditems.desktop or use $ chmod +x ./scripts.sh

commands used in this menu are
sudo pacman -Scc
sudo rm -rf /var/cache/
sudo rm -rf /tmp
sudo rm -rf /root/.cache/
sudo rm -rf /home/lancaster/.local/share/Trash
sudo rm -rf /root/.local/share/Trash/
