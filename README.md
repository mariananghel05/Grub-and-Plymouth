# Grub-and-Plymouth
1920x1080 or Display resolution image.
edit GRUB_BACKGROUND="Your/Image/Path" in /etc/default/grub
use grub-mkconfig -o /boot/grub/grub.cfg
for loadscreen 
install plymouth from AUR
edit 
GRUB_CMDLINE_LINUX_DEFAULT="quiet" and add splash in /etc/default/grub
and 
HOOKS=(base udev ..) add plymouth after base and udev
........................................................
for adding themes to plymouth phat is /usr/share/plymouth/themes
use plymouth-set-default-theme -l for show all themes
and plymouth-set-default-theme -R themename for set a theme
