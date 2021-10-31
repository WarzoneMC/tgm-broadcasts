# Broadcasts
Warzone preset Broadcasts

## Updating the broadcasts

- When making a pull request to this repo, make sure you first follow the general format of the rest of the broadcasts (blank line before and after the broadcast).
- Make sure you also include the reasoning for the changes you are making. 

## How to setup

1. Setup a server using the [TGM](https://jenkins.bennydoesstuff.me/job/TGM/) plugin (check out the plugin's [README](https://github.com/Warzone/TGM/blob/master/README.md) for more information).

2. Issue the command ``/bc config url https://raw.githubusercontent.com/WarzoneMC/Broadcasts/master/broadcasts.json`` from either in-game or by using your console.

3. Use the command ``/bc reload`` to reload the broadcast config. This should update your broadcasts from this repo. You can then edit the broadcast queue by using the command ``/bc config queue``
