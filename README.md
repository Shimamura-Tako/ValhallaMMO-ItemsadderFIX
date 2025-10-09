# ValhallaMMO-ItemsadderFIX
Make your ValhallaMMO resource pack no longer conflict with ItemsAdder.

[中文文档](README_zhcn.md)

## What is this?
This magical extension allows your ValhallaMMO resource pack to no longer conflict with your ItemsAdder item textures, and also works with other resource packs that use IA (such as the Slimefun resource pack).

## How to use?
0. Download this repository and extract it on your server host

1. Place the `valhallafix` folder in the `contents` directory, execute `/iareload` and `/iazip`, then load the `generated.zip` resource pack

2. Modify the ValhallaMMO resource pack by deleting all files in the `assets/minecraft/items` directory (currently not all files - do not delete `bow.json` and `crossbow.json` for now), then load it in the game above `generated.zip`

3. That's it! Now you can freely create any items without worrying about texture conflicts with ValhallaMMO

4. It is recommended to use BungeeResourcepacks or other plugins to send resource packs to players in the correct order.

## I'm encountering an issue!
Please submit an issue in this repository instead of going to ValhallaMMO's repository, because this extension was created by me, not by Athlaeos.

## Why am I having issues using it on versions below 1.21.4 (or equal to 1.21.9)?
This extension was initially created for my own server, which runs on version 1.21.8 with ValhallaMMO version 1.6.4.

Therefore, you might encounter some minor problems when using it on older or newer server/plugin versions.

However, if you really need it for lower versions, try using DeepSeek, ChatGPT, or other AI tools to help you create a compatible version for lower Minecraft versions.

## Future Plans
- Compatibility with bow and crossbow
- Replace all `textures` methods with `model_path` methods
- And more...
