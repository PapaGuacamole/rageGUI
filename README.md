# rageGUI
* A user-configurable GUI element is built which automatically updates battlerage abilities, dynamically displaying when your character has sufficient rage stored to use the ability, with an animated timer showing the cooldown. An event is raised when the ability is used, which can be scripted using an event handler (an example is included) for relaying to party, etc.
* Can be toggled on and off
* User configuration options include GUI size, position, colours
* Rage abilities for all dragon colours and adventurer classes are included.
* Clicking the GUI element corresponding to the rage ability will attempt to use the ability. *There are no checks included for amount of rage, rage balance, etc, it is as if the commands have been manually entered.*
* For extra convenience, hotkeys CTRL+1 to 6 also send the commands to the MUD.
* For Iron Realm's [Achaea](http://www.achaea.com)
* Requires [Mudlet v2.1 or higher](http://www.mudlet.org)
* Full functionality is not available without [Demonnic's Anitimers (v2 or above)](https://github.com/demonnic/animatedtimers)
