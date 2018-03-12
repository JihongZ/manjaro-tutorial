# Use Timeshift to backup system

## Command line Options

```bash
timeshift --restore    #interactive

timeshift --restore --snapshot "2015-01-21_19-28-43" --backup-device /dev/sda2 --target-device /dev/sda1 --skip-grub

timeshift --delete    #interactive

timeshift --delete --snapshot "2015-01-21_19-28-43"

timeshift --delete-all    #completely remove all snapshots
```

![img](http://4.bp.blogspot.com/-1Zs8rotF0lY/VL_j4KhR4kI/AAAAAAAABrM/mvMvSbYaQYs/s400/options.png)

