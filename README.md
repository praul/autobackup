# autobackup
Automated backup to connected usb drives with encryption support (wip)

**It's gonna be like this, doing it after vacation**
```
devlist = [(dev, mountpoint, aftercommand, copytarget, copysources()), (...)]

aftercommand = veracrypt -p "123456" --non-interactive mountpoint/container.vc /media/usb1/
copycommand = rsync...

check dev/...
exists mountpoint/autousb-dev?
exists dev?

-> mount dev to mountpoint
exists mountpoint/autousb-dev`?

->aftercommand

exists copytarget autousb-target?
-> copycommand copysources copytarget
```
