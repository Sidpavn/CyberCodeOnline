# Update Notes

**CyberCode Online** is currently under an early and heavy development stage, which means many changes and new features are being added every day! That also means many stats are being adjusted all the time. So, if you have anything to suggest, feel free to [create an issue](https://github.com/DexterHuang/CyberCodeOnline/issues) or join our [Discord server](https://discord.link/cco).

Fancy helping out with running costs? [Buy me a potato](https://www.buymeacoffee.com/cybercodeonline) or [subscibe to my Patreon](https://www.patreon.com/cybercodeonline/).

### Help Needed:
 * contribution/words.json - Random Words
 * contribution/dungeon/layout/structure-mask.json - Dungeon Layouts
 * contribution/notes/* - In Dungeon Lore
 * contribution/mobile/tips.md - Tips for Mobile
 * contribution/lang/* - Localisations
 * tips.txt - Tips for desktop
 * mobile-tutorial/* - Mobile Tutorial
 * tutorial/* - Desktop Tutorial

**Remember to add your name to the ['Credits.md'](https://github.com/DexterHuang/CyberCodeOnline/blob/master/Credits.md) doc when you create a PR**

If you would like to help to maintain CyberCode Online, please feel free to submit a PR at [our GitHub repo](https://github.com/DexterHuang/CyberCodeOnline).

## Updates Log 

### **2021/05/20- v0.531**
 * NEW - `Item Calibration`, you may now access `Equipment Workbench` from your `Gang Headquarter`, insert a `Equipment Calibration Core` to activate the wrokbench, once activated, you may use it to `Calibrate` one of item of your choice, each item has differen `Calibration Capacity` varies base on thier Tier, 
 * *IMPORTANT* if calibration fails, your item will be destoryed, ireversable 
 * Added `Calibration AI Shard`, after activating this you will get a stackable buff that increase the success chance of calibration
 * Added `Equipment Calibration Core` drops from enemies, used for item calibration
 * Updated item detail UI, now shows clearly where each attribution is coming from:
    - white - total
    - grey - attachment
    - yellow - calibration
 * Item list now shows attachment icon dots


### **2021/05/20- v0.487**
 * Fixed typo on dungeon 2.5x exp -> 2.0x exp, its not a nerf its wrong since long ago (exp is unchanged only increased by 10% from previous patch)
 * You can now join gang dungeon with no level requirement
 * Remove exp memory from gang dungeon 
 * Decreases all skill required exp to level up!
 * Increase AI Core bitcoin drop by 30%

### **2021/05/19- v0.487**
 * Increase exp gain from killing enemies by 10%
 * Decresed Bitcoin gain from AI Cores

### **2021/05/18- v0.487**
 * Decreased gang related item's droprate in crates, but drastic increase in boss drops
 * Fixed `Gang Memory Shard` not spawning correctly
 * Upgraded the email server (All your mail history will be lost, it's expected)
 * Boss XP gain has been doubled in dungeons

### **2021/05/17- v0.487**
 * Now clicking on player's gang tag in chat message title will navigate you to the respective gang's details page
 * Entering gang dungeons will now consume a `Gang Invasion Order Transmitter`
 * Entering gang dungeons created by a gang member will no longer require you to have `Gang Invasion Order Transmitter`
 * More optimization
 * Fixed an issue regarding loading a name which is either changed or the player is already banned in the gang member page

### **2021/05/16- v0.487**
 * Added `Gang Headquarter`.
 * Gangs now require an upkeep fee and resource, the fee and resources required depends on the member count
 * Added `Gather Resouce` action in `Gang Headquarter`. This action gives resource to your gang
 * Added `Gang Dungeon`, a high difficulty dungeon, that is bigger and deeper with a stronger boss. The boss is guaranteed for rare+ drops and requires `Gang Invasion Transmitter`, and only accessible to gang members.
 * Added `Gang Invasion Transmitter`, it only drops in the loot room of challenge dungeons, use this to enter the gang dungeon
 * Added gang levels, now gangs can be leveled up based on players actions
 * Player tag now shows gang level

### **2021/05/13- v0.487**
 * Removed unit amount from player profiles on the web version

### **2021/05/12- v0.487**
 * Nametags now have distinct colors if the tagged player is a donator
 * Potential fix to dungeon crash issue
 * Updated level exp bar UI on the profile page


### **2021/05/11- v0.487**
 * Added icons for travelling
 * Added a prompt to change language when your system language isn't english
 * Fix the bug where you can click edit bio on other player's profile
 * Made the circuit background more noticeable
 * Changed the color of the AFK loading bar to improve readability
 * Change the brightness of red to increase readability

### **2021/05/10- v0.487**
 * New Death Screen design
 * Updated AFK progress bar design
 * Updated level stats display
 * Added Icons for NPCs
 * Minor `AI Core` nerf
 * Added Bio to profile (available only to donation tier `Elite` and above)
 * Added barcode decoraction (available only to donation tier `Elite` and above)
 * Added Level up screen
 * Fixed bugged enemies, causing the player to crash until the dungeon expires
 * Fixed bugged dungeons stuck in the map

### **2021/05/07- v0.487**
 * Added an animation for attacking and receiving damage
 * Added an indication when health is low during combat
 * Bitcoins are now required to unlock all Locked Containers
 * Added a limit to the number of Locked Containers that can be unlocked in one go
