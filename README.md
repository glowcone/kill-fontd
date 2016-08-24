# kill-fontd
Resets fontd, which sometimes takes up 95% of the CPU for no apparent reason on OSX.

## Installation
1. Download [kill-fontd](https://raw.githubusercontent.com/recurza/kill-fontd/master/kill-fontd) (Right click > Save As... > Downloads).

2. Remove the .txt extension.

3. Open Terminal and type/paste this:
```bash
cd ~/Downloads
chmod +x kill-fontd
```

You may want to use [crontab](https://help.ubuntu.com/community/CronHowto#Starting_to_Use_Cron) to run it automatically every so often. Remember to use the root crontab.
