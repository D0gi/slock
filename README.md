# slock
slock(i3lock) with blurred screenshot and logo
![screenlockscreenshot](https://github.com/D0gi/slock/blob/master/screenshotblur.png?raw=true)

## Dependencies:
 i3lock, scrot, imagemagick, xautolock
##Use
- add the script slock to `/usr/local/bin/`
- run `chmod +x slock`
- for autolock add `xautolock -time 10 -locker slock` to a startscript (e.g. `.bashrc`)
