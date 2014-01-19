xlocker
=======

A bash script that loop through every display looking for a fullscreen window. If a window is in fullscreen state xtrlock is executed, else slock is executed.

Essentially if there is a video playing in full screen (or any window in full screen) you can watch it while your computer is protected from unauthorized use.

#Installation instructions
Download and copy xlocker into PATH
```shell
git clone https://github.com/SotiriosVrachas/xlocker.git
sudo cp xlocker/xlocker /usr/local/bin/
```
install `xautolock` 
```shell
sudo apt-get install xautolocker
```
launch xautolock at your session start. (varies depending on the desktop environment)
```shell
xautolock -time 1 -locker xlocker -secure
```
change "1" to how many minutes you want xautolock to timeout in idle before launching xlocker 

## Black outs and energy saving
alias for slock and xtrlock in ~/.profile for power management
```shell
alias slock='xset dpms force off; slock'
alias xtrlock='xset -dpms; xset s off; xtrlock; xset +dpms; xset s on'
```
# Where to get help
You can create a new (issue)[https://github.com/SotiriosVrachas/xlocker/issues]

# Contribution guidelines
Feel free to contribute in any way you want. I yould like to know if you hahe any problem, or not.

# Inspiration, Alternatives
https://github.com/iye/lightsOn
