# shell-scripts-configs
A repository for my commonly used shell-scripts and configurations

This repository contains shell scripts, configurations, or other convenient stuff that automates things that I usually perform after clean install of operating system or application

## Contents
Coming soon

### Importing and Exporting `ini` files
To save all (dump) dconf settings into ini file:
```sh
dconf dump / > dconf-settings.ini
````
To restore them:
```sh
dconf load / < dconf-settings.ini
```
