# dmenu-scripts
A set of scripts to do various tasks using Suckless' dmenu. All these scripts are tied to keyboard shortcuts using xbindkeys or sxhkd.

### Scripts
  * netcon / netdiscon: connect / disconnect networks (depends on NetworkManager)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/netcon_preview.png?raw=true)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/netdiscon_preview.png?raw=true)

  * usbmount / usbunmount / usbpoweroff: mount / unmount / poweroff drives (depends on udisks2, also depends on a policykit if you want to mount internal drives)
![](https://raw.githubusercontent.com/I-LeCorbeau/dmenu-scripts/master/.previews/usbmount_preview.png?token=AOH2DYBZX75TYATZ3HVC5B26EX5HU)
![](https://raw.githubusercontent.com/I-LeCorbeau/dmenu-scripts/master/.previews/usbunmount_preview.png?token=AOH2DYCNTQDXCR5PYGOEVKC6EX5QA)
![](https://raw.githubusercontent.com/I-LeCorbeau/dmenu-scripts/master/.previews/usbpoweroff_preview.png?token=AOH2DYHDXXW4K7QAWX7PNGC6EX5SO)

  * poweroffreboot1: poweroff or reboot computer. (systemd version, uses systemctl and doesn't require sudo)
![](https://raw.githubusercontent.com/I-LeCorbeau/dmenu-scripts/master/.previews/poweroffreboot1_preview.png?token=AOH2DYGHQCKEAB7B2YYD76K6EX52E)

  * monitor: switch monitor setup. (relies on xrandr)
![](https://github.com/I-LeCorbeau/dmenu-scripts/blob/master/.previews/monitor_preview.png?raw=true)

#### TODO
  * poweroffreboot2 (for Void Linux install): poweroff or reboot computer, but does not rely on systemd. Will require that the user has permission to poweroff and reboot without password (uses sudo poweroff / sudo reboot)
 * Check for and remove "bashisms" (if there are any) to make the scripts more portable

More will come.
