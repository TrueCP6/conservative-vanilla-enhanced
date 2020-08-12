These features will work in singleplayer, on CVE servers, on vanilla servers and on realms when playing with a CVE client.

# Features for more casual players
## Controller support
To switch to and from controller input Options -> Controls -> Options and change the mode.

[![](https://media.forgecdn.net/attachments/277/282/2020-02-01_00.png)](https://www.curseforge.com/minecraft/mc-mods/lambdacontrols)

## Stats of a food are shown as the item's tooltip and in the hunger bar
![](https://camo.githubusercontent.com/61132c47ef7a1f43467d66f419df44bacf8d55c0/687474703a2f2f692e696d6775722e636f6d2f6675726f4141692e706e67)

## View your saturation level in your hunger bar
![](https://camo.githubusercontent.com/bde4595cfdcdd4e16a4b65955e9c1453b431b797/687474703a2f2f7a697070792e6766796361742e636f6d2f5368696d6d6572696e67596561726c794369636164612e676966)

## Subtle reverb in caves
[An example of the effect](https://youtu.be/mV0j4EIdLE8).

## Improved inventory management
- When hovering over items you can scroll up and down to send single items up and down
- When holding control you can move all stacks of the same type of item
- When you're in scrollable inventories you can press alt to prevent scrolling items
- When you're sending items via shift-leftclick you can now hold both buttons to send all stacks you're hovering over
- Hold alt-leftclick to drop items quickly
- When you're in the creative inventory and hover over the tab icons you can scroll through all the creative tabs and pages
- In  recipe books you can hover over the recipe grid to scroll through the pages and hover over the recipe group tabs to scroll through them.
- Sort inventories by clicking with your mouse wheel
    - By default sorts by raw id (will most likely group by mods and similar items)
    - Hold shift while clicking to sort by quantity
    - Hold control while clicking to sort by alphabet
- Press the swap key in any inventory to swap with the offhand
- Let your slots be automagically refilled from your inventory!
- Pick the matching tools for blocks by either sneaking while picking the block or by holding a tool. (this is configurable)
- Right-click trades or recipes to directly apply the crafting. When holding shift it will craft/trade a full stack

This was taken from the [Mouse Wheelie CurseForge page](https://www.curseforge.com/minecraft/mc-mods/mouse-wheelie).

## Discord rich presence integration
Your Discord status will display more information when playing. [PLACEHOLDER]

## Better crash handling
When the game crashes while in a world, you will just be sent back to the main menu instead of having to restart the game.

![](https://media.forgecdn.net/attachments/271/740/crash.png)

## Hide tutorials
Minecraft will no longer tell you how to play a game you've been playing for years.

## Screenshots are copied to clipboard
When you take a screenshot, the image will be copied to clipboard for easy pasting on to platforms like Discord.

## Offline skins
Your skin will still be visible when playing offline.

## Tab autocomplete for math equations in chat (use chat as a calculator)
3+3 -> TAB -> 6

4\*4= -> TAB -> 4\*4=16

Supports basic operations, exponents, square roots (`sqrt()`) and basic trigonometry functions (`sin()`, `cos()` and `tan()`).

## Sheared sheep will properly show their wool colour
![](https://i.imgur.com/hPfME5T.png)

## Bind commands to a hotkey
To create macros go to Mods -> Command Macros and then click the options icon in the top right of the screen. From here you can add as many macros as you like.

## View the stats of a horse in their inventory
![](https://media.forgecdn.net/attachments/268/918/donkey_inv.png)

## View the amount of bees and honey in a hive or nest in the item tooltip
![](https://media.forgecdn.net/attachments/274/614/beenfo-tooltip.png)

## Toggle between hold or toggle sneak and sprint with a hotkey
This can be configured in the controls menu.

## Moves chat up so it does not obscure the armor bar
![](https://raw.githubusercontent.com/gnembon/chat-up/master/chat-up.png)

## Smoother piston animations
[An example](https://youtu.be/lRvNknl0QPM?t=116).

## Colourful campfire smoke
Campfires' smoke will take on the colour of the block beneath it when powered.

![](https://media.giphy.com/media/URkCdfxP3vn41HPfif/giphy.gif)

## Place blocks in mid air in creative
Works like an angel block.

## Place blocks faster
A new block will be placed as soon as your cursor moves to an empty space.

## Fly speed presets
Change your fly speed by pressing `NUMPAD1`, `NUMPAD2`, `NUMPAD3` or `NUMPAD4`

## Scroll through hotbars
Press `ALT + Scroll Down` to scroll through your inventory hotbars.

## Restock stacks of items
When you run out of items in your hotbar a stack of the same type of item will automatically be pulled from your inventory.

## Reduced lava fog with respiration helmets
Also applies to any water breathing effects.

## Preview maps and shulker boxes in you inventory
Press shift when hovering over the item.

## Warning when potion effects are about to run out
Does not apply to ambient potion effects.

## Print your death co-ordinates to chat
Only visible to you.

## Zoom
Press `Z` to zoom.

## Enable auto swapping off of almost broken tools
To enable: `X + C` -> `Tweak Toggles` -> `tweakSwapAlmostBrokenTools`.

## Less slowdown when walking on slime blocks
Makes slimeblocks more viable to use as scaffolding.

# Features for more technical players
## Schematics!
[![](https://media.forgecdn.net/attachments/274/406/2020-01-02_21.png)](https://youtu.be/aMZSXAKZzpo?t=155)

## Custom superflat presets
To add presets: `X + C` -> `Lists` -> `flatWorldPresets`.

## Condensed F3-like screen with more information
Can display standard F3 information in a easier to read format as well as server TPS and MSPT, whether the player is in a slime chunk, ping to server, player speed, IRL time, ingame time and more. To configure: `H + C` -> `Tweak Toggles`. Info toggles can also be bound to hotkeys in the `Info Hotkeys` tab.

## Structure bounding box overlays
Press `B` to enable the rendering of all structure bounding box overlays. To enable for individual generated structures press `H + C` -> `Structures`.

## Other overlays
In `H + C` -> `Renderer Hotkeys` the following overlay toggles can be bound.
- Light level
- Slime chunks
- Pathfinding debug
- Water debug
- Block grid
- Random tick range
- Region file boundaries
- Spawn chunks