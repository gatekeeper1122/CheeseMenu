# CheeseMenu
Cheese menu is a UI made for the 2take1 lua api, it is supposed to be as close as possible in usage to the 2t1 api to support luas not made for it.

## Preview
![GTA5_kzYH52SWMf](https://user-images.githubusercontent.com/71855034/176974636-6d80196e-fd48-47d6-8767-f18206ce5b81.png)
![GTA5_w4gl9vnclG](https://user-images.githubusercontent.com/71855034/177609082-edf75130-73b7-4d0d-afcb-69ec9abe4d8c.png)

Note: other scripts seen loaded here do not come with cheese menu.

## Usage
If you are a lua dev then using this is quite close to using the 2t1 api
- Differences to 2t1
  - menu.get_feature_by_hierarchy_key
    - if duplicates are found it'll return the first one created
    - its hierarchy keys are case sensitive and not all lowercase like 2t1's
    - it'll look for cheesemenu features first, if not found, it'll use the original 2t1 function
 


How to install
1. Download by going to [Releases](https://github.com/GhustOne/CheeseMenu/releases) and downloading cheesemenu.zip on the latest release
2. Simply put `cheesemenu.lua` and `cheesemenu` folder that are in the downloaded zip in the scripts folder for 2t1 and load it

Any scripts loaded after will be embedded in cheesemenu

Controls are in Script Features > Cheese Menu > Controls

## Customizability
Cheese menu is quite customizable, it allows mutli frame headers, backgrounds and changing just about any color

If you wish to use multi frame headers I added an example, fps can go below 1 if you want the header to change every now and then


![GTA5_p6I2g4HpkE](https://user-images.githubusercontent.com/71855034/176974874-7b72c742-fdbc-4cb9-a7b3-3fa0f9efd431.png)
![GTA5_gAofqF8R8a](https://user-images.githubusercontent.com/71855034/176974877-9fc5c686-910d-4448-966c-2670bf4fa8ee.png)

## Hotkey system
Since this is separate from 2t1 and many lua scripts rely on 2t1's hotkeys I've made an extremely similar hotkey system for cheese menu.
- F11 on a feature will set a hotkey
- Shift + F11 will remove a hotkey if it exists
- Ctrl + F11 will show a hotkey if it exists

Hotkeys will be saved automatically

## Credits
- Kektram - for teaching me the basics of lua, I only started because of him.

- Proddy - telling me about many bad habits in lua and helping even though he hates the concept of cheesemenu

- Rimuru - only got the idea because of her UI, learnt some stuff from it too 
