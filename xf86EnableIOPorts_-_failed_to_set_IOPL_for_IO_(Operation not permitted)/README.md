# xf86EnableIOPorts_-_failed_to_set_IOPL_for_IO_(Operation not permitted)
## Background
I was fed up with the beep from the pcspeaker in Manjaro linux. To disable it I
had to type in `xset -b` on every login. I tried adding `xset -b` to ~/.xinitrc
then to ~/.bash_profile but nothing seemed to work.
But then I stumbled upon an
[article](https://wiki.archlinux.org/index.php/PC_speaker#Globally) on archwiki.
In that page it is said that to disable it just unload the kernal module pcspkr
by doing `# rmmod pcspkr`. So I tried it and rebooted.
Not only that this didn't work, I also got the error displayed in
[screen.txt](https://github.com/NikhilMTomy/manjaro-errors/blob/master/xf86EnableIOPorts_-_failed_to_set_IOPL_for_IO_(Operation%20not%20permitted)/screen.txt).
## The error
See
[screen.txt](https://github.com/NikhilMTomy/manjaro-errors/blob/master/xf86EnableIOPorts_-_failed_to_set_IOPL_for_IO_(Operation%20not%20permitted)/screen.txt)
## Status
Not solved  
Asked at
[Reddit](https://www.reddit.com/r/ManjaroLinux/comments/64yhaz/xorg_error_xf86enableioports_failed_to_set_iopl/)
