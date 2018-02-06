Change Log
========

_If we jump numbers at all, it's probably because it just fixed something minor we didn't make a note of, or maybe we just don't like that number._

## 1.4.0 (2018-02-06)

### Changes

* The IDs that were used for some Ultimate Awakening weapons have been corrected. Saved short links have been updated accordingly, but any saved long links will break if they used those items.
* If you have any problems using your old short links, let us know on GitHub or Discord and we'll see what we can do.

## 1.3.0 (2017-12-12)

### New stuffs

* Mystic has arrived! She is now enabled.... minus awakening of course.

* #### Added Asula accessory set
*  - Asula's Crimson Eye Necklace
*  - Asula's Crimson Eye Belt
*  - Asula's Crimson Eye Ring
*  - Asula's Crimson Eye Earring

* #### Added Kamasylvia part 1 items
*  - Spirit Stones (Disposable Alchemy Stones) - Green/Blue versions of Life, Guardian and Destruction.
*  - Valtarra Eclipsed Belt
*  - Narc Ear Accessory
*  - Anbelif Earring
*  - Griffon's Helmet (new boss helmet)
*  - Black Leopard Armor craftable outfit

* #### Oct 18th patch items update
*  - Loure Armor Set
*  - Root treant and treant spirt accessory set
*  - Chimera's pupil gem (earring)
*  - Delphad Castillion's Carnage main weapons for all classes
*  - Kaia necklace
*  - Added set effect for valencia quest rings

- Added Capotia Ring and Earring (level 61 and 62 rewards)
- Added Freed and Roaring Magical secondary weapons
- Added Ultimate Green Awakening Weapons for all classes (except mystic)

* #### Added Kamasylvia part 2 items
*  - Lemoria Armor set
*  - Added Lemoria set to all Liverto weapons
*  - Tungrad Belt
*  - Grana Oath Earring
*  - Grana Guardian Necklace
*  - Grana Harmony Ring
*  - Forest Ronaros Ring
*  - Urugon's Shoes (new boss shoes)

* #### Other item additions
* Added Capotia Belt (level 63 reward)
* Added Black Abyssal main weapons for all classes
* Added Mediah Merchants Union Helm
* Added Derek's Light Leather Shoes
* Added Beia's Black Magic Gloves

#### Hidden stats revealed!
* Too much to list, if it had a hidden stat it is now shown with the exception of set bonuses like grunil, but that only applies to ingame not here.
* Added once hidden stats to all items where applicable.
* Added Extra Damage against humans to all dandelion awakening weapons except mystic, which will be added when her awakening comes.

### Bugs
* Fixed Ridell Earring Base DP
* Fixed green/blue taritas and zereth helmet enhancement stats.

### Changes
- Minor database cleanup
- Changed Jarrette's set from 4 / 6 to 3 / 5
- Renamed bow.json (maehwa/musa secondary weapon) to shortbow.json
- Renamed kunoichi.json (kunoichi secondary weapon) to kunai.json
- Added those changes to bdo_database.php
- Added Grana set for the kama 2 questline items (earring, ring, necklace)
- Added Skill Exp stat type
- Added hev (Hidden Evasion) stat type
- Added hdr (Hidden Damage Reduction) stat type

* #### Removed the following as they don't exist ingame:
*  - 11918 - Forest Emerald Earring
*  - 11919 - Placid Forest Emerald Earring
*  - 11920 - Emerald Earring of Tranquility
*  - 12108 - Ocean Sapphire Ring
*  - 12109 - Translucent Ocean Sapphire Ring
*  - 12110 - Sapphire Ring of Storms
*  - 12118  Forest Emerald Ring
*  - 12119  Placid Forest Emerald Ring
*  - 12120  Emerald Ring of Tranquility

## 1.2.1 (2017-08-16)

### New stuffs

* Added Striker Awakening weapons
* Added base for Mystic class along with her banner and logo
* Added new favicon because why not!
* Added Mystic weapons and images 
* Added Dim Magic Crystals

### Bugs

* Fixed some/all striker/mystic offhand stats. hopefully got 'em all...
* Re-add Ancient Magic Crystal - Carmae... which somehow went missing.
* Fixed Fugitive Khalk's Earring enhancement values
* Fixed enhancement stats on Rhutum Elite Belt
* Fixed Magic Crystal of Infinity - Precision accuracy
* Fixed stats on some alchemy stones
* Corrected Tungrad Earring name
* Fixed Ultimate Bronze Dagger special effect... Additional Speed Attack Damage 1% > Additional Special Attack Damage 1
* Fixed various GREEN quality secondary weapon enhancement values...
*  - Theos Ornamental Knot
*  - Parrying Dagger
*  - Krea Dagger
*  - Rhik Talisman
*  - Krea Talisman
*  - Blade Trinket
*  - Kite Shield
*  - White Horn Warrior Bow
*  - Tadd Shuriken
*  - Tadd Kunai
* Fixed Helm Destroyer’s Belt enhancement stats
* Fix for certain items ap/dp being in the wrong place and hiding gem slots on 0 slot items

### Changes

* Update outfit crystal slots, only the pearl shop combat one can have a slot in it.
* Updated gearscore calculation. calculate gearscore based on normal ap or awakening ap (whichever is higher) + dp total. Was previously just normal ap + dp total.
* Renamed Centaur's Belt to Centaurus Belt
* Accuracy update... accuracy values on weapons and accessories updated…to reflect current changes. Too many items to list, if it has accuracy it has been updated (don't think i missed any). (see <a href="https://community.blackdesertonline.com/index.php?threads/patch-notes-july-5th-2017.24889//" target="_blank">Patch Notes - Item Changes</a>)
* Minor database cleanup
* Moved to a new dynamic split database system, all database sections are now split into separate json files and rebuilt on the fly with php magic. :D
* Hide item effects and enhancement effects for items when they didn't have them.

## 1.2.0 (2017-05-19)

### New stuffs

* Added Striker Class and Weapons
* Added new offhand crystal (Spirit Crystal)
* Added new mediah necklace (Necklace of Dim Spell, Necklace of Concentrated Spell, Necklace of Sealed Spell)
* Added Helm Destroyer's Belt
* Added set bonus for the above items (belt and necklace)
* Added new craftable costumes.
* Enabled outfit crystal slot.

### Bugs

* Removed enhance prefix from gems on tooltip popups

### Changes

* Changed "Breath Gauge" stat to "Underwater Breathing"
* Updated Accuracy and Evasion stats on crystals and Alchemy Stones (Destruction / Protection) - (see <a href="https://community.blackdesertonline.com/index.php?threads/patch-notes-may-17th-2017-updated-on-18-05-17.2986/" target="_blank">Patch Notes - Item Changes</a>)
* Crystal cleanup, removed a bunch of crystals that don't appear to exist anywhere. (see <a href="https://github.com/Ihellmasker/BDO-Planner/commit/17c0feb539181b3c07b9f1e7f4d237d3dd4f04fb" target="_blank">This commit</a>)

## 1.1.3 (2017-04-19)

### New stuffs

* All the new free "Magical" Armors (Dim, Concentrated, Sealed, Roaring)
* All the new free "Magical" Secondary Weapons (Dim, Concentrated, Sealed)
* New HQ class icons
* Added Dark Knight class and their weapons
* Added WON, BON and JIN crystals
* Added simple versions of the craftable costumes (Jarette's/Delphe Knights/Thermian Casual etc), simple versions as in they're not class locked like in game. But it does the job. :)

### Changes / Bugs

* Fixed enhancement values on various items (probably too many to list)
* Changed "atk" stat to "hap" on various items
* Fixed incorrect gem slots on some items

## 1.1.2 (2017-01-25)

### Bugsssss

* Fixed the rounding issue with AP and Awakening AP... again... hopefully for the last time.
* Corrected Kutum weapons AP
* Corrected Wizard base resistances
* Corrected Rosar weapon enhancements

## 1.1.0 (2017-01-25)

### New stuffs

* All of the new Coral belts have been added

### Bugs D:

* Fixed an issue with Awakened AP being 1 lower than it should in certain circumstances

## 1.0.2 (2017-01-21)

### Fixed it, maybe?

* Gems will no longer reset when changing the enhancement levels of items

## 1.0.1 (2017-01-19)

### Bug fix time!

* Fixed an issue with searches being case sensitive
* Fixed an issue with item display in the popups on smaller resolutions

## 1.0.0 (2017-01-19)

### Notes

We've officially renamed to BDO Planner now with the intent to add more features outside of just planning your gear choices!

### Features

_There were lots of changes done since the last update, so it's possible we'll Kakao this update note and miss a lot of stuff._

* **Short links**, this is the big thing, short links have now been added. As theres no account system, they will be delete after 30 days of not being accessed just to stop our databases overflowing. As long as the links used though it won't be deleted.
* **Long links**, we have had to redo the long link structure and some of the database, so unfortunately all old links will be broken completely. Long links still exist, and unlike the short links, they're not temporary. Hopefully we shouldn't have to change anything again that will break links.
* **Item tooltips**. Finally! When you hover an item it will show a proper tooltip of the items stats!
* Fixed some bug with Alchemy Stone stats showing sometimes when they're not activated.
* **All resist** has changed slightly. If an item gave "all resist" before, it will now give the 4 resist categories separately to allow the calculation of your total resists to show properly.
  
### Visual changes

* **New class select screen**. We wanted something a bit more interesting to look at when you first open the page, so we made something a bit nicer here. Functionally it's still the same though.
* **Settings moved to new modal**. Just a small change we made as more tabs will be appearing for other things.
* **Saving moved to new modal**. Similar to above, we moved saving into it's own modal to remove the large text box from the footer, and because you can now generate short links on demand!
* Various other minor font and colour tweaks around the place.
* Change the styling on the enhancement sliders
  
### Back-end changes

_Just in case you follow the git more than just using it, here's some of the back-end things that were changed._

* Rewrote a lot of the database, now items are idenfitied by their ingame ID number rather than name, this allows for duplicate entries for things such as Alchemy Stones, it also allows for a more robust saving system rather than saving based on it's position in the database.
* Removed redundant data, we found a lot of redundant data in our databases, such as sets on items without sets, so we removed a lot! Probably still more to go though.

---

## 0.5.1 (2017-01-07)

Features

* Simplified costume pieces have been added, more will be coming soon. As all Pearl costumes give the same stats, we've simplified it into a single item regardless of class for now, we will be fully adding them at a later time though.
* More minor UI changes

## 0.5.0 (2017-01-03)

Features

* Added class base resistances to calculations
* Removed tooltips from Enhancement Sliders and added dividers to help, also added enhancement level into item names
* Rewrote the search/filter system completely, should notice massive performance increases now
* Added gear score, which is your AP + DP, for reference purposes
* Split stat displays into tabs
* Added remove button to unequip item
* Added Alchemy stones that can be toggled
* Added Compact mode for popups, enable this under settings!
  
Other things

* Updated to Bootstrap v4 Alpha5, this means the style has changed slightly but allows us to do some more stuff that we couldn't before.
* Rewrote the search/filter system completely, should notice massive performance increases now

## 0.4.0 (2016-12-21)

Features:

* Images for all items have been added! Everything looks nicer now!
* New Layout, the layout resembles the in-game display a bit more, and now uses a dark theme.
* Stat breakdown tooltips, when hovering on a stat you will see which of your items are providing that stat.
* Rarity filter will now let you search for items by their rarity.

## 0.3.4 (2016-12-15)

Features:

* Added displaying Enhancement levels ontop of equipment icons and on tooltips (IHellMasker)
* Added gear listing to show your current gear and gems (IHellMasker)

## 0.3.3.5 (2016-12-14)

Features:

* Added Search to gear and gem windows. (IHellmasker)
* Added simple tooltips to gear slots showing the item name. (IHellmasker)

Bug Fixes:

* Fixed Jarrette's accessory set bonus. (IHellmasker)

Changes:

* Hidden AP is now separate from "sheet" AP and shown in the Offensive stats section. (Shadowtrance)

## 0.3.3.4 (2016-12-06)

Features:

* Added Awakening weapons. (Shadowtrance)
* Fully implemented awakening ap calculation. (Shadowtrance)

Changes:

* Changed class selection on main page to image button style layout. (Shadowtrance)
* Share link now spans the full width due to removal of the class select dropdown list. (Shadowtrance)
* Changed equipment slots layout slightly to better accommodate the added awakening weapon slot. (Shadowtrance)

## 0.3.3.3 (2016-11-17)

Features:

* Added Ninja and Kunoichi classes. (Shadowtrance)
* Enhancement level up to +20 now for applicable items. (Shadowtrance)
* Small additions to main page, copy link button mainly. (Shadowtrance)
* Copy to clipboard and tooltip added to app.js. (Shadowtrance)
* Kunai (kunoichi) and Shuriken (Ninja) images added. (Shadowtrance)
* Huge item database update (basically every item available currently). Hopefully no issues here, there A LOT to add. :) (Shadowtrance)
* Crystal clean up in item database, corrected some, removed some that don't exist in game in any region that i know of yet. (Shadowtrance)
* Fixed saving and loading of "all" crystals for items. (SirMrE)

## 0.3.3.2 (2016-11-07)

Bug Fixes:

* Fixed the issue where gems which fits all slots would not work and throw an uncaught type error. (Shadowtrance)


## 0.3.3.1 (2016-10-08)

Bug Fixes:

* Fixed the issue where gems which fits all slots would not should on the list.


## 0.3.3 (2016-05-08)

Bug Fixes:

* Fixed the issue with sharelinks not saving primary and secondary weapons.


## 0.3.2 (2016-18-07)

Features:

* Added shareable links. You can now share you setup/build with others.
* Add hover tooltips on gear slots.

Changes:

* Refactored a large part of the app.js code.

Bug Fixes:

* removed console.log from debugging.


## 0.3.1.2 (2016-14-04)

Bug Fixes:

* Fixed wrong base stats for Witch's Earring (Thanks StoneSlayer!)


## 0.3.1.1 (2016-14-04)

Bug Fixes:

* Fixed wrong rarity on a couple of crystals (Thanks /user/l7arkSpirit!).
* Fixed Critical Hit Rate being displayed as % (Thanks /user/l7arkSpirit!).
* Fixed issue with armor crystals now being selectable (Thanks /user/l7arkSpirit!).


## 0.3.1 (2016-14-04)

Features:

* Added Musa/Maehwa items and classes.

Changes:

* Enhancement slider now updates as you slide instead on on release.


## 0.3.0.1 (2016-14-04)

Changes:

* Made the border around gear thicker.

Bug Fixes:

* Fixed a bug where gem slots would show when changing class.


## 0.3.0 (2016-14-04)

Features:

* Added gem system (Thanks to /user/l7arkSpirit on reddit for the gems design idea).

Bug Fixes:

* Fixed some minor display errors.


## 0.2.2 (2016-12-04)

Features:

* Added missing boss armor.


## 0.2.1 (2016-12-04)

Features:

* Added missing earrings.


## 0.2.0 (2016-12-04)

Features:

* Complete UI overhaul. This is an ongoing process.


## 0.1.1 (2016-09-04)

Features:

* Enhancement level dropdown will update based on the max enhancement level available for selected item.

Bug Fixes:

* Fixed error when enhancement level was higher than what was available for selected item.


## 0.1.0 (2016-09-04)

Features:

* Initial release.
