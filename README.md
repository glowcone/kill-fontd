# kill-fontd
Resets fontd, which sometimes takes up 95% of the CPU for no apparent reason on OSX.

## Installation
Download [kill-fontd](https://raw.githubusercontent.com/recurza/kill-fontd/master/kill-fontd).

Open Terminal and type/paste this:
```bash
cd ~/Downloads/kill-fontd
sudo chmod +x kill-fontd
```

You may want to use [crontab](https://help.ubuntu.com/community/CronHowto#Starting_to_Use_Cron) to run it automatically every so often. Remember to use the root crontab.
