# ValhallaMMO-ItemsadderFIX
Make your ValhallaMMO resource pack no longer conflict with ItemsAdder.

[中文文档](readme_zhcn.md)

## What is this?
This magical extension allows your ValhallaMMO resource pack to no longer conflict with your ItemsAdder item textures, and also works with other resource packs that use IA (such as the Slimefun resource pack).

## How to use?
0. Download this repository and extract it on your server host

1. Place the `valhallafix` folder in the `contents` directory, execute `/iareload` and `/iazip`, then load the `generated.zip` resource pack

2. Modify the ValhallaMMO resource pack by deleting all files in the `assets/minecraft/items` directory (currently not all files - do not delete equipment, tools, weapons, and gray/lime dye files for now), then load it in the game above `generated.zip`

3. That's it! Now you can freely create any items without worrying about texture conflicts with ValhallaMMO

## Why am I having issues using it on versions below 1.21.4?
This extension was initially created for my own server, which runs on version 1.21.8.

However, if you really need it for lower versions, try using DeepSeek, ChatGPT, or other AI tools to help you create a compatible version for lower Minecraft versions.

Alternatively, the ValhallaMMO author could officially support compatibility with IA and ValhallaMMO (though this is unlikely).

## Future Plans
- Compatibility with all material equipment, tools, and weapons
- Compatibility with gray/lime dye
