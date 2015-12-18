rawzica - Chores reminders for workplaces
=========================================

So you have plants at your workplace. Perhaps you hold common meals on
fridays and there's dishes to be cleaned, remains to be stuffed with.
Maybe you lack a cleaning lady, and one of you has to do all the work.
Every time.

Perhaps you decide to take turns in waterning the plants, cleaning the shit up,
and taking care of similar chores. Perhaps you shift duties every other week,
keeping the chiefs in an online collaborative spreadsheet.

Rawzica can parse that (CSV) spreadsheet and send configurable daily
email reminders. 


Installing
----------
To build/install on a Debian-based GNU/Linux distro:

```bash
# Build the deb package
dpkg-buildpackage -us -uc -b
# Install the package
dpkg -i ../rawzica_*.deb
# Install its dependencies
apt-get install -f
```

Usage
-----
Configure rawzica in /etc/rawzica.conf. That's it.