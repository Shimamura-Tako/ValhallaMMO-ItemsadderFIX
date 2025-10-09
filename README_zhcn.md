# ValhallaMMO-ItemsAdderFIX
让你的ValhallaMMO资源包不再与ItemsAdder冲突。

[English README](README.md)

## 这是什么？
这个神奇的扩展可以让你的ValhallaMMO资源包不再与你的ItemsAdder物品纹理冲突，也对其他使用IA的资源包生效（例如Slimefun资源包）

## 怎么使用？
0. 下载这个储存库并解压在你的服务器主机上

1. 将`valhallafix`文件夹放置在contents目录下，执行`/iareload`和`/iazip`并加载`generated.zip`资源包

2. 修改`ValhallaMMO`资源包，删除压缩包中`assets/minecraft/items`目录下的所有（现在暂时不是，不要删除弓和弩）文件，并将其加载在游戏中，置于`generated.zip`之上

3. 完事！现在你可以尽情地创建任何物品，而无需担心它会与ValhallaMMO纹理冲突

## 为什么我在小于1.21.4的版本上使用出现问题？
这个扩展目前只是为我自己的服务器创建的，我的服务器版本是1.21.8。

不过，如果你真的很需要，试着使用DeepSeek、ChatGPT或其他AI帮助你制作低版本扩展。

又或者，ValhallaMMO的作者亲自来兼容IA和ValhallaMMO（不太可能）

## 将来的计划
- 兼容弓和弩
