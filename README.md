# dmenu-scripts
A set of scripts to do various tasks using Suckless' dmenu. All these scripts are tied to keyboard shortcuts using xbindkeys or sxhkd.

### Scripts
  * netcon / netdiscon: connect / disconnect networks (depends on NetworkManager)
  * usbmount / usbunmount / usbpoweroff: mount / unmount / poweroff drives (depends on udisks2, also depends on a policykit if you want to mount internal drives)
  * poweroffreboot1: poweroff or reboot computer. (systemd version, uses systemctl and doesn't require sudo)
  * poweroffreboot2: poweroff or reboot computer, but does not rely on systemd. Will require that the user has permission to poweroff and reboot without password (uses sudo poweroff / sudo reboot)

More will come.
