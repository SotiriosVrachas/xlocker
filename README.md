xlocker
=======

A bash script that loop through every display looking for a fullscreen window.
If a window is in fullscreen state xtrlock is executed, else slock is executed.

Essentially if there is a video playing in fullscreen you can watch it while your computer is protected from unauthorized use.
This script is associated with:
* https://github.com/sotiri/xtrlock which is a modified version of xtrlocker with transparent cursor
* https://github.com/sotiri/slock which is a modified version of slock with black background color when active

and it is used with xautolock
```shell
xautolock -time 1 -locker xlocker
```
and these alias for slock and xtrlock in ~/.profile for power management
```shell
alias slock='xset dpms force off; slock'
alias xtrlock='xfce4-power-manager --quit; xset s noblank; xset s off; xtrlock; xfce4-power-manager'
```
