# ValhallaMMO-ItemsAdderFIX
让你的ValhallaMMO资源包不再与ItemsAdder冲突。

[English README](README.md)

## 这是什么？
这个神奇的扩展可以让你的ValhallaMMO资源包不再与你的ItemsAdder物品纹理冲突，也对其他使用IA的资源包生效（例如Slimefun资源包）

## 怎么使用？
0. 下载这个储存库并解压在你的服务器主机上

1. 将`valhallafix`文件夹放置在contents目录下，执行`/iareload`和`/iazip`并加载`generated.zip`资源包

2. 修改`ValhallaMMO`资源包，删除压缩包中`assets/minecraft/items`目录下的所有（现在暂时不是，不要删除`bow.json`和`crossbow.json`）文件，并将其加载在游戏中，置于`generated.zip`之上

3. 完事！现在你可以尽情地创建任何物品，而无需担心它会与ValhallaMMO纹理冲突

4. 建议使用BungeeResourcepacks或其他插件将资源包按正确的顺序发送给玩家

## 我遇到了问题！
请在此储存库下提交issue，而不是跑去ValhallaMMO的储存库，因为这个扩展是由我创建的，而不是Athlaeos。

## 为什么我在小于1.21.4的版本上使用出现问题？
这个扩展目前只是为我自己的服务器创建的，我的服务器版本是1.21.8，ValhallaMMO版本是1.6.4。

所以你在旧版或新版服务器/插件上使用时可能遇见一些小小的问题。

不过，如果你真的很需要，试着使用DeepSeek、ChatGPT或其他AI帮助你制作低版本扩展。

## 将来的计划
- 兼容弓和弩
- 将所有的`textures`方法替换成`model_path`方法
- 更多……
