# User Configuration

This folder is for your custom settings.

Create a file matching the settings file you want to change and add just the settings you want to edit here.

For example:

```ini
# conf/user/combo.ini
[Mercenary]
Chi-Ji=1,1,3
Baron Geddon=2
Ragnaros=2
```

OR

you can copy the .sample in this directory :
* settings.sample.ini -> settings.ini (for your bot settings)
* combo.sample.ini -> combo.ini (to manage your Mercenary abilities during a battle)

This will override any existing values for those specific mercenaries in `conf/system/combo.ini` while keeping all the other values the same.

(you can copy combo.sample.ini into combo.ini to modify it)
