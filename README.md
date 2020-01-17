# dmenu-scripts
A set of scripts to do various tasks using Suckless' dmenu. All these scripts are tied to keyboard shortcuts using xbindkeys or sxhkd.

### Scripts
  * netcon / netdiscon: connect / disconnect networks (depends on NetworkManager)
  * usbmount / usbunmount / usbpoweroff: mount / unmount / poweroff drives (depends on udisks2, also depends on a policykit if you want to mount internal drives)
  * poweroffreboot1: poweroff or reboot computer. (systemd version, uses systemctl and doesn't require sudo)
  * monitor: switch monitor setup. (relies on xrandr)

#### TODO
  * poweroffreboot2 (for Void Linux install): poweroff or reboot computer, but does not rely on systemd. Will require that the user has permission to poweroff and reboot without password (uses sudo poweroff / sudo reboot)
 * Remove "bashisms" to make the scripts more portable

More will come.
