# dmenu-scripts
A set of scripts to do various tasks using Suckless' dmenu. All these scripts are tied to keyboard shortcuts using xbindkeys or sxhkd.

### Scripts
  * chwall-dmenu: change wallpaper with dmenu. Details found [here](https://lecorbeausvault.wordpress.com/2020/07/08/chwall-chwall-dmenu-change-wallpaper-via-command-line-or-dmenu/).

  * netcon / netdiscon: connect / disconnect networks (depends on NetworkManager)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/netcon_preview.png?raw=true)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/netdiscon_preview.png?raw=true)

  * usbmount / usbunmount / usbpoweroff: mount / unmount / poweroff drives (depends on udisks2, also depends on a policykit if you want to mount internal drives)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/usbmount_preview.png?raw=true)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/usbunmount_preview.png?raw=true)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/usbpoweroff_preview.png?raw=true)

  * poweroffreboot: poweroff or reboot computer. (This one uses the systemctl poweroff/reboot commands, but for non-systemd distros, you can install elogind and replace "systemctl" with "loginctl")
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/poweroffreboot1_preview.png?raw=true)

  * monitor: switch monitor setup. (relies on xrandr)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/monitor_preview.png?raw=true)

#### TODO
 * Check for and remove "bashisms" (if there are any) to make the scripts more portable

More will come.
