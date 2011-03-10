*Jukkasjärvi* is a set of packages that installs a curated set of software and configuration files to quickly set up a newly-jailbroken iOS device the way I like it. (All that's left to do is change the root and mobile passwords!)

## Contents
### Stage 1

* adv-cmds
* apt7
* class-dump
* curl
* CyDelete
* Erica's Utilities
* MultiIconMover
* No Folder Badges
* nvi
* openssh
* PrivaCy
* Single-Use Clipboard
* SwitcherMod
* uikittools
* wget
* unrar
* unzip
* [moyashi's repository][1]
* [cycript development build repository][2]
* Saner bash prompt for root/mobile
* [z][3]

[1]: http://hitoriblog.com
[2]: http://www.cycript.org
[3]: https://github.com/rupa/z

### Stage 2

* cycript (latest dev version)
* [DefaultFlashOff][4]
* [StatusBarCustomClock 4][5]
* [TimeServerClient][6]
* Sane default settings for the latter two

[4]: http://hitoriblog.com/?p=2182
[5]: http://hitoriblog.com/?p=2175
[6]: http://hitoriblog.com/?p=985

## How to Use

* Jailbreak your device.
* Configure Wi-Fi so Cydia can fetch packages.
* Run all upgrades proposed by Cydia when first launched.
* Add *http://r-ch.net/jukkasjarvi/* as a source in Cydia. (Manage > Sources > Edit > Add)
* Install the *Jukkasjärvi (Stage 1)* package. This should prompt you to reboot on completion.
* Reboot.
* Install the *Jukkasjärvi (Stage 2)* package. This should prompt you to restart SpringBoard.
* Restart SpringBoard.
* Log into your phone via SSH and change the default password (alpine) to something less default.
* Enjoy.
